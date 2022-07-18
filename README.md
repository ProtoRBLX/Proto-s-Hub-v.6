game:GetService("StarterGui"):SetCore("SendNotification", { 
	Title = "Script Loaded";
	Text = "SCRIPTS HERE AREN'T GUARANTEED WORKING";
	Icon = "rbxthumb://type=Asset&id=72382659&w=150&h=150"})
Duration = 16;


local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Thumbnail = Instance.new("ImageLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local BloxFruits = Instance.new("TextButton")
local Aresenal = Instance.new("TextButton")
local AnimeFight = Instance.new("TextButton")
local KingLegacy = Instance.new("TextButton")
local babf = Instance.new("TextButton")
local Shindo = Instance.new("TextButton")
local HotelEl = Instance.new("TextButton")
local Animesim = Instance.new("TextButton")
local jb = Instance.new("TextButton")
local MM2 = Instance.new("TextButton")
local brook = Instance.new("TextButton")
local Meepcity = Instance.new("TextButton")
local petsim = Instance.new("TextButton")
local tohell = Instance.new("TextButton")
local bw = Instance.new("TextButton")
local Beeswarm = Instance.new("TextButton")
local sonic = Instance.new("TextButton")
local Dahood = Instance.new("TextButton")
local LabelMain = Instance.new("TextLabel")
local ScrollingFrame2 = Instance.new("ScrollingFrame")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")
local TextButton_7 = Instance.new("TextButton")
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
local Page1 = Instance.new("TextButton")
local Page2 = Instance.new("TextButton")
local Home = Instance.new("TextButton")
local scriptsother = Instance.new("Frame")
local otherscripts = Instance.new("TextLabel")
local v3 = Instance.new("TextButton")
local v5 = Instance.new("TextButton")
local v4 = Instance.new("TextButton")
local sprintscript = Instance.new("TextButton")
local Spyx = Instance.new("TextButton")
local FruityWare = Instance.new("TextButton")
local Others = Instance.new("TextButton")
local homeframe = Instance.new("Frame")
local w = Instance.new("TextLabel")
local TextLabel = Instance.new("TextLabel")
local sub = Instance.new("TextLabel")
local x = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui

MainFrame.Name = "Main Frame"
MainFrame.Parent = ScreenGui
MainFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MainFrame.BorderColor3 = Color3.fromRGB(255, 0, 0)
MainFrame.Position = UDim2.new(0.237309664, 0, 0.312871277, 0)
MainFrame.Size = UDim2.new(0, 414, 0, 204)
MainFrame.Active = true
MainFrame.Draggable = true

UICorner.CornerRadius = UDim.new(0, 11)
UICorner.Parent = MainFrame

Thumbnail.Name = "Thumbnail"
Thumbnail.Parent = MainFrame
Thumbnail.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Thumbnail.BorderColor3 = Color3.fromRGB(255, 0, 0)
Thumbnail.BorderSizePixel = 3
Thumbnail.Position = UDim2.new(0.0628019348, 0, 0.0539215691, 0)
Thumbnail.Size = UDim2.new(0, 90, 0, 90)
Thumbnail.Image = "http://www.roblox.com/asset/?id=5163036189"

ScrollingFrame.Parent = MainFrame
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScrollingFrame.BorderColor3 = Color3.fromRGB(255, 0, 0)
ScrollingFrame.Position = UDim2.new(0.341737598, 0, 0.19898665, 0)
ScrollingFrame.Size = UDim2.new(0, 253, 0, 150)
ScrollingFrame.Visible = false
ScrollingFrame.CanvasPosition = Vector2.new(0, 258)

BloxFruits.Name = "BloxFruits"
BloxFruits.Parent = ScrollingFrame
BloxFruits.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
BloxFruits.BorderColor3 = Color3.fromRGB(255, 0, 0)
BloxFruits.BorderSizePixel = 2
BloxFruits.Position = UDim2.new(0.0316205546, 0, 0.0171568636, 0)
BloxFruits.Size = UDim2.new(0, 86, 0, 32)
BloxFruits.Font = Enum.Font.SourceSans
BloxFruits.Text = "Blox Fruits"
BloxFruits.TextColor3 = Color3.fromRGB(255, 0, 0)
BloxFruits.TextSize = 14.000
BloxFruits.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/ATR",true))()
end)

