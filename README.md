--main

local Settings = {
  JoinTeam = "Pirates"; -- Pirates/Marines
  Translator = true; -- true/false
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/newredz/BloxFruits/refs/heads/main/Source.luau"))(Settings)

local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
end 


--Tabs


local Tabs = {
    Main = Window:AddTab({ Title = "Scripting" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
end

--notificao

local Toggle = Tab:AddToggle("Tokyto", 
{
    Title = "HubMain", 
    Description = "Toggle description",
    Default = false, -- esse "," e preciso coloque em qualquer situação 
    Callback = function(state)
	if state then
	    print("Script On")
	else
	    print("script  Off")
        end
    end 
})
