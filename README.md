local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = Nimdas hub
🥓", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest", IntroText = "Welcome to Nimdas Universal Script!"})

local Tab = Window:MakeTab({
	Name = "Tab 1",
	Icon = "rbxassetid://7733954611",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Universal Scripts"
})

--[[
Name = <string> - The name of the section.
]]

OrionLib:MakeNotification({
	Name = "BaconPartnerr's Universal Script!",
	Content = "BaconScriptsPartnerr",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddButton({
	Name = "Fly Script 🕊️",
	Callback = function()
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Walk On Walls 🧱",
	Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]] 

Tab:AddButton({
	Name = "Rewind time ⏰",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/L"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "AntiLag",
	Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/8YZ2cc6V"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({ Name = "Infinite Yield ♾️", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))() print("button pressed") end
})

--[[ Name = - The name of the button. Callback = - The function of the button. ]]

local Tab = Window:MakeTab({
	Name = "Tab 2",
	Icon = "rbxassetid://7743869054",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Doors"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Utilities Hub ⌚",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/plamen6789/UtilitiesHub/main/UtilitiesGUI'))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Mspaint 🎨",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercortent.com/notpoiu/mspaint/main/main.lua"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Kardin X lolcat 😺 🙍",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()
local window = DrRayLibrary:Load("Leaf hub", "Default")

local tab = DrRayLibrary.newTab("Main", "4483345998")

tab.newButton("Death autofarm", "Execute in lobby then join a singleplayer game (use mods for more knobs)", function()
   
task.spawn(queue_on_teleport or syn and syn.queue_on_teleport, game:HttpGet("https://raw.githubusercontent.com/ActualMasterOogway/Scripts/main/Doors/Death-Farm.lua"))
end)

tab.newButton("crucifix anything", "hold Q and left click on anything", function()
_G.Uses = 414141414141
_G.Range = 30
_G.OnAnything = true
_G.Fail = false
_G.Variant = "Electric"
loadstring(game:HttpGet('https://raw.githubusercontent.com/PenguinManiack/Crucifix/main/Crucifix.lua'))()
end)

tab.newButton("mspaint V2", "Old goated doors script new update", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/notpoiu/mspaint/main/main.lua"))()
end)

tab.newButton("Kaiden shader", "kaiden famous doors hacker lolcat friend shader script", function()
local Bloom = Instance.new("BloomEffect", game.Lighting)
Bloom.Intensity = 0.12
Bloom.Size = 9e9
Bloom.Threshold = 0.05

local DepthOfField = Instance.new("DepthOfFieldEffect", game.Lighting)
DepthOfField.FarIntensity = 0.3
DepthOfField.FocusDistance = 20
DepthOfField.InFocusRadius = 0
DepthOfField.NearIntensity = 0

local SunRays = Instance.new("SunRaysEffect", game.Lighting)
SunRays.Intensity = 0.1
SunRays.Spread = 0.8

local ColorCorrection = Instance.new("ColorCorrectionEffect", game.Lighting)
ColorCorrection.Brightness = 0.025
ColorCorrection.Contrast = 0.13
ColorCorrection.Saturation = 0.15

game.Lighting.GlobalShadows = false
game.Lighting.OutdoorAmbient = Color3.fromRGB(35, 35, 45)
end)

tab.newButton("Grumble spawner", "Spawns grumbles (they dont deal damage) click Q to spawm use the sword to dispawn them", function()
-- Q TO SPAWN

local Speed = 12

local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local Debris = game:GetService("Debris")
local UserInputService = game:GetService("UserInputService")

local Player = Players.LocalPlayer
local Character = Player.Character or Player.CharacterAdded:Wait()

local Sword = game:GetObjects("rbxassetid://72674416931709")[1]

local Cache = game:GetObjects("rbxassetid://96223289630255")[1]
local Cache2 = game:GetObjects("rbxassetid://103869039972033")[1]

Cache:Destroy()
Cache2:Destroy()

Sword.Parent = Player.Backpack

task.spawn(function()
	local Tool = Sword
	local Handle = Tool:WaitForChild("Handle")
	local Humanoid = Character.Humanoid
	local Torso = Character:FindFirstChild("Torso") or Character:FindFirstChild("HumanoidRootPart")

	local function Create(ty)
		return function(data)
			local obj = Instance.new(ty)
			for k, v in pairs(data) do
				if type(k) == 'number' then
					v.Parent = obj
				else
					obj[k] = v
				end
			end
			return obj
		end
	end

	local BaseUrl = "rbxassetid://"

	local DamageValues = {
		BaseDamage = 5,
		SlashDamage = 10,
		LungeDamage = 30
	}

	local Animations = {
		R15Slash = 522635514,
		R15Lunge = 522638767
	}

	local Damage = DamageValues.BaseDamage

	local Grips = {
		Up = CFrame.new(0, 0, -1.70000005, 0, 0, 1, 1, 0, 0, 0, 1, 0),
		Out = CFrame.new(0, 0, -1.70000005, 0, 1, 0, 1, -0, 0, 0, 0, -1)
	}

	local Sounds = {
		Slash = Handle:WaitForChild("SwordSlash"),
		Lunge = Handle:WaitForChild("SwordLunge"),
		Unsheath = Handle:WaitForChild("Unsheath")
	}

	local ToolEquipped = false

	Tool.Grip = Grips.Up
	Tool.Enabled = true

	local function IsTeamMate(Player1, Player2)
		return (Player1 and Player2 and not Player1.Neutral and not Player2.Neutral and Player1.TeamColor == Player2.TeamColor)
	end

	local function TagHumanoid(humanoid, player)
		local Creator_Tag = Instance.new("ObjectValue")
		Creator_Tag.Name = "creator"
		Creator_Tag.Value = player
		Debris:AddItem(Creator_Tag, 2)
		Creator_Tag.Parent = humanoid
	end

	local function UntagHumanoid(humanoid)
		for i, v in pairs(humanoid:GetChildren()) do
			if v:IsA("ObjectValue") and v.Name == "creator" then
				v:Destroy()
			end
		end
	end

	local function CheckIfAlive()
		return (((Player and Player.Parent and Character and Character.Parent and Humanoid and Humanoid.Parent and Humanoid.Health > 0 and Torso and Torso.Parent) and true) or false)
	end

	local function Blow(Hit)
		if not Hit or not Hit.Parent or not CheckIfAlive() or not ToolEquipped then
			return
		end
		local RightArm = Character:FindFirstChild("Right Arm") or Character:FindFirstChild("RightHand")
		if not RightArm then
			return
		end
		local RightGrip = RightArm:FindFirstChild("RightGrip")
		if not RightGrip or (RightGrip.Part0 ~= Handle and RightGrip.Part1 ~= Handle) then
			return
		end
		local character = Hit.Parent
		if character == Character then
			return
		end
		local humanoid = character:FindFirstChildOfClass("Humanoid")
		if not humanoid or humanoid.Health == 0 then
			return
		end
		local player = Players:GetPlayerFromCharacter(character)
		if player and (player == Player or IsTeamMate(Player, player)) then
			return
		end
		UntagHumanoid(humanoid)
		TagHumanoid(humanoid, Player)
		humanoid:TakeDamage(Damage)	
	end

	local function Attack()
		Damage = DamageValues.SlashDamage
		Sounds.Slash:Play()

		if Humanoid then
			if Humanoid.RigType == Enum.HumanoidRigType.R6 then
				local Anim = Instance.new("StringValue")
				Anim.Name = "toolanim"
				Anim.Value = "Slash"
				Anim.Parent = Tool
			elseif Humanoid.RigType == Enum.HumanoidRigType.R15 then
				local Anim = Tool:FindFirstChild("R15Slash")
				if Anim then
					local Track = Humanoid:LoadAnimation(Anim)
					Track:Play(0)
				end
			end
		end	
	end

	local function Lunge()
		Damage = DamageValues.LungeDamage

		Sounds.Lunge:Play()

		if Humanoid then
			if Humanoid.RigType == Enum.HumanoidRigType.R6 then
				local Anim = Instance.new("StringValue")
				Anim.Name = "toolanim"
				Anim.Value = "Lunge"
				Anim.Parent = Tool
			elseif Humanoid.RigType == Enum.HumanoidRigType.R15 then
				local Anim = Tool:FindFirstChild("R15Lunge")
				if Anim then
					local Track = Humanoid:LoadAnimation(Anim)
					Track:Play(0)
				end
			end
		end	

		wait(0.2)
		Tool.Grip = Grips.Out
		wait(0.6)
		Tool.Grip = Grips.Up

		Damage = DamageValues.SlashDamage
	end

	Tool.Enabled = true
	local LastAttack = 0

	local function Activated()
		if not Tool.Enabled or not ToolEquipped or not CheckIfAlive() then
			return
		end
		Tool.Enabled = false
		local Tick = RunService.Stepped:wait()
		if (Tick - LastAttack < 0.2) then
			Lunge()
		else
			Attack()
		end
		LastAttack = Tick
		Damage = DamageValues.BaseDamage
		local SlashAnim = (Tool:FindFirstChild("R15Slash") or Create("Animation"){
			Name = "R15Slash",
			AnimationId = BaseUrl .. Animations.R15Slash,
			Parent = Tool
		})

		local LungeAnim = (Tool:FindFirstChild("R15Lunge") or Create("Animation"){
			Name = "R15Lunge",
			AnimationId = BaseUrl .. Animations.R15Lunge,
			Parent = Tool
		})
		Tool.Enabled = true
	end

	local function Equipped()
		if not CheckIfAlive() then
			return
		end
		ToolEquipped = true
		Sounds.Unsheath:Play()
	end

	local function Unequipped()
		Tool.Grip = Grips.Up
		ToolEquipped = false
	end

	Tool.Activated:Connect(Activated)
	Tool.Equipped:Connect(Equipped)
	Tool.Unequipped:Connect(Unequipped)

	Handle.Touched:Connect(Blow)
end)

UserInputService.InputBegan:Connect(function(input, gP)
	if input.KeyCode == Enum.KeyCode.Q and not gP then
		local Dummy = game:GetObjects("rbxassetid://96223289630255")[1]
		local Grumbo = game:GetObjects("rbxassetid://103869039972033")[1]

		Dummy.Parent = workspace
		Grumbo.Parent = workspace

		Dummy.HumanoidRootPart.CFrame = Character.HumanoidRootPart.CFrame + Vector3.new(math.random(-15, 15), 0, math.random(-15, 15))

		task.wait()

		local Idle = Grumbo.GrumbleRig.AnimationController.Animator:LoadAnimation(Grumbo.GrumbleRig.Idle)
		Idle.Looped = true
		Idle:Play()

		local Blink = Grumbo.GrumbleRig.AnimationController.Animator:LoadAnimation(Grumbo.GrumbleRig.Blink)

		local Stun = Grumbo.GrumbleRig.AnimationController.Animator:LoadAnimation(Grumbo.GrumbleRig.Stun)

		task.spawn(function()
			while Grumbo:IsDescendantOf(workspace) do
				task.wait(math.random(2, 5))
				Blink:Play()
			end
		end)

		local function followPlayer()
			local Direction = (Character.HumanoidRootPart.Position - Dummy.HumanoidRootPart.Position).unit
			Dummy.HumanoidRootPart.Velocity = Direction * Speed
			Dummy.HumanoidRootPart.CFrame = CFrame.new(Dummy.HumanoidRootPart.Position, Character.HumanoidRootPart.Position)
		end

		Dummy.Humanoid:GetPropertyChangedSignal("Health"):Connect(function()
			if Dummy.Humanoid.Health <= 0 then
				Stun:Play()
				task.wait(1)
				Dummy:Destroy()
				Grumbo:Destroy()
			end
		end)

		RunService.RenderStepped:Connect(function()
			if Grumbo:IsDescendantOf(workspace) and Dummy:IsDescendantOf(workspace) and Dummy:FindFirstChild("HumanoidRootPart") and Dummy:FindFirstChild("Humanoid").Health > 0 then
				local Distance = (Character.HumanoidRootPart.Position - Dummy.HumanoidRootPart.Position).magnitude

				if Distance <= math.huge then
					followPlayer()
				end

				Grumbo:PivotTo(Dummy.HumanoidRootPart.CFrame)
			end
		end)
	end
end)
end)

tab.newButton("Enable floor 2 (The mines)", "Get floor 2 without the badge", function()
CustomModifiers:EnableFloor("Mines", true)
end)

tab.newButton("Enable floor 0 (Backdoor)", "Get floor 0 without the badge", function()
CustomModifiers:EnableFloor("Backdoor", true)
end)
      		print("button pressed")
  	end    
})

local Tab = Window:MakeTab({
	Name = "Tab 3",
	Icon = "rbxassetid://7734058599",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Strongest Battlesgrounds 💪"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "KadeHub ☠️",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
----<< LOADER >> -----
if getgenv().KadeHubLoaded ~= true then
    getgenv().KadeHubLoaded = true
   loadstring(game:HttpGet("https://raw.githubusercontent.com/skibiditoiletfan2007/Work/main/latest.lua"))()
else
    game.StarterGui:SetCore("SendNotification",  { Title = "KadeHub"; Text = "KadeHub is already executed!"; Icon = "rbxassetid://17893547380"; Duration = 15; })
end
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Phantasm Hub 👻",
	Callback = function()
getgenv().ToggleKeybind = Enum.KeyCode.RightControl
getgenv().FreeEmotesTab = true -- if you want free emotes turn this to true

--// https://discord.gg/bntsEjwnA5 (you should join forreal real....)

loadstring(game:HttpGet("https://raw.githubusercontent.com/ATrainz/main/main/Phantasm-Loader.lua"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Tab 4",
	Icon = "rbxassetid://7733964808",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Pet simulator 99 😺🐶"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Redz Hub 🍒",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Halloween Special (limited)",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Pet-Simulator-99!-Cheat-Menu-17428"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Tab 5",
	Icon = "rbxassetid://7733955664",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "slap battles 👏"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Giang hub 🙏",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/Giangplay/Slap_Battles/main/Slap_Battles.lua"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Kykyryz0B hub",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/KykyryzoB/KykyryzoB-Hub-SB/main/KykryzoB.lua"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Voxul Hub 🟣 (SR only)",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet('https://raw.githubusercontent.com/Voxul/VoxulHub/main/loader.lua'))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Tab 6",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Blade ball 🏀"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Zyphrantis Hub 🥓!",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/bankboi001fr/bankboi001fr/refs/heads/main/Loader",true))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "plutonium Hub🌅 (Random Scripts just search)",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/PawsThePaw/Plutonium.AA/main/Plutonium.Loader.lua", true))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Tab 7",
	Icon = "rbxassetid://7734058345",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Mm2 🔪"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Highlight hub 🐈‍⬛ (hlvipcomingsoon)",
	Callback = function()
--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/ThatSick/HighlightMM2/main/Main"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "XXX , I meant... Xhub ♥️",
	Callback = function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

local Tab = Window:MakeTab({
	Name = "Tab 8",
	Icon = "rbxassetid://7743872929",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "Blox fruits 🍑"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Azure Hub 🔵",
	Callback = function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Blox-Fruits-w-azure-hub-10114"))()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]
Tab:AddButton({
	Name = "Redz Hub 🍒 (Blox fruit)",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Blox-Fruits-RedzHub-No-Key-Autofarm-17214"))()
      		print("button pressed")
  	end    
})