Aresenal.Name = "Aresenal"
Aresenal.Parent = ScrollingFrame
Aresenal.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Aresenal.BorderColor3 = Color3.fromRGB(255, 0, 0)
Aresenal.BorderSizePixel = 2
Aresenal.Position = UDim2.new(0.588932812, 0, 0.0171568636, 0)
Aresenal.Size = UDim2.new(0, 86, 0, 32)
Aresenal.Font = Enum.Font.SourceSans
Aresenal.Text = "Aresenal"
Aresenal.TextColor3 = Color3.fromRGB(255, 0, 0)
Aresenal.TextSize = 14.000
Aresenal.MouseButton1Down:connect(function()
	function getplrsname() for i,v in pairs(game:GetChildren()) do if v.ClassName == "Players" then return v.Name end end end local players = getplrsname() local plr = game[players].LocalPlayer coroutine.resume(coroutine.create(function() while wait(1) do coroutine.resume(coroutine.create(function() for _,v in pairs(game[players]:GetPlayers()) do if v.Name ~= plr.Name and v.Character then v.Character.RightUpperLeg.CanCollide = false v.Character.RightUpperLeg.Transparency = 75 v.Character.RightUpperLeg.Size = Vector3.new(21,21,21) v.Character.LeftUpperLeg.CanCollide = false v.Character.LeftUpperLeg.Transparency = 75 v.Character.LeftUpperLeg.Size = Vector3.new(21,21,21) v.Character.HeadHB.CanCollide = false v.Character.HeadHB.Transparency = 75 v.Character.HeadHB.Size = Vector3.new(21,21,21) v.Character.HumanoidRootPart.CanCollide = false v.Character.HumanoidRootPart.Transparency = 75 v.Character.HumanoidRootPart.Size = Vector3.new(21,21,21) end end end)) end end))
end)

AnimeFight.Name = "AnimeFight"
AnimeFight.Parent = ScrollingFrame
AnimeFight.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AnimeFight.BorderColor3 = Color3.fromRGB(255, 0, 0)
AnimeFight.BorderSizePixel = 2
AnimeFight.Position = UDim2.new(0.588932812, 0, 0.127450988, 0)
AnimeFight.Size = UDim2.new(0, 86, 0, 32)
AnimeFight.Font = Enum.Font.SourceSans
AnimeFight.Text = "Anime Fighters"
AnimeFight.TextColor3 = Color3.fromRGB(255, 0, 0)
AnimeFight.TextSize = 14.000
AnimeFight.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/ZenHub/main/Loader", true))()
end)

KingLegacy.Name = "King Legacy"
KingLegacy.Parent = ScrollingFrame
KingLegacy.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
KingLegacy.BorderColor3 = Color3.fromRGB(255, 0, 0)
KingLegacy.BorderSizePixel = 2
KingLegacy.Position = UDim2.new(0.0316205621, 0, 0.127450988, 0)
KingLegacy.Size = UDim2.new(0, 86, 0, 32)
KingLegacy.Font = Enum.Font.SourceSans
KingLegacy.Text = "King Legacy"
KingLegacy.TextColor3 = Color3.fromRGB(255, 0, 0)
KingLegacy.TextSize = 14.000
KingLegacy.MouseButton1Down:connect(function()
	loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()
end)

babf.Name = "babf"
babf.Parent = ScrollingFrame
babf.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
babf.BorderColor3 = Color3.fromRGB(255, 0, 0)
babf.BorderSizePixel = 2
babf.Position = UDim2.new(0.0316205621, 0, 0.240196079, 0)
babf.Size = UDim2.new(0, 86, 0, 32)
babf.Font = Enum.Font.SourceSans
babf.Text = "Build A Boat"
babf.TextColor3 = Color3.fromRGB(255, 0, 0)
babf.TextSize = 14.000
babf.MouseButton1Down:connect(function()
babf.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/StenDirt/Trash-Game/main/Script.lua"))()
end)
end)

Shindo.Name = "Shindo"
Shindo.Parent = ScrollingFrame
Shindo.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Shindo.BorderColor3 = Color3.fromRGB(255, 0, 0)
Shindo.BorderSizePixel = 2
Shindo.Position = UDim2.new(0.588932812, 0, 0.240196079, 0)
Shindo.Size = UDim2.new(0, 86, 0, 32)
Shindo.Font = Enum.Font.SourceSans
Shindo.Text = "Shindo Life"
Shindo.TextColor3 = Color3.fromRGB(255, 0, 0)
Shindo.TextSize = 14.000
Shindo.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/SxnwDev/Premier/main/Free-Premier.lua", true))()
end)

HotelEl.Name = "HotelEl"
HotelEl.Parent = ScrollingFrame
HotelEl.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
HotelEl.BorderColor3 = Color3.fromRGB(255, 0, 0)
HotelEl.BorderSizePixel = 2
HotelEl.Position = UDim2.new(0.588932812, 0, 0.355392158, 0)
HotelEl.Size = UDim2.new(0, 86, 0, 32)
HotelEl.Font = Enum.Font.SourceSans
HotelEl.Text = "Hotel Elephant"
HotelEl.TextColor3 = Color3.fromRGB(255, 0, 0)
HotelEl.TextSize = 14.000
HotelEl.MouseButton1Down:connect(function()
	game.ReplicatedStorage.MoneyRequest:FireServer(false, 2e9, "Cash")
end)

