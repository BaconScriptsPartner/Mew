local Luna = loadstring(game:HttpGet("https://raw.githubusercontent.com/Nebula-Softworks/Luna-Interface-Suite/refs/heads/master/source.lua", true))()

local Window = Luna:CreateWindow({
	Name = "Luna Example Window", -- This Is Title Of Your Window
	Subtitle = nil, -- A Gray Subtitle next To the main title.
	LogoID = "82795327169782", -- The Asset ID of your logo. Set to nil if you do not have a logo for Luna to use.
	LoadingEnabled = true, -- Whether to enable the loading animation. Set to false if you do not want the loading screen or have your own custom one.
	LoadingTitle = "Luna Interface Suite", -- Header for loading screen
	LoadingSubtitle = "by Nebula Softworks", -- Subtitle for loading screen
	ConfigSettings = {
		RootFolder = nil, -- The Root Folder Is Only If You Have A Hub With Multiple Game Scripts and u may remove it. DO NOT ADD A SLASH
		ConfigFolder = "Big Hub" -- The Name Of The Folder Where Luna Will Store Configs For This Script. DO NOT ADD A SLASH
	},
	KeySystem = false, -- As Of Beta 6, Luna Has officially Implemented A Key System!
	KeySettings = {
		Title = "Luna Example Key",
		Subtitle = "Key System",
		Note = "Best Key System Ever! Also, Please Use A HWID Keysystem like Pelican, Luarmor etc. that provide key strings based on your HWID since putting a simple string is very easy to bypass",
		SaveInRoot = false, -- Enabling will save the key in your RootFolder (YOU MUST HAVE ONE BEFORE ENABLING THIS OPTION)
		SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
		Key = {"Example Key"}, -- List of keys that will be accepted by the system, please use a system like Pelican or Luarmor that provide key strings based on your HWID since putting a simple string is very easy to bypass
		SecondAction = {
			Enabled = true, -- Set to false if you do not want a second action,
			Type = "Link", -- Link / Discord.
			Parameter = "" -- If Type is Discord, then put your invite link (DO NOT PUT DISCORD.GG/). Else, put the full link of your key system here.
		}
	}
})

local Tab = Window:CreateTab({
	Name = "tab 1",
	Icon = "view_in_ar",
	ImageSource = "Material",
	ShowTitle = true -- This will determine whether the big header text in the tab will show
})

Tab:CreateSection("Section")
Section:Set("universal")
Section:Destroy() -- Destroys the section

local Button = Tab:CreateButton({
	Name = "Wall walker",
	Description = nil, -- Creates A Description For Users to know what the button does (looks bad if you use it all the time),
    	Callback = function()
	 loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
         -- The function that takes place when the button is pressed
    	end
})

local Button = Tab:CreateButton({
	Name = "rewind time",
	Description = nil, -- Creates A Description For Users to know what the button does (looks bad if you use it all the time),
    	Callback = function()	 loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/L"))() 
         -- The function that takes place when the button is pressed
    	end
})

local Button = Tab:CreateButton({
	Name = "stream sniper︻デ═一",
	Description = nil, -- Creates A Description For Users to know what the button does (looks bad if you use it all the time),
    	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Guest3D/ZirconHub/refs/heads/main/StreamSniper.lua"))() 
         -- The function that takes place when the button is pressed
    	end
})

local Button = Tab:CreateButton({
	Name = "Anti Lag",
	Description = nil, -- Creates A Description For Users to know what the button does (looks bad if you use it all the time),
    	Callback = function()
	 loadstring(game:HttpGet("https://pastebin.com/raw/8YZ2cc6V"))()
         -- The function that takes place when the button is pressed
    	end
})

local Tab = Window:CreateTab({
	Name = "tab 2",
	Icon = "view_in_ar",
	ImageSource = "Material",
	ShowTitle = true -- This will determine whether the big header text in the tab will show
})

Tab:CreateSection("Section")
Section:Set("slap battles👋")
Section:Destroy() -- Destroys the section

local Button = Tab:CreateButton({
	Name = "Giang hub",
	Description = nil, -- Creates A Description For Users to know what the button does (looks bad if you use it all the time),
    	Callback = function()	 loadstring(game:HttpGet("https://raw.githubusercontent.com/Giangplay/Slap_Battles/main/Slap_Battles.lua"))()
         -- The function that takes place when the button is pressed
    	end
})