Animesim.Name = "Animesim"
Animesim.Parent = ScrollingFrame
Animesim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Animesim.BorderColor3 = Color3.fromRGB(255, 0, 0)
Animesim.BorderSizePixel = 2
Animesim.Position = UDim2.new(0.0316205621, 0, 0.355392158, 0)
Animesim.Size = UDim2.new(0, 86, 0, 32)
Animesim.Font = Enum.Font.SourceSans
Animesim.Text = "Anime Dimension"
Animesim.TextColor3 = Color3.fromRGB(255, 0, 0)
Animesim.TextSize = 14.000
Animesim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/ghost-home/public/main/AnimeGhost.lua', true))()
end)

jb.Name = "jb"
jb.Parent = ScrollingFrame
jb.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
jb.BorderColor3 = Color3.fromRGB(255, 0, 0)
jb.BorderSizePixel = 2
jb.Position = UDim2.new(0.0316205621, 0, 0.475490183, 0)
jb.Size = UDim2.new(0, 86, 0, 32)
jb.Font = Enum.Font.SourceSans
jb.Text = "JailBreak"
jb.TextColor3 = Color3.fromRGB(255, 0, 0)
jb.TextSize = 14.000
jb.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://3762448307")[1].Source)()
end)

MM2.Name = "MM2"
MM2.Parent = ScrollingFrame
MM2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MM2.BorderColor3 = Color3.fromRGB(255, 0, 0)
MM2.BorderSizePixel = 2
MM2.Position = UDim2.new(0.588932812, 0, 0.475490183, 0)
MM2.Size = UDim2.new(0, 86, 0, 32)
MM2.Font = Enum.Font.SourceSans
MM2.Text = "MM2"
MM2.TextColor3 = Color3.fromRGB(255, 0, 0)
MM2.TextSize = 14.000
MM2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Drifter0507/scripts/main/mm2", true))()
end)

brook.Name = "brook"
brook.Parent = ScrollingFrame
brook.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
brook.BorderColor3 = Color3.fromRGB(255, 0, 0)
brook.BorderSizePixel = 2
brook.Position = UDim2.new(0.588932812, 0, 0.588235319, 0)
brook.Size = UDim2.new(0, 86, 0, 32)
brook.Font = Enum.Font.SourceSans
brook.Text = "BrookHaven"
brook.TextColor3 = Color3.fromRGB(255, 0, 0)
brook.TextSize = 14.000
brook.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/1rZyGLpQ'),true))()
end)

Meepcity.Name = "Meepcity"
Meepcity.Parent = ScrollingFrame
Meepcity.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Meepcity.BorderColor3 = Color3.fromRGB(255, 0, 0)
Meepcity.BorderSizePixel = 2
Meepcity.Position = UDim2.new(0.0316205323, 0, 0.588235319, 0)
Meepcity.Size = UDim2.new(0, 86, 0, 32)
Meepcity.Font = Enum.Font.SourceSans
Meepcity.Text = "MeepCity"
Meepcity.TextColor3 = Color3.fromRGB(255, 0, 0)
Meepcity.TextSize = 14.000
Meepcity.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/1rZyGLpQ'),true))()
end)

petsim.Name = "petsim"
petsim.Parent = ScrollingFrame
petsim.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
petsim.BorderColor3 = Color3.fromRGB(255, 0, 0)
petsim.BorderSizePixel = 2
petsim.Position = UDim2.new(0.0316205323, 0, 0.698529482, 0)
petsim.Size = UDim2.new(0, 86, 0, 32)
petsim.Font = Enum.Font.SourceSans
petsim.Text = "Pet Sim X"
petsim.TextColor3 = Color3.fromRGB(255, 0, 0)
petsim.TextSize = 14.000
petsim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/31"))();
end)

tohell.Name = "tohell"
tohell.Parent = ScrollingFrame
tohell.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
tohell.BorderColor3 = Color3.fromRGB(255, 0, 0)
tohell.BorderSizePixel = 2
tohell.Position = UDim2.new(0.588932812, 0, 0.80392164, 0)
tohell.Size = UDim2.new(0, 86, 0, 32)
tohell.Font = Enum.Font.SourceSans
tohell.Text = "Tower Of Hell"
tohell.TextColor3 = Color3.fromRGB(255, 0, 0)
tohell.TextSize = 14.000
tohell.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/TwomadJR/nto/main/admiin"))()
end)

bw.Name = "bw"
bw.Parent = ScrollingFrame
bw.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
bw.BorderColor3 = Color3.fromRGB(255, 0, 0)
bw.BorderSizePixel = 2
bw.Position = UDim2.new(0.588932812, 0, 0.700980425, 0)
bw.Size = UDim2.new(0, 86, 0, 32)
bw.Font = Enum.Font.SourceSans
bw.Text = "BedWars"
bw.TextColor3 = Color3.fromRGB(255, 0, 0)
bw.TextSize = 14.000
bw.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/YourLocalNzi/Ye/main/Jn_V9.txt'),true))()
end)

Beeswarm.Name = "Beeswarm"
Beeswarm.Parent = ScrollingFrame
Beeswarm.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Beeswarm.BorderColor3 = Color3.fromRGB(255, 0, 0)
Beeswarm.BorderSizePixel = 2
Beeswarm.Position = UDim2.new(0.588932812, 0, 0.904411793, 0)
Beeswarm.Size = UDim2.new(0, 86, 0, 32)
Beeswarm.Font = Enum.Font.SourceSans
Beeswarm.Text = "Bee Swarm Sim"
Beeswarm.TextColor3 = Color3.fromRGB(255, 0, 0)
Beeswarm.TextSize = 14.000
Beeswarm.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Historia00012/HISTORIAHUB/main/BSS%20FREE"))()
end)

sonic.Name = "sonic"
sonic.Parent = ScrollingFrame
sonic.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
sonic.BorderColor3 = Color3.fromRGB(255, 0, 0)
sonic.BorderSizePixel = 2
sonic.Position = UDim2.new(0.0316205621, 0, 0.904411793, 0)
sonic.Size = UDim2.new(0, 86, 0, 32)
sonic.Font = Enum.Font.SourceSans
sonic.Text = "Sonic Sim"
sonic.TextColor3 = Color3.fromRGB(255, 0, 0)
sonic.TextSize = 14.000
sonic.MouseButton1Down:connect(function()
	loadstring(game:HttpGet"https://gitlab.com/L1ZOT/test-project/-/raw/main/Sonic-Speed-Simulator-AutoEXC")()

end)

Dahood.Name = "Dahood"
Dahood.Parent = ScrollingFrame
Dahood.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dahood.BorderColor3 = Color3.fromRGB(255, 0, 0)
Dahood.BorderSizePixel = 2
Dahood.Position = UDim2.new(0.0316205621, 0, 0.80392164, 0)
Dahood.Size = UDim2.new(0, 86, 0, 32)
Dahood.Font = Enum.Font.SourceSans
Dahood.Text = "Untitled Hood"
Dahood.TextColor3 = Color3.fromRGB(255, 0, 0)
Dahood.TextSize = 14.000
Dahood.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\66\97\108\108\105\103\117\115\97\112\111\84\84\47\66\97\108\108\105\103\117\115\97\112\111\84\84\47\109\97\105\110\47\85\110\116\105\116\108\101\100\104\111\111\100\71\117\105\10"))()
end)

LabelMain.Name = "LabelMain"
LabelMain.Parent = MainFrame
LabelMain.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelMain.BackgroundTransparency = 1.000
LabelMain.BorderColor3 = Color3.fromRGB(255, 0, 0)
LabelMain.BorderSizePixel = 2
LabelMain.Position = UDim2.new(0.427536219, 0, 0, 0)
LabelMain.Size = UDim2.new(0, 181, 0, 40)
LabelMain.Font = Enum.Font.SourceSansBold
LabelMain.Text = "Proto's Hub v.6"
LabelMain.TextColor3 = Color3.fromRGB(255, 0, 0)
LabelMain.TextSize = 40.000

ScrollingFrame2.Name = "ScrollingFrame2"
ScrollingFrame2.Parent = MainFrame
ScrollingFrame2.Active = true
ScrollingFrame2.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
ScrollingFrame2.BorderColor3 = Color3.fromRGB(255, 0, 0)
ScrollingFrame2.Position = UDim2.new(0.341737598, 0, 0.19898665, 0)
ScrollingFrame2.Size = UDim2.new(0, 253, 0, 150)
ScrollingFrame2.Visible = false

TextButton.Parent = ScrollingFrame2
TextButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton.BorderSizePixel = 2
TextButton.Position = UDim2.new(0.0316205546, 0, 0.0171568636, 0)
TextButton.Size = UDim2.new(0, 86, 0, 32)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Stand Upright RB"
TextButton.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton.TextSize = 14.000
TextButton.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/xlostpexz/Standupright/main/Stand%20UpRight.lua"))()
end)

TextButton_2.Parent = ScrollingFrame2
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_2.BorderSizePixel = 2
TextButton_2.Position = UDim2.new(0.588932812, 0, 0.0171568636, 0)
TextButton_2.Size = UDim2.new(0, 86, 0, 32)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Doomspire"
TextButton_2.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_2.TextSize = 14.000
TextButton_2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/WyqZ5CXE'),true))()
end)

TextButton_3.Parent = ScrollingFrame2
TextButton_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_3.BorderSizePixel = 2
TextButton_3.Position = UDim2.new(0.588932812, 0, 0.127450988, 0)
TextButton_3.Size = UDim2.new(0, 86, 0, 32)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Pls Donate"
TextButton_3.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_3.TextSize = 14.000
TextButton_3.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/EA5numw0'),true))()
end)

TextButton_4.Parent = ScrollingFrame2
TextButton_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_4.BorderSizePixel = 2
TextButton_4.Position = UDim2.new(0.0316205621, 0, 0.127450988, 0)
TextButton_4.Size = UDim2.new(0, 86, 0, 32)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Weapon Fight Sim"
TextButton_4.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_4.TextSize = 12.000
TextButton_4.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://rawscripts.net/raw/loader_1038"))()
end)

TextButton_5.Parent = ScrollingFrame2
TextButton_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_5.BorderSizePixel = 2
TextButton_5.Position = UDim2.new(0.0316205621, 0, 0.240196079, 0)
TextButton_5.Size = UDim2.new(0, 86, 0, 32)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Mining Sim"
TextButton_5.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_5.TextSize = 14.000
TextButton_5.MouseButton1Down:connect(function()
	_G.FarmTicket = true
	game:GetService("ReplicatedStorage").Events.SetToolHolding:FireServer("Fishing Rod")
	game.Players.LocalPlayer.PlayerGui.SurfaceGui.Frame.Main.Pet.ChildAdded:Connect(function(a)if a.Name=="Camera"then else if tostring(_G.FarmTicket)=="true" then game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack({a.Name,"All"}))end end end)
	while _G.FarmTicket do task.wait()tweenService,tweenInfo=game:GetService("TweenService"),TweenInfo.new(1,Enum.EasingStyle.Linear)tween=tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart,tweenInfo,{CFrame=CFrame.new(-2943.33154296875,5.150033950805664,-113.26372528076172)})tween:Play()game:GetService("ReplicatedStorage").Events.FishingCast:FireServer(unpack({workspace.Worlds:FindFirstChild("Summer Fair").Fishing.Ocean.Part,Vector3.new(-3041.581298828125,0.18494415283203125,-104.90171813964844)}))end
end)

TextButton_6.Parent = ScrollingFrame2
TextButton_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_6.BorderSizePixel = 2
TextButton_6.Position = UDim2.new(0.588932812, 0, 0.240196079, 0)
TextButton_6.Size = UDim2.new(0, 86, 0, 32)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "Piggy"
TextButton_6.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_6.TextSize = 14.000
TextButton_6.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/YA3tWWwM'),true))()
end)

TextButton_7.Parent = ScrollingFrame2
TextButton_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_7.BorderSizePixel = 2
TextButton_7.Position = UDim2.new(0.588932812, 0, 0.355392158, 0)
TextButton_7.Size = UDim2.new(0, 86, 0, 32)
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = "Prison Life"
TextButton_7.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_7.TextSize = 14.000
TextButton_7.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebinp.com/raw/dt7JbaH5'))()
end)

TextButton_8.Parent = ScrollingFrame2
TextButton_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_8.BorderSizePixel = 2
TextButton_8.Position = UDim2.new(0.0316205621, 0, 0.355392158, 0)
TextButton_8.Size = UDim2.new(0, 86, 0, 32)
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = "Naval Warfare"
TextButton_8.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_8.TextSize = 14.000
TextButton_8.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/vCkw6SF7'))()
end)

TextButton_9.Parent = ScrollingFrame2
TextButton_9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_9.BorderSizePixel = 2
TextButton_9.Position = UDim2.new(0.0316205621, 0, 0.475490183, 0)
TextButton_9.Size = UDim2.new(0, 86, 0, 32)
TextButton_9.Font = Enum.Font.SourceSans
TextButton_9.Text = "Flee The Facility"
TextButton_9.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_9.TextSize = 14.000
TextButton_9.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Drifty96/ftfgui/main/ftfgui", true))()
end)

TextButton_10.Parent = ScrollingFrame2
TextButton_10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_10.BorderSizePixel = 2
TextButton_10.Position = UDim2.new(0.588932812, 0, 0.475490183, 0)
TextButton_10.Size = UDim2.new(0, 86, 0, 32)
TextButton_10.Font = Enum.Font.SourceSans
TextButton_10.Text = "Big Paintball"
TextButton_10.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_10.TextSize = 14.000
TextButton_10.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/WetCheezit/Releases/main/Big-Paintball/KillAll.lua"))()
end)

TextButton_11.Parent = ScrollingFrame2
TextButton_11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_11.BorderSizePixel = 2
TextButton_11.Position = UDim2.new(0.588932812, 0, 0.588235319, 0)
TextButton_11.Size = UDim2.new(0, 86, 0, 32)
TextButton_11.Font = Enum.Font.SourceSans
TextButton_11.Text = "Tower Of Misery"
TextButton_11.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_11.TextSize = 14.000
TextButton_11.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://raw.githubusercontent.com/cjdjmj/tow/main/README.md"),true))()
end)

TextButton_12.Parent = ScrollingFrame2
TextButton_12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_12.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_12.BorderSizePixel = 2
TextButton_12.Position = UDim2.new(0.0316205323, 0, 0.588235319, 0)
TextButton_12.Size = UDim2.new(0, 86, 0, 32)
TextButton_12.Font = Enum.Font.SourceSans
TextButton_12.Text = "Mega Easy Obby"
TextButton_12.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_12.TextSize = 14.000
TextButton_12.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/X361rzKq"))()
end)

TextButton_13.Parent = ScrollingFrame2
TextButton_13.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_13.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_13.BorderSizePixel = 2
TextButton_13.Position = UDim2.new(0.0316205323, 0, 0.698529482, 0)
TextButton_13.Size = UDim2.new(0, 86, 0, 32)
TextButton_13.Font = Enum.Font.SourceSans
TextButton_13.Text = "Legend Of Speed"
TextButton_13.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_13.TextSize = 12.000
TextButton_13.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/r3Nrx0zN'),true))()
end)

TextButton_14.Parent = ScrollingFrame2
TextButton_14.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_14.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_14.BorderSizePixel = 2
TextButton_14.Position = UDim2.new(0.588932812, 0, 0.80392164, 0)
TextButton_14.Size = UDim2.new(0, 86, 0, 32)
TextButton_14.Font = Enum.Font.SourceSans
TextButton_14.Text = "Natural Diaster"
TextButton_14.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_14.TextSize = 14.000
TextButton_14.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/JnGNjU0X'))()
end)

TextButton_15.Parent = ScrollingFrame2
TextButton_15.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_15.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_15.BorderSizePixel = 2
TextButton_15.Position = UDim2.new(0.588932812, 0, 0.700980425, 0)
TextButton_15.Size = UDim2.new(0, 86, 0, 32)
TextButton_15.Font = Enum.Font.SourceSans
TextButton_15.Text = "Hotel Elephant"
TextButton_15.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_15.TextSize = 14.000
TextButton_15.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/Teemsploit/Epic-roblox-hack/main/HotelElephantFuckerV2'))()
end)

TextButton_16.Parent = ScrollingFrame2
TextButton_16.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_16.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_16.BorderSizePixel = 2
TextButton_16.Position = UDim2.new(0.588932812, 0, 0.904411793, 0)
TextButton_16.Size = UDim2.new(0, 86, 0, 32)
TextButton_16.Font = Enum.Font.SourceSans
TextButton_16.Text = "Lumber Tycoon"
TextButton_16.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_16.TextSize = 14.000
TextButton_16.MouseButton1Down:connect(function()
	loadstring(game:HttpGet"https://pastebin.com/raw/25abQ0nC")()
end)

TextButton_17.Parent = ScrollingFrame2
TextButton_17.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_17.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_17.BorderSizePixel = 2
TextButton_17.Position = UDim2.new(0.0316205621, 0, 0.904411793, 0)
TextButton_17.Size = UDim2.new(0, 86, 0, 32)
TextButton_17.Font = Enum.Font.SourceSans
TextButton_17.Text = "Epic Minigames"
TextButton_17.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_17.TextSize = 14.000
TextButton_17.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/YePwz5u5", true))()
end)

TextButton_18.Parent = ScrollingFrame2
TextButton_18.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_18.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextButton_18.BorderSizePixel = 2
TextButton_18.Position = UDim2.new(0.0316205621, 0, 0.80392164, 0)
TextButton_18.Size = UDim2.new(0, 86, 0, 32)
TextButton_18.Font = Enum.Font.SourceSans
TextButton_18.Text = "Bot Clash"
TextButton_18.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_18.TextSize = 14.000
TextButton_18.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Krackenz/RobloxScripts/main/Protected%20(6).lua",true))()
end)

Page1.Name = "Page1"
Page1.Parent = MainFrame
Page1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Page1.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page1.BorderSizePixel = 2
Page1.Position = UDim2.new(0.0748792291, 0, 0.676470637, 0)
Page1.Size = UDim2.new(0, 79, 0, 19)
Page1.Font = Enum.Font.SourceSansBold
Page1.Text = "Page 1"
Page1.TextColor3 = Color3.fromRGB(255, 0, 0)
Page1.TextSize = 14.000

Page2.Name = "Page2"
Page2.Parent = MainFrame
Page2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Page2.BorderColor3 = Color3.fromRGB(255, 0, 0)
Page2.BorderSizePixel = 2
Page2.Position = UDim2.new(0.0748792291, 0, 0.80392158, 0)
Page2.Size = UDim2.new(0, 79, 0, 13)
Page2.Font = Enum.Font.SourceSansBold
Page2.Text = "Page 2"
Page2.TextColor3 = Color3.fromRGB(255, 0, 0)
Page2.TextSize = 14.000

Home.Name = "Home"
Home.Parent = MainFrame
Home.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Home.BorderColor3 = Color3.fromRGB(255, 0, 0)
Home.BorderSizePixel = 2
Home.Position = UDim2.new(0.0748792291, 0, 0.514705896, 0)
Home.Size = UDim2.new(0, 79, 0, 20)
Home.Font = Enum.Font.SourceSansBold
Home.Text = "Home"
Home.TextColor3 = Color3.fromRGB(255, 0, 0)
Home.TextSize = 23.000

scriptsother.Name = "scriptsother"
scriptsother.Parent = MainFrame
scriptsother.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
scriptsother.BorderColor3 = Color3.fromRGB(255, 0, 0)
scriptsother.Position = UDim2.new(0.342995167, 0, 0.196078435, 0)
scriptsother.Size = UDim2.new(0, 252, 0, 150)
scriptsother.Visible = false

otherscripts.Name = "other scripts"
otherscripts.Parent = scriptsother
otherscripts.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
otherscripts.BorderColor3 = Color3.fromRGB(255, 0, 0)
otherscripts.Position = UDim2.new(0.17635116, 0, -0.00377776474, 0)
otherscripts.Size = UDim2.new(0, 161, 0, 24)
otherscripts.Font = Enum.Font.SourceSansBold
otherscripts.Text = "My Other Scripts"
otherscripts.TextColor3 = Color3.fromRGB(255, 0, 0)
otherscripts.TextSize = 23.000

v3.Name = "v3"
v3.Parent = scriptsother
v3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
v3.BorderColor3 = Color3.fromRGB(255, 0, 0)
v3.BorderSizePixel = 2
v3.Position = UDim2.new(0.0258093942, 0, 0.247422293, 0)
v3.Size = UDim2.new(0, 80, 0, 31)
v3.Font = Enum.Font.SourceSansBold
v3.Text = "v3"
v3.TextColor3 = Color3.fromRGB(255, 0, 0)
v3.TextSize = 14.000
v3.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/r8WFBXKX"))()
end)

v5.Name = "v5"
v5.Parent = scriptsother
v5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
v5.BorderColor3 = Color3.fromRGB(255, 0, 0)
v5.BorderSizePixel = 2
v5.Position = UDim2.new(0.656761765, 0, 0.247422308, 0)
v5.Size = UDim2.new(0, 80, 0, 31)
v5.Font = Enum.Font.SourceSansBold
v5.Text = "v5"
v5.TextColor3 = Color3.fromRGB(255, 0, 0)
v5.TextSize = 14.000
v5.MouseButton1Down:connect(function()
	loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\80\114\111\116\111\116\121\112\101\82\66\76\88\47\80\114\111\116\111\45\115\45\72\117\98\47\109\97\105\110\47\82\69\65\68\77\69\46\109\100\39\41\41\40\41\10")()
end)

v4.Name = "v4"
v4.Parent = scriptsother
v4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
v4.BorderColor3 = Color3.fromRGB(255, 0, 0)
v4.BorderSizePixel = 2
v4.Position = UDim2.new(0.343269706, 0, 0.247422308, 0)
v4.Size = UDim2.new(0, 80, 0, 31)
v4.Font = Enum.Font.SourceSansBold
v4.Text = "v4"
v4.TextColor3 = Color3.fromRGB(255, 0, 0)
v4.TextSize = 14.000
v4.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/buCsmABy'),true))()
end)

sprintscript.Name = "sprint script"
sprintscript.Parent = scriptsother
sprintscript.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
sprintscript.BorderColor3 = Color3.fromRGB(255, 0, 0)
sprintscript.BorderSizePixel = 2
sprintscript.Position = UDim2.new(0.0258093774, 0, 0.574088931, 0)
sprintscript.Size = UDim2.new(0, 80, 0, 31)
sprintscript.Font = Enum.Font.SourceSansBold
sprintscript.Text = "Change Speed"
sprintscript.TextColor3 = Color3.fromRGB(255, 0, 0)
sprintscript.TextSize = 14.000
sprintscript.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/PrototypeRBLX/Speed-Script/main/README.md'),true))()
end)

Spyx.Name = "Spyx"
Spyx.Parent = scriptsother
Spyx.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Spyx.BorderColor3 = Color3.fromRGB(255, 0, 0)
Spyx.BorderSizePixel = 2
Spyx.Position = UDim2.new(0.343269706, 0, 0.574088931, 0)
Spyx.Size = UDim2.new(0, 80, 0, 31)
Spyx.Font = Enum.Font.SourceSansBold
Spyx.Text = "SpyX"
Spyx.TextColor3 = Color3.fromRGB(255, 0, 0)
Spyx.TextSize = 14.000
Spyx.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/PrototypeRBLX/Spy-X-SCRIPT-ROBLOX/main/README.md'),true))()
end)

FruityWare.Name = "FruityWare"
FruityWare.Parent = scriptsother
FruityWare.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
FruityWare.BorderColor3 = Color3.fromRGB(255, 0, 0)
FruityWare.BorderSizePixel = 2
FruityWare.Position = UDim2.new(0.652793527, 0, 0.574088931, 0)
FruityWare.Size = UDim2.new(0, 80, 0, 31)
FruityWare.Font = Enum.Font.SourceSansBold
FruityWare.Text = "FruityWare"
FruityWare.TextColor3 = Color3.fromRGB(255, 0, 0)
FruityWare.TextSize = 14.000
FruityWare.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/PrototypeRBLX/FruityWare/main/README.md'),true))()
end)

Others.Name = "Others"
Others.Parent = MainFrame
Others.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Others.BorderColor3 = Color3.fromRGB(255, 0, 0)
Others.BorderSizePixel = 2
Others.Position = UDim2.new(0.0748792291, 0, 0.897058785, 0)
Others.Size = UDim2.new(0, 79, 0, 15)
Others.Font = Enum.Font.SourceSansBold
Others.Text = "Others"
Others.TextColor3 = Color3.fromRGB(255, 0, 0)
Others.TextSize = 14.000

homeframe.Name = "homeframe"
homeframe.Parent = MainFrame
homeframe.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
homeframe.BorderColor3 = Color3.fromRGB(255, 0, 0)
homeframe.Position = UDim2.new(0.342995167, 0, 0.196078435, 0)
homeframe.Size = UDim2.new(0, 252, 0, 150)

w.Name = "w"
w.Parent = homeframe
w.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
w.BackgroundTransparency = 1.000
w.Position = UDim2.new(0.103174604, 0, -0.0866667032, 0)
w.Size = UDim2.new(0, 200, 0, 50)
w.Font = Enum.Font.SourceSansBold
w.Text = "What Are You Looking For Today?"
w.TextColor3 = Color3.fromRGB(255, 0, 0)
w.TextSize = 14.000

TextLabel.Parent = homeframe
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.Position = UDim2.new(0.033470761, 0, 0.285367638, 0)
TextLabel.Size = UDim2.new(0, 234, 0, 37)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Credits To The Script Owners"
TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextSize = 14.000

sub.Name = "sub"
sub.Parent = homeframe
sub.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
sub.BorderColor3 = Color3.fromRGB(255, 0, 0)
sub.Position = UDim2.new(0.0827440545, 0, 0.653465152, 0)
sub.Size = UDim2.new(0, 209, 0, 20)
sub.Font = Enum.Font.SourceSans
sub.Text = "Sub 2 Prototype_RBLX"
sub.TextColor3 = Color3.fromRGB(255, 0, 0)
sub.TextSize = 14.000

x.Name = "x"
x.Parent = MainFrame
x.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
x.BorderColor3 = Color3.fromRGB(255, 0, 0)
x.Position = UDim2.new(0.929713011, 0, 0.0539215691, 0)
x.Size = UDim2.new(0, 20, 0, 9)
x.Font = Enum.Font.SourceSansBold
x.Text = "X"
x.TextColor3 = Color3.fromRGB(255, 0, 0)
x.TextSize = 33.000

UICorner_2.Parent = x

-- Scripts:

local function DZALQAO_fake_script() -- Page1.LocalScript 
	local script = Instance.new('LocalScript', Page1)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.homeframe.Visible = false
		script.Parent.Parent.ScrollingFrame.Visible = true
		script.Parent.Parent.ScrollingFrame2.Visible = false
		script.Parent.Parent.scriptsother.Visible = false
		wait(0.1)
	end)
end
coroutine.wrap(DZALQAO_fake_script)()
local function FDECAW_fake_script() -- Page2.LocalScript 
	local script = Instance.new('LocalScript', Page2)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.homeframe.Visible = false
		script.Parent.Parent.ScrollingFrame.Visible = false
		script.Parent.Parent.ScrollingFrame2.Visible = true
		script.Parent.Parent.scriptsother.Visible = false
		wait(0.1)
	end)
end
coroutine.wrap(FDECAW_fake_script)()
local function EQBO_fake_script() -- Home.LocalScript 
	local script = Instance.new('LocalScript', Home)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.homeframe.Visible = true
		script.Parent.Parent.ScrollingFrame.Visible = false
		script.Parent.Parent.ScrollingFrame2.Visible = false
		script.Parent.Parent.scriptsother.Visible = false
		wait(0.1)
	end)
end
coroutine.wrap(EQBO_fake_script)()
local function YPCDPY_fake_script() -- Others.LocalScript 
	local script = Instance.new('LocalScript', Others)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.homeframe.Visible = false
		script.Parent.Parent.ScrollingFrame.Visible = false
		script.Parent.Parent.ScrollingFrame2.Visible = false
		script.Parent.Parent.scriptsother.Visible = true
		wait(0.1)
	end)
end
coroutine.wrap(YPCDPY_fake_script)()
local function OSYG_fake_script() -- w.LocalScript 
	local script = Instance.new('LocalScript', w)

	w = "What Are You Looking For Today?" --The words that are animated
	
	for i = 1,#w do
		script.Parent.Text = string.sub(w,1,i)
		wait(0.5) -- the time each words get typed in
	end wait() script.Parent.Visible = true
end
coroutine.wrap(OSYG_fake_script)()
local function TZQVYI_fake_script() -- x.Script 
	local script = Instance.new('Script', x)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(TZQVYI_fake_script)()
