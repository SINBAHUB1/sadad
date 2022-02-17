
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/NOOBHUBX/LoadingUI/main/NOOB%20HUB.Lua"))()
local function gamekiller()
    while true do
          local fucku = 1
       end
    end

game:GetService("RunService").RenderStepped:connect(function()
for i,v in pairs(game.CoreGui:GetChildren()) do
    if v:FindFirstChild("PropertiesFrame") then
    if v:FindFirstChild("ExplorerPanel") then
    if v:FindFirstChild("SideMenu") then
             warn("DarkDex Detected")
             game.Players.LocalPlayer:kick("Do not open DarkDex")
             wait(.3)
             game:Shutdown()
             wait(0.2)Players:Toggle("Aimbot Skill", false, function(vu)
   _G.AimbotSkill = vu
 end)

 spawn(function()
   pcall(function()
   while game:GetService("RunService").RenderStepped:wait() do
      if _G.AimbotSkill then
         pcall(function()
            if game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool") and game.Players.LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name]:FindFirstChild("MousePos") then
                local args = {
                    [1] = game:GetService("Players"):FindFirstChild(_G.SelectP).Character.HumanoidRootPart.Position
                }
                game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
            end
        end)
    end
   end
   end)
end)
             gamekiller()
        end
        end
        end
    end
    end)
---------Kick Players---------
------------------------------
local UIS=game:GetService'UserInputService'

UIS.InputBegan:Connect(function(Key)
end)
if game:GetService("RbxAnalyticsService"):GetClientId() == "" or game:GetService("RbxAnalyticsService"):GetClientId() == nil then
   game.Players.LocalPlayer:Kick("Crack ไมโหล") 
end
local hwide = game:GetService("RbxAnalyticsService"):GetClientId()
local mathhwid = string.split(string.reverse(string.rep(string.sub(hwide,1,30),5)),'-')

local hwid = mathhwid[1]..mathhwid[6]..mathhwid[2]..mathhwid[5]

len = string.rep("/"..string.len(hwid),5)
setclipboard('<hwid '..string.rep((hwid),1)..len..string.reverse(hwide)..len..mathhwid[7]) -- สำคัญ

local HwidList = {
    ["33D9FBAEBAAEBA9EBFDB6433D9FB"] = "46BDFBE9-CE74-4DD8-ABEA-BF9D338C2ED9",
    ["93617F8C898C8953D62EC593617F"] = "5CE26D35-27EE-411E-98C8-F716399C4E0F",
    ["515DC34E284E284AB2B922515DC3"] = "229B2BA4-EB42-4793-82E4-3CD515785B2E",
    ["FD9526D6D8D6D842B4D01EFD9526"] = "E10D4B24-F78A-44E1-8D6D-6259DF745A69",
    ["EBC505D9FAD9FA492C8669EBC505"] = "9668C294-48A3-4715-AF9D-505CBE904086",
    ["65A45D1B1B1B1B43DBB50D65A45D"] = "D05BBD34-8799-4B81-B1B1-D54A5600A6DC",
    ["deddbe5f185f18044a4173deddbe"] = "3714a440-589e-4896-81f5-ebdded0e2886",
    ["696A30148914898E27669C696A30"] = "C96672E8-3DCD-41F8-9841-03A6963820FB",
    ["1765DE98D898D86B24E37C1765DE"] = "C73E42B6-4E16-4BA6-8D89-ED56713BF0E8",
    ["F82A79471847183EBF7589F82A79"] = "9857FBE3-0823-4876-8174-97A28F4A771B",
    ["63A2D491099109E3ACBB9963A2D4"] = "99BBCA3E-BF1D-4A5F-9019-4D2A36EBB003",
    ["201F91D6C9D6C911A64A61201F91"] = "16A46A11-5D93-4647-9C6D-19F102F38E08",
    ["45B2C9BF79BF79A6D416D745B2C9"] = "7D614D6A-471B-482D-97FB-9C2B5434417B",
    ["2A986CD48AD48A9CA705B82A986C"] = "8B507AC9-6410-4B66-A84D-C689A2A0890E",
    ["40304562A862A8348B0046403045"] = "6400B843-42E3-4EF1-8A26-5403042AECD9",
    ["72BF151B491B49FB6B02FF72BF15"] = "FF20B6BF-38CC-4245-94B1-51FB273DC569",
    ["5C4142AB4AAB4A82C07E3A5C4142"] = "A3E70C28-0F47-4DC3-A4BA-2414C54DD3E3",
    ["801298E52AE52A730E8B9C801298"] = "C9B8E037-A1AA-4768-A25E-8921080A83B8",
    ["1340A8FA99FA9952FD33771340A8"] = "7733DF25-7324-4ADD-99AF-8A0431D6DE0F",
    ["3A6ACFDB1BDB1BFF2D40513A6ACF"] = "1504D2FF-7530-466F-B1BD-FCA6A389A58F",
    ["A53176B6F8B6F8AE31BF94A53176"] = "49FB13EA-2F51-4B91-8F6B-67135A37F40A",
    ["62367CEF48EF4890563EB162367C"] = "1BE36509-9E4C-48BE-84FE-C763266D5FBE",
    ["9A476CC568C5688A9CC4179A476C"] = "714CC9A8-E1BB-4C74-865C-C674A99A3585",
    ["E2767A53AB53AB3687F8E4E2767A"] = "4E8F7863-4F66-4860-BA35-A7672E6EC18D",
    ["8D8A523EB83EB871395F888D8A52"] = "88F59317-B409-4E00-8BE3-25A8D8386B94",
    ["62367CEF48EF4890563EB162367C"] = "1BE36509-9E4C-48BE-84FE-C763266D5FBE",
    ["AABCFE990999096B3CD490AABCFE"] = "094DC3B6-C65D-4D2A-9099-EFCBAA220B79",
    ["E7303BD7A9D7A9BCF1400DE7303B"] = "D0041FCB-A8DD-43AA-9A7D-B3037E67AE91",
    ["67827A2ACB2ACB039D1EC667827A"] = "6CE1D930-96C1-414B-BCA2-A72876FCEDA6",
    ["b494158cd88cd8eda77b5db49415"] = "d5b77ade-c8fd-4aee-8dc8-51494b90425e",
    ["deff88d089d089a5b1766edeff88"] = "e6671b5a-848a-4a2a-980d-88ffed1236f5",
    ["0E28FA267B267B67A6CEB40E28FA"] = "4BEC6A76-2EB7-40A3-B762-AF82E0660BE1",
    ["c226b0e069e06925c8b1e4c226b0"] = "4e1b8c52-a032-47cb-960e-0b622c9ba37d",
    ["BDF419D34BD34B41B7A07FBDF419"] = "F70A7B14-4CD6-41CB-B43D-914FDB7EFEEE",
    ["301ACAD5FAD5FA7BECCF3A301ACA"] = "A3FCCEB7-1D87-4A9E-AF5D-ACA10371182B",
    ["A4A7F367AA67AA80EF51AAA4A7F3"] = "AA15FE08-9EFE-4C70-AA76-3F7A4A0C05A1",
    ["C9DE21AE38AE38BB834B2CC9DE21"] = "C2B438BB-7952-48DF-83EA-12ED9C03AD63",
    ["064A876E486E48B6668916064A87"] = "6198666B-C05F-4F5D-84E6-78A46015CFC3",
    ["FBB6F2B17AB17A4AB47880FBB6F2"] = "08874BA4-21FA-47C8-A71B-2F6BBF6DC684",
    ["8CC5C90CBB0CBBBECE8AF58CC5C9"] = "5FA8ECEB-F6D3-409A-BBC0-9C5CC8754CB1",
    ["EBD76154F854F82A9CDAEEEBD761"] = "EEADC9A2-FD72-43F1-8F45-167DBEC75811",
    ["0EDD2EC368C3686A4CB6860EDD2E"] = "686BC4A6-F894-4E86-863C-E2DDE0C305CA",
    ["8AAB8708AA08AA1D26BC3F8AAB87"] = "F3CB62D1-34AF-4B4E-AA80-78BAA876F30A",
    ["D638CA7CEA7CEA3DFD9A0ED638CA"] = "E0A9DFD3-E4CA-48E4-AEC7-AC836DD4E172",
    ["8BED59F15AF15A590567338BED59"] = "33765095-34EF-4CB5-A51F-95DEB8FB417D",
    ["95740EA6F9A6F98070B8E395740E"] = "3E8B0708-3113-45DF-9F6A-E047594A6DF6",
    ["27F028D9C9D9C94575466227F028"] = "26645754-3BEE-42AC-9C9D-820F72A9B161",
    ["25C7E3F9CAF9CA9F91FD4C25C7E3"] = "C4DF19F9-C972-47E9-AC9F-3E7C5206C728",
    ["74120506ca06caa04fbbef741205"] = "febbf40a-778a-4568-ac60-502147d2d954",
    ["9D50E64E5A4E5AB258C6059D50E6"] = "506C852B-AEA0-44D7-A5E4-6E05D9AB1957",
    ["10D57EC329C329D9914E0010D57E"] = "00E4199D-5EC3-45AE-923C-E75D011B33D0",
    ["B709D73DB93DB984F48B20B709D7"] = "02B84F48-C2CD-4DC6-9BD3-7D907BB60CCE",
    ["8BE0E285F985F9399B027F8BE0E2"] = "F720B993-6462-45BE-9F58-2E0EB8A1026A",
    ["4EA8171BB91BB99CC362994EA817"] = "99263CC9-52C2-4B5D-9BB1-718AE498A528",
    ["B4121845DA45DAEA64B191B41218"] = "191B46AE-C00A-4BC9-AD54-81214BE7468E",
    ["45DC34879A879AC9E5D44F45DC34"] = "F44D5E9C-0595-4143-A978-43CD54838930",
    ["5A36F883EA83EA2DED0D665A36F8"] = "66D0DED2-2A9F-4858-AE38-8F63A5304B1B",
    ["E6F53E387A387AB223662FE6F53E"] = "F266322B-2EED-49A2-A783-E35F6E4B94FF",
    ["dcd60a2ba82ba823563d02dcd60a"] = "20d36532-b4a4-4b3c-8ab2-a06dcdbe0720",
    ["36BFF848F948F97C46EC4B36BFF8"] = "B4CE64C7-B00C-44C2-9F84-8FFB6390D55B",
    ["1B98B270E870E8D18185F01B98B2"] = "288FCA401B98B2-70E8-5824-AE7A-D18185F0",
}

if _G.License == mathhwid[7] then
if _G.LoadedHwid == string.reverse(hwide) then
if _G.Key == hwid then
if HwidList[_G.Key] == game:GetService("RbxAnalyticsService"):GetClientId() then




-- Atom Lib
do 
	local ui =  game:GetService("CoreGui"):FindFirstChild("Atom Lib") 
	if ui then
		ui:Destroy()
	end
end



local UserInputService = game:GetService("UserInputService")
local TweenService = game:GetService("TweenService")
local RunService = game:GetService("RunService")
local LocalPlayer = game:GetService("Players").LocalPlayer
local Mouse = LocalPlayer:GetMouse()

local Atomlib = Instance.new("ScreenGui")

Atomlib.Name = "Atom Lib"
Atomlib.Parent = game:GetService("CoreGui")
Atomlib.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

local function MakeDraggable(topbarobject, object)
	local Dragging = nil
	local DragInput = nil
	local DragStart = nil
	local StartPosition = nil

	local function Update(input)
		local Delta = input.Position - DragStart
		local pos =
			UDim2.new(
				StartPosition.X.Scale,
				StartPosition.X.Offset + Delta.X,
				StartPosition.Y.Scale,
				StartPosition.Y.Offset + Delta.Y
			)
		local Tween = TweenService:Create(object, TweenInfo.new(0.2), {Position = pos})
		Tween:Play()
	end

	topbarobject.InputBegan:Connect(
		function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				Dragging = true
				DragStart = input.Position
				StartPosition = object.Position

				input.Changed:Connect(
					function()
						if input.UserInputState == Enum.UserInputState.End then
							Dragging = false
						end
					end
				)
			end
		end
	)

	topbarobject.InputChanged:Connect(
		function(input)
			if
				input.UserInputType == Enum.UserInputType.MouseMovement or
				input.UserInputType == Enum.UserInputType.Touch
			then
				DragInput = input
			end
		end
	)

	UserInputService.InputChanged:Connect(
		function(input)
			if input == DragInput and Dragging then
				Update(input)
			end
		end
	)
end

do  local ui =  game:GetService("CoreGui").RobloxGui.Modules:FindFirstChild("Close")  if ui then ui:Destroy() end end
local Close = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local MainFrameUICorner = Instance.new("UICorner")
local Button = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")

local UserInputService = game:GetService("UserInputService")
local TweenService = game:GetService("TweenService")
local RunService = game:GetService("RunService")
local LocalPlayer = game:GetService("Players").LocalPlayer

Close.Name = "Close"
Close.Parent = game:GetService("CoreGui").RobloxGui.Modules
Close.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = Close
MainFrame.Active = true
MainFrame.AnchorPoint = Vector2.new(0.5, 0.5)
MainFrame.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
MainFrame.BorderColor3 = Color3.fromRGB(35, 35, 35)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0.18696712, 0, 0.164417177, 0)
MainFrame.Size = UDim2.new(0, 0, 0, 0) -- 0, 100, 0, 50

MakeDraggable(Button,MainFrame)

local DropFrameStroke = Instance.new("UIStroke")

DropFrameStroke.Thickness = 1
DropFrameStroke.Name = ""
DropFrameStroke.Parent = MainFrame
DropFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
DropFrameStroke.Color = Color3.fromRGB(255,24,24)
DropFrameStroke.Transparency = 1

TweenService:Create(
	MainFrame,
	TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
	{Size = UDim2.new(0, 100, 0, 50)}
):Play()

repeat wait() until MainFrame.Size == UDim2.new(0, 100, 0, 50)

TweenService:Create(
	DropFrameStroke,
	TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
	{Transparency = 0}
):Play()

repeat wait() until DropFrameStroke.Transparency == 0


MainFrameUICorner.Name = "MainFrameUICorner"
MainFrameUICorner.Parent = MainFrame

Button.Name = "Button"
Button.Parent = MainFrame
Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button.BackgroundTransparency = 1.000
Button.Size = UDim2.new(0, 100, 0, 50)
Button.AutoButtonColor = false
Button.Font = Enum.Font.SourceSans
Button.Text = ""
Button.TextColor3 = Color3.fromRGB(0, 0, 0)
Button.TextSize = 14.000

TextLabel.Parent = MainFrame
TextLabel.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel.Size = UDim2.new(0, 100, 0, 25)
TextLabel.Font = Enum.Font.GothamSemibold
TextLabel.Text = "Open"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 12.000

Toggle = false 

Button.MouseButton1Click:Connect(function()
	if Toggle == false then
		TextLabel.TextSize = 0 
		TweenService:Create(
			TextLabel,
			TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
			{TextSize = 12}
		):Play()
		TextLabel.Text = "Close"
		Atomlib.Enabled = true
	else
		TextLabel.TextSize = 0 
		TweenService:Create(
			TextLabel,
			TweenInfo.new(0.2, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
			{TextSize = 12}
		):Play()
		TextLabel.Text = "Open"
		Atomlib.Enabled = false
	end
	Toggle = not Toggle
end)


local create = {}


function create:Win()

    local fs = false 
    local currentservertoggled = ""
    local Main = Instance.new("Frame")
        
    Main.Name = "Main"
    Main.Parent = Atomlib
    Main.BackgroundColor3 = Color3.fromRGB(19 , 19, 19)
    Main.BorderSizePixel = 0
    Main.Position = UDim2.new(0.5, 0, 0.5   , 0)
    Main.Size = UDim2.new(0, 0, 0, 0)
    Main.ClipsDescendants = true 
    Main.AnchorPoint = Vector2.new(0.5, 0.5)

    local Logo = Instance.new("ImageLabel")

    
    Logo.Name = "Logo"
    Logo.Parent = Main
    Logo.AnchorPoint = Vector2.new(0.5, 0.5)
    Logo.Position = UDim2.new(0.1, 0, 0.08, 0)
    Logo.BackgroundColor3 = Color3.fromRGB(19, 19, 19)
    Logo.BorderColor3 = Color3.fromRGB(27, 42, 53)
    Logo.BorderSizePixel = 0
    Logo.Size = UDim2.new(0, 56, 0, 56)
    Logo.Image = "rbxassetid://8252330502"
    
    
    local PageTap = Instance.new("Frame")
    local UIGradient_PageTap = Instance.new("UIGradient")

    PageTap.Name = "PageTap"
    PageTap.Parent = Main
    PageTap.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    PageTap.BackgroundTransparency = 1
    PageTap.BorderSizePixel = 0
    PageTap.Position = UDim2.new(0.189873412, 0, 0, 0)
    PageTap.Size = UDim2.new(0, 320, 0, 56)

    UIGradient_PageTap.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(230, 0, 39)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 35, 138))}
    UIGradient_PageTap.Parent = PageTap

    
    local ScolTap = Instance.new("ScrollingFrame")
    local UIListLayout_ScolTap = Instance.new("UIListLayout")
    local UIPadding_ScolTap = Instance.new("UIPadding")

    ScolTap.Name = "ScolTap"
    ScolTap.Parent = PageTap
    ScolTap.Active = true
    ScolTap.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    ScolTap.BackgroundTransparency = 1
    ScolTap.BorderSizePixel = 0
    ScolTap.Size = UDim2.new(0, 320, 0, 56)
    ScolTap.CanvasSize = UDim2.new(0.5, 0, 0, 0)
    ScolTap.ScrollBarThickness = 3
    ScolTap.ScrollBarImageColor3 =  Color3.fromRGB(235, 235, 235)

    UIListLayout_ScolTap.Parent = ScolTap
    UIListLayout_ScolTap.FillDirection = Enum.FillDirection.Horizontal
    UIListLayout_ScolTap.SortOrder = Enum.SortOrder.LayoutOrder
    UIListLayout_ScolTap.Padding = UDim.new(0, 5)

    UIPadding_ScolTap.Parent = ScolTap
    UIPadding_ScolTap.PaddingTop = UDim.new(0, 6)


    local pagesFolder = Instance.new("Folder")

    pagesFolder.Name = "pagesFolder"
    pagesFolder.Parent = Main
  
    MakeDraggable(Main,Main)
    local tween = game:GetService("TweenService")
    local library = {currenttab = '',toggledui = false}
    tween:Create(Main,TweenInfo.new(0.4,Enum.EasingStyle.Back),{Size = UDim2.new(0, 395, 0, 395)}):Play()


    game:GetService("UserInputService").InputBegan:Connect(function(input)
        if input.KeyCode == Enum.KeyCode.RightControl then 
            if library.toggledui == false then
                library.toggledui = true  
                tween:Create(Main,TweenInfo.new(0.4,Enum.EasingStyle.Back,Enum.EasingDirection.In),{Size = UDim2.new(0, 0, 0, 0)}):Play()
            else 
                library.toggledui = false 
                tween:Create(Main,TweenInfo.new(0.4,Enum.EasingStyle.Back),{Size = UDim2.new(0, 395, 0, 395)}):Play()
            end 
        end
    end)


local tap = {}

function tap:addtap(text)

    local TextButton_Tap = Instance.new("TextButton")

    TextButton_Tap.Parent = ScolTap
    TextButton_Tap.Name = "TextButton_Tap"
    TextButton_Tap.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    TextButton_Tap.BackgroundTransparency = 1
    TextButton_Tap.Position = UDim2.new(0.0151898731, 0, 0.132352948, 0)
    TextButton_Tap.Size = UDim2.new(0, 75, 0, 50)
    TextButton_Tap.Font = Enum.Font.GothamSemibold
    TextButton_Tap.TextColor3 = Color3.fromRGB(155, 155, 155)
    TextButton_Tap.TextSize = 10.000
    TextButton_Tap.TextWrapped = true
    TextButton_Tap.Text = text
    
    

    local TextLabel_Tap = Instance.new("TextLabel") 

    TextLabel_Tap.Parent = TextButton_Tap
    TextLabel_Tap.Name = "TextLabel_Tap"
    TextLabel_Tap.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TextLabel_Tap.AnchorPoint = Vector2.new(0.5, 0.5)
    TextLabel_Tap.Position = UDim2.new(0.52, 0, 0.8, 0)
    TextLabel_Tap.Size = UDim2.new(0, 0, 0, 0)
    TextLabel_Tap.Font = Enum.Font.SourceSans
    TextLabel_Tap.Text = " "
    TextLabel_Tap.TextColor3 = Color3.fromRGB(255, 0, 95)
    TextLabel_Tap.TextSize = 14.000
    TextLabel_Tap.BorderSizePixel = 0



    local MainFramePage = Instance.new("Frame")

    
    MainFramePage.Name = "MainFramePage"
    MainFramePage.Parent = pagesFolder
    MainFramePage.BackgroundColor3 = Color3.fromRGB(19, 19, 19)
    MainFramePage.BorderSizePixel = 0
    MainFramePage.Position = UDim2.new(0, 0, 0.141772151, 0)
    MainFramePage.Size = UDim2.new(0, 395, 0, 339)
    MainFramePage.Visible = false 



    local FramePage = Instance.new("Frame")
    local ScolPage = Instance.new("ScrollingFrame")
    local MainPage = Instance.new("Frame")
    local UIGridLayout_MainPage = Instance.new("UIGridLayout")
    local UIListLayout_MainPage = Instance.new("UIListLayout")
    local UIPadding_MainPage = Instance.new("UIPadding")

    --Properties:

    FramePage.Name = "FramePage"
    FramePage.Parent = MainFramePage
    FramePage.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
    FramePage.BorderSizePixel = 0
    FramePage.ClipsDescendants = true
    FramePage.Position = UDim2.new(0, 0, 0.02359882, 0)
    FramePage.Size = UDim2.new(0, 395, 0, 331)
    FramePage.Visible = true 

    ScolPage.Name = "ScolPage"
    ScolPage.Parent = FramePage
    ScolPage.Active = true
    ScolPage.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
    ScolPage.BorderSizePixel = 0
    ScolPage.Size = UDim2.new(0, 395, 0, 324)
    ScolPage.ScrollBarThickness = 3
    ScolPage.ScrollBarImageColor3 =  Color3.fromRGB(255, 0, 125)

    MainPage.Name = "MainPage"
    MainPage.Parent = ScolPage
    MainPage.BackgroundTransparency = 1 
    MainPage.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
    MainPage.BorderSizePixel = 0
    MainPage.Size = UDim2.new(0, 395, 0, 324)

    UIGridLayout_MainPage.Parent = MainPage
    UIGridLayout_MainPage.SortOrder = Enum.SortOrder.LayoutOrder
    UIGridLayout_MainPage.CellPadding = UDim2.new(0, 20, 0, 10)
    UIGridLayout_MainPage.CellSize = UDim2.new(0, 170, 0, 295)

    UIListLayout_MainPage.Parent = MainPage
    UIListLayout_MainPage.SortOrder = Enum.SortOrder.LayoutOrder
    UIListLayout_MainPage.Padding = UDim.new(0, 5)

    UIPadding_MainPage.Parent = MainPage
    UIPadding_MainPage.PaddingLeft = UDim.new(0, 16)
    UIPadding_MainPage.PaddingTop = UDim.new(0, 10)


    TextButton_Tap.MouseButton1Click:connect(function (  )
        currentservertoggled = MainPage.Name
        for i, v in next, pagesFolder:GetChildren() do
            if v.Name == "MainFramePage" then
                -- TweenService:Create(
                --     fucklib,
                --     TweenInfo.new(0.15, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
                --     {BackgroundTransparency = 0}
                -- ):Play()
                v.Visible = false

            end

            MainFramePage.Visible = true
       --     wait(0.125)
            -- TweenService:Create(
            --     fucklib,
            --     TweenInfo.new(0.15, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            --     {BackgroundTransparency = 1}
            -- ):Play()
        --    MainPage:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0), UDim2.new(0.5, 0, 0.5, 0), "In", "Quad", 0.15, true)
        end
        
    for i ,v in next , ScolTap:GetChildren() do
        if v:IsA("TextButton") then
            TweenService:Create(
                v.TextLabel_Tap,
                TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
                {Size = UDim2.new(0, 0, 0, 0)}
            ):Play()
            TweenService:Create(
                v,
                TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
                {TextColor3 = Color3.fromRGB(155, 155, 155)}
            ):Play()
            
            
        end
        TweenService:Create(
            TextLabel_Tap,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {Size = UDim2.new(0, 50, 0, 2)}
        ):Play()
        TweenService:Create(
            TextButton_Tap,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {TextColor3 = Color3.fromRGB(255, 255, 255)}
        ):Play()
    end
 end)



    if fs == false then
        TweenService:Create(
            TextLabel_Tap,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {Size = UDim2.new(0, 50, 0, 2)}
        ):Play()
        TweenService:Create(
            TextButton_Tap,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {TextColor3 = Color3.fromRGB(255, 255, 255)}
        ):Play()

        MainFramePage.Visible = true
        MainFramePage.Name  = text .. "Server"
        fs  = true
    end

local page = {}

function page:addpage()

    local Page = Instance.new("Frame")
    local ScolPage2 = Instance.new("ScrollingFrame")
    
    
    Page.Name = "Page"
    Page.Parent = MainPage
    Page.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    Page.BorderSizePixel = 0
    Page.Position = UDim2.new(0.51645571, 0, 0.0526315793, 0)
    Page.Size = UDim2.new(0, 178, 0, 262)
    
    ScolPage2.Name = "ScolPage"
    ScolPage2.Parent = Page
    ScolPage2.Active = true
    ScolPage2.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
    ScolPage2.BorderSizePixel = 0
    ScolPage2.Size = UDim2.new(0, 185, 0, 298)
    ScolPage2.ScrollBarThickness = 3
    ScolPage2.ScrollBarImageColor3 =  Color3.fromRGB(235, 235, 235)
    

    local UIListLayout_ScolPage2 = Instance.new("UIListLayout")

    UIListLayout_ScolPage2.Parent = ScolPage2
    UIListLayout_ScolPage2.SortOrder = Enum.SortOrder.LayoutOrder
    UIListLayout_ScolPage2.Padding = UDim.new(0, 7)

    
    local UIPadding_ScolPage2 = Instance.new("UIPadding")

    UIPadding_ScolPage2.Parent = ScolPage2
    UIPadding_ScolPage2.PaddingLeft = UDim.new(0,15)
    UIPadding_ScolPage2.PaddingTop = UDim.new(0, 15)

    game:GetService("RunService").Stepped:Connect(function ()
        pcall(function ()
              ScolTap.CanvasSize = UDim2.new(0,UIListLayout_ScolTap.AbsoluteContentSize.X  ,0,0)  
              ScolPage.CanvasSize = UDim2.new(0,0,0,UIGridLayout_MainPage.AbsoluteContentSize.Y + 20 )  
              ScolPage2.CanvasSize = UDim2.new(0,0,0,UIListLayout_ScolPage2.AbsoluteContentSize.Y+ 30 )  
        end)
    end)

    
local ems = {}

function ems:Button(text,callback)
    


    local ToggleFrame = Instance.new("Frame")
    
    ToggleFrame.Name = "ToggleFrame"
    ToggleFrame.Parent = ScolPage2
    ToggleFrame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
    ToggleFrame.BorderSizePixel = 0
    ToggleFrame.BackgroundTransparency = 1
    ToggleFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    ToggleFrame.Size = UDim2.new(0, 155, 0, 22)

    local emsTextButton = Instance.new("TextButton")

    emsTextButton.Parent = ToggleFrame
    emsTextButton.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
    emsTextButton.BackgroundTransparency = 1
    emsTextButton.AnchorPoint = Vector2.new(0.5, 0.5)
    emsTextButton.Position = UDim2.new(0.5, 0, 0.5, 0)
    emsTextButton.Size = UDim2.new(1, 0, 0.8, 0)
    emsTextButton.Font = Enum.Font.GothamSemibold
    emsTextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
    emsTextButton.TextSize = 13.000
    emsTextButton.TextWrapped = true
    emsTextButton.Text = ""
    emsTextButton.BorderSizePixel = 0
    emsTextButton.AutoButtonColor = false 

    local TextButton_Pageframe_Uiconner = Instance.new("UICorner")
            
    TextButton_Pageframe_Uiconner.CornerRadius = UDim.new(0, 3)
    TextButton_Pageframe_Uiconner.Name = ""
    TextButton_Pageframe_Uiconner.Parent = ToggleFrame

    local TextLabel_emsTextButton = Instance.new("TextLabel") 

    TextLabel_emsTextButton.Parent = emsTextButton
    TextLabel_emsTextButton.Name = "TextLabel_emsTextButton"
    TextLabel_emsTextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TextLabel_emsTextButton.AnchorPoint = Vector2.new(0.5, 0.5)
    TextLabel_emsTextButton.Position = UDim2.new(0.5, 0, 0.5, 0)
    TextLabel_emsTextButton.Size = UDim2.new(0, 0, 0, 0)
    TextLabel_emsTextButton.Font = Enum.Font.GothamSemibold
    TextLabel_emsTextButton.Text = text
    TextLabel_emsTextButton.TextColor3 = Color3.fromRGB(255, 0, 95)
    TextLabel_emsTextButton.TextSize = 10.000
    TextLabel_emsTextButton.BorderSizePixel = 0

    local MheeFrameStroke = Instance.new("UIStroke",ToggleFrame)
                    
    MheeFrameStroke.Thickness = 1
    MheeFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
    MheeFrameStroke.Color = Color3.fromRGB(255, 0, 95)
    MheeFrameStroke.Transparency = 0

    emsTextButton.MouseButton1Click:Connect(function()
        TweenService:Create(
            TextLabel_emsTextButton,
            TweenInfo.new(0.1, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {TextSize =5} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        wait(0.1)
        TweenService:Create(
            TextLabel_emsTextButton,
            TweenInfo.new(0.1, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {TextSize = 10} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        pcall(callback)
    end)

    
    emsTextButton.MouseEnter:Connect(function (  )
    --    if joincheck.check1 == false then

            TweenService:Create(
                emsTextButton,
                TweenInfo.new(0.5, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
                {BackgroundColor3 =  Color3.fromRGB(255, 0, 95)} -- UDim2.new(0, 128, 0, 25)
            ):Play()
--     end
        -- joincheck = not joincheck
        -- callback(joincheck)
    end)
    emsTextButton.MouseLeave:Connect(function (  )

            TweenService:Create(
                emsTextButton,
                TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
                {BackgroundColor3 =  Color3.fromRGB(255, 0, 95)} -- UDim2.new(0, 128, 0, 25)
            ):Play()
    end)
end

function ems:Button1(text,callback)

    local ToggleFrame1 = Instance.new("Frame")
    
    ToggleFrame1.Name = "ToggleFrame"
    ToggleFrame1.Parent = ScolPage2
    ToggleFrame1.BackgroundColor3 = Color3.fromRGB(255, 0 ,95)
    ToggleFrame1.BorderSizePixel = 0
    ToggleFrame1.BackgroundTransparency = 0
    ToggleFrame1.Position = UDim2.new(0.5, 0, 0.5, 0)
    ToggleFrame1.Size = UDim2.new(0, 155, 0, 22)

    local emsTextButton1 = Instance.new("TextButton")

    emsTextButton1.Parent = ToggleFrame1
    emsTextButton1.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
    emsTextButton1.BackgroundTransparency = 1
    emsTextButton1.AnchorPoint = Vector2.new(0.5, 0.5)
    emsTextButton1.Position = UDim2.new(0.5, 0, 0.5, 0)
    emsTextButton1.Size = UDim2.new(1, 0, 0.8, 0)
    emsTextButton1.Font = Enum.Font.GothamSemibold
    emsTextButton1.TextColor3 = Color3.fromRGB(255, 255, 255)
    emsTextButton1.TextSize = 13.000
    emsTextButton1.TextWrapped = true
    emsTextButton1.Text = ""
    emsTextButton1.BorderSizePixel = 0
    emsTextButton1.AutoButtonColor = false 

    local TextButton_Pageframe_Uiconner1 = Instance.new("UICorner")
            
    TextButton_Pageframe_Uiconner1.CornerRadius = UDim.new(0, 3)
    TextButton_Pageframe_Uiconner1.Name = ""
    TextButton_Pageframe_Uiconner1.Parent = ToggleFrame1

    local TextLabel_emsTextButton1 = Instance.new("TextLabel") 

    TextLabel_emsTextButton1.Parent = emsTextButton1
    TextLabel_emsTextButton1.Name = "TextLabel_emsTextButton"
    TextLabel_emsTextButton1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    TextLabel_emsTextButton1.AnchorPoint = Vector2.new(0.5, 0.5)
    TextLabel_emsTextButton1.Position = UDim2.new(0.5, 0, 0.5, 0)
    TextLabel_emsTextButton1.Size = UDim2.new(0, 0, 0, 0)
    TextLabel_emsTextButton1.Font = Enum.Font.GothamSemibold
    TextLabel_emsTextButton1.Text = text
    TextLabel_emsTextButton1.TextColor3 = Color3.fromRGB(255, 255 ,255)
    TextLabel_emsTextButton1.TextSize = 10.000
    TextLabel_emsTextButton1.BorderSizePixel = 0

    local MheeFrameStroke1 = Instance.new("UIStroke",ToggleFrame1)
                    
    MheeFrameStroke1.Thickness = 1
    MheeFrameStroke1.LineJoinMode = Enum.LineJoinMode.Round
    MheeFrameStroke1.Color = Color3.fromRGB(255, 0 ,95)
    MheeFrameStroke1.Transparency = 0

    emsTextButton1.MouseButton1Click:Connect(function()
        TweenService:Create(
            TextLabel_emsTextButton1,
            TweenInfo.new(0.1, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {TextSize =5} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        wait(0.1)
        TweenService:Create(
            TextLabel_emsTextButton1,
            TweenInfo.new(0.1, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {TextSize = 10} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        pcall(callback)
    end)

    
    emsTextButton1.MouseEnter:Connect(function (  )
    --    if joincheck.check1 == false then

            TweenService:Create(
                emsTextButton1,
                TweenInfo.new(0.5, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
                {BackgroundColor3 =  Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
            ):Play()
--     end
        -- joincheck = not joincheck
        -- callback(joincheck)
    end)
    emsTextButton1.MouseLeave:Connect(function (  )

            TweenService:Create(
                emsTextButton1,
                TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
                {BackgroundColor3 =  Color3.fromRGB(255, 255, 255)} -- UDim2.new(0, 128, 0, 25)
            ):Play()
    end)
end

function  ems:Toggle(text,de,callback)

    local togdoc = {boolen = false ; }
    local ToggleFrame = Instance.new("Frame")
    
    ToggleFrame.Name = "ToggleFrame"
    ToggleFrame.Parent = ScolPage2
    ToggleFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    ToggleFrame.BorderSizePixel = 0
    ToggleFrame.BackgroundTransparency = 1
    ToggleFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    ToggleFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    ToggleFrame.Size = UDim2.new(0, 10, 0, 30)
    
    local ToggleButton = Instance.new("TextButton")

    ToggleButton.Parent = ToggleFrame
    ToggleButton.BackgroundColor3 = Color3.fromRGB( 0, 0, 60)
    ToggleButton.BackgroundTransparency = 1
    ToggleButton.AnchorPoint = Vector2.new(0, 0.5)
    ToggleButton.Position = UDim2.new(0.5, 0, 0.5, 0)
    ToggleButton.Size = UDim2.new(0, 155, 0, 25)
    ToggleButton.Font = Enum.Font.GothamSemibold
    ToggleButton.TextColor3 = Color3.fromRGB(255, 255, 255)
    ToggleButton.TextSize = 13.000
    ToggleButton.TextWrapped = false
    ToggleButton.Text = ""
    ToggleButton.BorderSizePixel = 0 
    ToggleButton.AutoButtonColor = false 
    ToggleButton.ClipsDescendants = true 

    local ToggleButton2 = Instance.new("TextButton")

    ToggleButton2.Parent = ToggleFrame
    ToggleButton2.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    ToggleButton2.BackgroundTransparency = 1
    ToggleButton2.AnchorPoint = Vector2.new(0.5, 0.5)
    ToggleButton2.Position = UDim2.new(1, 0, 0.45, 0)
    ToggleButton2.Size = UDim2.new(0, 20, 0, 20)
    ToggleButton2.Font = Enum.Font.GothamSemibold
    ToggleButton2.TextColor3 = Color3.fromRGB(255, 255, 255)
    ToggleButton2.TextSize = 13.000
    ToggleButton2.TextWrapped = false
    ToggleButton2.Text = ""
    ToggleButton2.BorderSizePixel = 0 


    local TextLabelToggle = Instance.new("TextLabel") 

    TextLabelToggle.Parent = ToggleButton
    TextLabelToggle.Name = "TextLabelToggle"
    TextLabelToggle.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TextLabelToggle.AnchorPoint = Vector2.new(0.5, 0.5)
    TextLabelToggle.Position = UDim2.new(0.64, 0, 0.4, 0)
    TextLabelToggle.Size =  UDim2.new(0, 150, 0, 40)
    TextLabelToggle.Font = Enum.Font.GothamBold
    TextLabelToggle.Text = tostring(text)
    TextLabelToggle.TextColor3 = Color3.fromRGB(255, 255, 255)
    TextLabelToggle.TextSize = 11.000
    TextLabelToggle.BorderSizePixel = 0
    TextLabelToggle.TextScaled = true
    TextLabelToggle.BackgroundTransparency = 1
    TextLabelToggle.TextXAlignment = Enum.TextXAlignment.Left
    local resizetext2 =  Instance.new("UITextSizeConstraint",TextLabelToggle)
    resizetext2.MaxTextSize = 11
    
    local TextButton_2_Toggle = Instance.new("TextButton")

    TextButton_2_Toggle.Parent = ToggleButton2
    TextButton_2_Toggle.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TextButton_2_Toggle.BorderColor3 = Color3.fromRGB(249, 53, 139)
    TextButton_2_Toggle.BorderSizePixel = 0
    TextButton_2_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
    TextButton_2_Toggle.Position = UDim2.new(0.5, 0, 0.5, 0)
    TextButton_2_Toggle.Size = UDim2.new(0, 19, 0, 19)
    TextButton_2_Toggle.Font = Enum.Font.SourceSans
    TextButton_2_Toggle.Text = " "
    TextButton_2_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
    TextButton_2_Toggle.TextSize = 12.000
    TextButton_2_Toggle.AutoButtonColor = false 

    local TextButton_3_Toggle = Instance.new("TextButton")


    TextButton_3_Toggle.Parent = TextButton_2_Toggle
    TextButton_3_Toggle.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
    TextButton_3_Toggle.BorderColor3 = Color3.fromRGB(255, 0, 95)
    TextButton_3_Toggle.BorderSizePixel = 0
    TextButton_3_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
    TextButton_3_Toggle.Position = UDim2.new(0.5, 0, 0.5, 0)
    TextButton_3_Toggle.Size = UDim2.new(0, 17, 0, 17)
    TextButton_3_Toggle.Font = Enum.Font.SourceSans
    TextButton_3_Toggle.Text = " "
    TextButton_3_Toggle.TextColor3 = Color3.fromRGB(0, 0, 0)
    TextButton_3_Toggle.TextSize = 12.000
    TextButton_3_Toggle.AutoButtonColor = false 

    local ImageLabel_Toggle = Instance.new("ImageButton")


    ImageLabel_Toggle.Parent = TextButton_2_Toggle
    ImageLabel_Toggle.BackgroundTransparency = 1
    ImageLabel_Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    ImageLabel_Toggle.Size = UDim2.new(0, 0, 0, 0)
    ImageLabel_Toggle.Image = "rbxassetid://5880482965"
    ImageLabel_Toggle.AnchorPoint = Vector2.new(0.5, 0.5)
    ImageLabel_Toggle.Position = UDim2.new(0.47, 0, 0.5, 0)


    local FrameToggle = Instance.new("UICorner")
            
    FrameToggle.CornerRadius = UDim.new(0, 4)
    FrameToggle.Name = ""
    FrameToggle.Parent = emsTextButton

    local FrameToggle1 = Instance.new("UICorner")
            
    FrameToggle1.CornerRadius = UDim.new(0, 4)
    FrameToggle1.Name = ""
    FrameToggle1.Parent = TextButton_2_Toggle

    local FrameToggle2 = Instance.new("UICorner")
            
    FrameToggle2.CornerRadius = UDim.new(0, 4)
    FrameToggle2.Name = ""
    FrameToggle2.Parent = ImageLabel_Toggle

    local FrameToggle3 = Instance.new("UICorner")
            
    FrameToggle3.CornerRadius = UDim.new(0, 4)
    FrameToggle3.Name = ""
    FrameToggle3.Parent = TextButton_3_Toggle

    TextButton_3_Toggle.MouseButton1Click:Connect(function (  )
        if togdoc.boolen ==false then
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 23, 0, 23), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
        else
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
     --       ImageLabel_Toggle.Visible = false
        end
        togdoc.boolen = not togdoc.boolen
        pcall(callback,togdoc.boolen)
    end)

    ImageLabel_Toggle.MouseButton1Click:Connect(function (  )
        if togdoc.boolen ==false then
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 23, 0, 23), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
        else
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
     --       ImageLabel_Toggle.Visible = false
        end
        togdoc.boolen = not togdoc.boolen
        pcall(callback,togdoc.boolen)
    end)

    TextButton_2_Toggle.MouseButton1Click:Connect(function (  )
        if togdoc.boolen ==false then
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
        else
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
     --       ImageLabel_Toggle.Visible = false
        end
        togdoc.boolen = not togdoc.boolen
        pcall(callback,togdoc.boolen)
    end)


    ToggleButton.MouseButton1Click:Connect(function (  )
        if togdoc.boolen ==false then
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
        else
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
     --       ImageLabel_Toggle.Visible = false
        end
        togdoc.boolen = not togdoc.boolen
        pcall(callback,togdoc.boolen)
    end)

        if de == true then
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 27, 0, 27), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            wait(0.1)
            ImageLabel_Toggle:TweenSizeAndPosition(UDim2.new(0, 19, 0, 19), UDim2.new(0.5, 0, 0.5, 0), "In", "Bounce", 0.1, true)
            togdoc.boolen = not togdoc.boolen
            pcall(callback,togdoc.boolen)
        end
    end

function ems:DropDown(text,text2,list,callback)


    local checkdrop = {checkscol = false ; }
    local DropFrame = Instance.new("Frame")
    local dropfuc = {}

    DropFrame.Name = "DropFrame"
    DropFrame.Parent = ScolPage2
    DropFrame.BackgroundColor3 = Color3.fromRGB(255, 0 ,95)
    DropFrame.BorderSizePixel = 0
    DropFrame.BackgroundTransparency = 1
    DropFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    DropFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    DropFrame.Size = UDim2.new(0, 155, 0, 45)
    DropFrame.BackgroundTransparency = 1
    DropFrame.ClipsDescendants = true 

    local TextLabelDrop = Instance.new("TextLabel") 

    TextLabelDrop.Parent = DropFrame
    TextLabelDrop.Name = "TextLabelDrop"
    TextLabelDrop.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TextLabelDrop.BackgroundTransparency = 1
    TextLabelDrop.AnchorPoint = Vector2.new(0.5, 0.5)
    TextLabelDrop.Position = UDim2.new(0.5, 0, 0.2, 0)
    TextLabelDrop.Size = UDim2.new(0, 155, 0, 15)
    TextLabelDrop.Font = Enum.Font.GothamSemibold
    TextLabelDrop.Text = text
    TextLabelDrop.TextColor3 = Color3.fromRGB(255, 255, 255)
    TextLabelDrop.TextSize = 10.000
    TextLabelDrop.BorderSizePixel = 0
    TextLabelDrop.ClipsDescendants = true 

    local FrameDrop = Instance.new("Frame")
    
    FrameDrop.Name = "FrameDrop"
    FrameDrop.Parent = DropFrame
    FrameDrop.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    FrameDrop.BorderSizePixel = 0
    FrameDrop.BackgroundTransparency = 1
    FrameDrop.AnchorPoint = Vector2.new(0.5, 0.5)
    FrameDrop.Position = UDim2.new(0.5, 0, 0.75, 0)
    FrameDrop.Size = UDim2.new(0, 155, 0, 27)
    FrameDrop.BackgroundTransparency = 0
    FrameDrop.ClipsDescendants = true 

    local DropButton = Instance.new("TextButton")

    DropButton.Parent = FrameDrop
    DropButton.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    DropButton.BackgroundTransparency = 1
    DropButton.AnchorPoint = Vector2.new(0.5, 0.5)
    DropButton.Position = UDim2.new(0.5, 0, 0.5, 0)
    DropButton.Size = UDim2.new(0, 155, 0, 24)
    DropButton.Font = Enum.Font.GothamSemibold
    DropButton.TextColor3 = Color3.fromRGB(255, 255, 255)
    DropButton.TextSize = 11.000
    DropButton.TextWrapped = true
    DropButton.Text = ""
    DropButton.BorderSizePixel = 0 
    DropButton.AutoButtonColor = false 
    DropButton.ClipsDescendants = true 

    local TextLabelDrop2 = Instance.new("TextLabel") 

    TextLabelDrop2.Parent = DropButton
    TextLabelDrop2.Name = "TextLabelDrop"
    TextLabelDrop2.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TextLabelDrop2.BackgroundTransparency = 1
    TextLabelDrop2.AnchorPoint = Vector2.new(0.5, 0.5)
    TextLabelDrop2.Position = UDim2.new(0.5, 0, 0.5, 0)
    TextLabelDrop2.Size = UDim2.new(0, 155, 0, 22)
    TextLabelDrop2.Font = Enum.Font.GothamSemibold
    TextLabelDrop2.Text = text2.." : "
    TextLabelDrop2.TextColor3 = Color3.fromRGB(255, 255, 255)
    TextLabelDrop2.TextSize = 10.000
    TextLabelDrop2.BorderSizePixel = 0
    TextLabelDrop2.ClipsDescendants = true 

    local DropConer = Instance.new("UICorner")
            
    DropConer.CornerRadius = UDim.new(0, 4)
    DropConer.Name = ""
    DropConer.Parent = DropButton

    local DropConer1 = Instance.new("UICorner")
            
    DropConer1.CornerRadius = UDim.new(0, 4)
    DropConer1.Name = ""
    DropConer1.Parent = FrameDrop
    

    
    local TextButton_Dropdown = Instance.new("TextButton")

    TextButton_Dropdown.Parent = DropButton
    TextButton_Dropdown.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TextButton_Dropdown.BorderSizePixel = 0
    TextButton_Dropdown.Size = UDim2.new(0, 22, 0, 24)
    TextButton_Dropdown.Font = Enum.Font.SourceSans
    TextButton_Dropdown.Text = "  "
    TextButton_Dropdown.TextColor3 = Color3.fromRGB(0, 0, 0)
    TextButton_Dropdown.TextSize = 14.000
    TextButton_Dropdown.AutoButtonColor = false 
    TextButton_Dropdown.AnchorPoint = Vector2.new(0.5, 0.5)
    TextButton_Dropdown.Position = UDim2.new(0.91, 0, 0.5, 0)
    
    local DropConer2 = Instance.new("UICorner")
            
    DropConer2.CornerRadius = UDim.new(0, 4)
    DropConer2.Name = ""
    DropConer2.Parent = TextButton_Dropdown

    local DropArbt_listimage = Instance.new("ImageButton")
                            
    DropArbt_listimage.Parent = TextButton_Dropdown
    DropArbt_listimage.BackgroundTransparency = 1
    DropArbt_listimage.AnchorPoint = Vector2.new(0.5, 0.5)
    DropArbt_listimage.Position = UDim2.new(0.5, 0, 0.5, 0)
    DropArbt_listimage.BorderSizePixel = 0
    DropArbt_listimage.Size = UDim2.new(0, 20, 0, 20)
    DropArbt_listimage.Image = "http://www.roblox.com/asset/?id=6031091004"

    local ListFrame = Instance.new("Frame")
    
    ListFrame.Name = "ListFrame"
    ListFrame.Parent = ScolPage2
    ListFrame.BackgroundColor3 = Color3.fromRGB(255, 0 ,95)
    ListFrame.BorderSizePixel = 0
    ListFrame.BackgroundTransparency = 1
    ListFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    ListFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    ListFrame.Size = UDim2.new(0, 155, 0, 0)
    ListFrame.BorderSizePixel = 0 
    ListFrame.ClipsDescendants = true 
    ListFrame.Visible = false 

    local ScolPage_list = Instance.new("ScrollingFrame")


    local UIListLayout_MainPage_list = Instance.new("UIListLayout")
    local UIPadding_MainPage_list = Instance.new("UIPadding")


    ScolPage_list.Name = "ScolPage_list"
    ScolPage_list.Parent = ListFrame
    ScolPage_list.Active = true
    ScolPage_list.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
    ScolPage_list.BorderSizePixel = 0
    ScolPage_list.Size = UDim2.new(0, 155, 0, 0)
    ScolPage_list.ScrollBarThickness = 3
    ScolPage_list.AnchorPoint = Vector2.new(0.5, 0.5)
    ScolPage_list.Position = UDim2.new(0.5, 0, 0.5, 0)
    ScolPage_list.ClipsDescendants = true 
    ScolPage_list.ScrollBarImageColor3 =  Color3.fromRGB(235, 235, 235)
    ScolPage_list.ScrollBarImageColor3 =  Color3.fromRGB(235, 235, 235)

    UIListLayout_MainPage_list.Parent = ScolPage_list
    UIListLayout_MainPage_list.SortOrder = Enum.SortOrder.LayoutOrder
    UIListLayout_MainPage_list.Padding = UDim.new(0, 5)

    UIPadding_MainPage_list.Parent = ScolPage_list
    UIPadding_MainPage_list.PaddingLeft = UDim.new(0, 0)
    UIPadding_MainPage_list.PaddingTop = UDim.new(0, 0)


    local DropConer4 = Instance.new("UICorner")
            
    DropConer4.CornerRadius = UDim.new(0, 4)
    DropConer4.Name = ""
    DropConer4.Parent = ListFrame

    local framesize =  50
    local count = 0 
    for i , v in pairs(list) do 
        count = count + 1 
        
        if count == 1 then
            framesize = 50 
        elseif count == 2 then
            framesize = 70 
        elseif count >= 3 then
            framesize = 150 
        end

    local listDropButton = Instance.new("TextButton")

    listDropButton.Parent = ScolPage_list
    listDropButton.BackgroundColor3 = Color3.fromRGB(15, 15 ,15)
    listDropButton.BorderSizePixel = 0
    listDropButton.Size = UDim2.new(0, 155, 0, 24)
    listDropButton.Font = Enum.Font.GothamSemibold
    listDropButton.Text = tostring(v)
    listDropButton.TextColor3 = Color3.fromRGB(255, 20, 95)
    listDropButton.TextSize = 11.000
    listDropButton.AutoButtonColor = false 
    listDropButton.AnchorPoint = Vector2.new(0.5, 0.5)
    listDropButton.Position = UDim2.new(0.5, 0, 0.5, 0)

    listDropButton.MouseButton1Click:Connect(function()
        TweenService:Create(
            ListFrame,
            TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 155, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        TweenService:Create(
            ScolPage_list,
            TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 155, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        repeat
            wait()
        until ScolPage_list.Size ==  UDim2.new(0, 155, 0, 0)
        ListFrame.Visible = false
        TextLabelDrop2.Text = text2.." : "..tostring(v)  
        callback(v)
    end
)

    listDropButton.MouseEnter:Connect(function ()
        TweenService:Create(
            listDropButton,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {BackgroundColor3 = Color3.fromRGB(25, 25, 25)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
    end)
    listDropButton.MouseLeave:Connect(function ()
        TweenService:Create(
            listDropButton,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {BackgroundColor3 = Color3.fromRGB(15, 15, 15)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
    end)

    ScolPage_list.CanvasSize = UDim2.new(0,0,0,UIListLayout_MainPage_list.AbsoluteContentSize.Y + 10)  



end

    DropArbt_listimage.MouseButton1Click:Connect(function()     
        if checkdrop.checkscol == false then 
            ListFrame.Visible = true 
            TweenService:Create(
                DropArbt_listimage,
                TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
                {Rotation = -180}
            ):Play()
            TweenService:Create(
                ListFrame,
                TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
                {Size =  UDim2.new(0, 155, 0, framesize)} -- UDim2.new(0, 128, 0, 25)
            ):Play()
            TweenService:Create(
                ScolPage_list,
                TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
                {Size =  UDim2.new(0, 155, 0, framesize)} -- UDim2.new(0, 128, 0, 25)
            ):Play()

    else
        TweenService:Create(
            DropArbt_listimage,
            TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
            {Rotation = 0}
        ):Play()
        TweenService:Create(
            ListFrame,
            TweenInfo.new(0.2, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 155, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        TweenService:Create(
            ScolPage_list,
            TweenInfo.new(0.2, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 155, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        repeat
            wait()
        until ScolPage_list.Size ==  UDim2.new(0, 155, 0, 0)
        ListFrame.Visible = false
        end
        checkdrop.checkscol  = not    checkdrop.checkscol  
        pcall(callback,   checkdrop.checkscol )
    end)


    DropButton.MouseButton1Click:Connect(function()     
        if checkdrop.checkscol == false then 
            ListFrame.Visible = true 
            TweenService:Create(
                DropArbt_listimage,
                TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
                {Rotation = -180}
            ):Play()
            TweenService:Create(
                ListFrame,
                TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
                {Size =  UDim2.new(0, 155, 0, framesize)} -- UDim2.new(0, 128, 0, 25)
            ):Play()
            TweenService:Create(
                ScolPage_list,
                TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
                {Size =  UDim2.new(0, 155, 0, framesize)} -- UDim2.new(0, 128, 0, 25)
            ):Play()

    else
        TweenService:Create(
            DropArbt_listimage,
            TweenInfo.new(0.3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out),
            {Rotation = 0}
        ):Play()
        TweenService:Create(
            ListFrame,
            TweenInfo.new(0.2, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 155, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        TweenService:Create(
            ScolPage_list,
            TweenInfo.new(0.2, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 155, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        repeat
            wait()
        until ScolPage_list.Size ==  UDim2.new(0, 155, 0, 0)
        ListFrame.Visible = false
        end
        checkdrop.checkscol  = not    checkdrop.checkscol  
        pcall(callback,   checkdrop.checkscol )
    end)

    function dropfuc:Add(text2)
       
    local listDropButton = Instance.new("TextButton")

    listDropButton.Parent = ScolPage_list
    listDropButton.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
    listDropButton.BorderSizePixel = 0
    listDropButton.Size = UDim2.new(0, 155, 0, 24)
    listDropButton.Font = Enum.Font.GothamSemibold
    listDropButton.Text = tostring(text2)
    listDropButton.TextColor3 = Color3.fromRGB(255, 0, 95)
    listDropButton.TextSize = 11.000
    listDropButton.AutoButtonColor = false 
    listDropButton.AnchorPoint = Vector2.new(0.5, 0.5)
    listDropButton.Position = UDim2.new(0.5, 0, 0.5, 0)



    listDropButton.MouseButton1Click:Connect(function()
        TweenService:Create(
            ListFrame,
            TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 140, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        TweenService:Create(
            ScolPage_list,
            TweenInfo.new(0.3, Enum.EasingStyle.Back, Enum.EasingDirection.Out),
            {Size =  UDim2.new(0, 140, 0, 0)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
        repeat
            wait()
        until ScolPage_list.Size ==  UDim2.new(0, 140, 0, 0)
        ListFrame.Visible = false
        TextLabelDrop2.Text = text.." : "..tostring(text2)  
        callback(text2)
    end
)

    listDropButton.MouseEnter:Connect(function ()
        TweenService:Create(
            listDropButton,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {BackgroundColor3 = Color3.fromRGB(25, 25, 25)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
    end)
    listDropButton.MouseLeave:Connect(function ()
        TweenService:Create(
            listDropButton,
            TweenInfo.new(0.3, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
            {BackgroundColor3 = Color3.fromRGB(15, 15, 15)} -- UDim2.new(0, 128, 0, 25)
        ):Play()
    end)

    ScolPage_list.CanvasSize = UDim2.new(0,0,0,UIListLayout_MainPage_list.AbsoluteContentSize.Y + 10)  


    end

    function dropfuc:Clear()
    for i, v in next, ScolPage_list:GetChildren() do
        if v:IsA("TextButton")  then 
        v:Destroy()
        
        end
        ScolPage_list.CanvasSize = UDim2.new(0,0,0,UIListLayout_MainPage_list.AbsoluteContentSize.Y + 10)  
    end   

end  
    return  dropfuc
end

function ems:Slder(text,min,max,de,callback)
    local SliderFunc = {}
    local SliderFrame = Instance.new("Frame")


    SliderFrame.Name = "SliderFrame"
    SliderFrame.Parent = ScolPage2
    SliderFrame.BackgroundColor3 = Color3.fromRGB(255,255,255)
    SliderFrame.BorderSizePixel = 0
    SliderFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    SliderFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
    SliderFrame.Size = UDim2.new(0, 155, 0, 50)
    SliderFrame.BackgroundTransparency = 1
    SliderFrame.ClipsDescendants = true 

    local fakeclick = Instance.new("TextButton",SliderFrame)

    fakeclick.BackgroundColor3 = Color3.fromRGB(15,15,15)
    fakeclick.BorderSizePixel = 0
    fakeclick.Size = UDim2.new(1, 0, 1, 0)
    fakeclick.Font = Enum.Font.GothamSemibold
    fakeclick.Text = ""
    fakeclick.TextColor3 = Color3.fromRGB(255, 255, 255)
    fakeclick.Transparency = 1
    fakeclick.TextSize = 10.000
    fakeclick.AutoButtonColor = false 
    fakeclick.AnchorPoint = Vector2.new(0.5, 0.5)
    fakeclick.Position = UDim2.new(0.5, 0, 0.3, 0)

    local Conner_SliderFrame1 = Instance.new("UICorner")
       
    Conner_SliderFrame1.CornerRadius = UDim.new(0, 5)
    Conner_SliderFrame1.Name = ""
    Conner_SliderFrame1.Parent = SliderFrame

    local SlisFrameStroke = Instance.new("UIStroke",SliderFrame)
                    
    SlisFrameStroke.Thickness = 1
    SlisFrameStroke.LineJoinMode = Enum.LineJoinMode.Round
    SlisFrameStroke.Color = Color3.fromRGB(255, 0, 95)
    SlisFrameStroke.Transparency = 0
    local TalabelSlider = Instance.new("TextLabel") 

    TalabelSlider.Parent = SliderFrame
    TalabelSlider.Name = "TalabelSlider"
    TalabelSlider.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    TalabelSlider.BackgroundTransparency = 1
    TalabelSlider.AnchorPoint = Vector2.new(0.5, 0.5)
    TalabelSlider.Position = UDim2.new(0.5, 0, 0.2, 0)
    TalabelSlider.Size = UDim2.new(0, 145, 0, 20)
    TalabelSlider.Font = Enum.Font.GothamSemibold
    TalabelSlider.Text = text
    TalabelSlider.TextColor3 = Color3.fromRGB(255, 255, 255)
    TalabelSlider.TextSize = 11.000
    TalabelSlider.BorderSizePixel = 0
    TalabelSlider.ClipsDescendants = true 
    TalabelSlider.TextXAlignment = Enum.TextXAlignment.Left

       
    local ValueFrame = Instance.new("Frame")

    ValueFrame.Name = "ValueFrame"
    ValueFrame.Parent = SliderFrame
    ValueFrame.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
    ValueFrame.BorderSizePixel = 0
    ValueFrame.BackgroundTransparency = 0
    ValueFrame.AnchorPoint = Vector2.new(0.5, 0.5)
    ValueFrame.Position = UDim2.new(0.5, 0, 0.7, 0)
    ValueFrame.Size = UDim2.new(0, 145, 0, 20)
    ValueFrame.BackgroundTransparency = 1
    ValueFrame.ClipsDescendants = true 

    local SecValue = Instance.new("Frame")

    SecValue.Name = "SecValue"
    SecValue.Parent = ValueFrame
    SecValue.BackgroundColor3 = Color3.fromRGB(155, 155, 155)
    SecValue.BorderSizePixel = 0
    SecValue.BackgroundTransparency = 0
    SecValue.AnchorPoint = Vector2.new(0.5, 0.5)
    SecValue.Position = UDim2.new(0.5, 0, 0.5, 0)
    SecValue.Size = UDim2.new(0, 135, 0, 4)
    SecValue.BackgroundTransparency = 0
    SecValue.ClipsDescendants = false 

    
    local MainValue = Instance.new("Frame")

    MainValue.Name = "MainValue"
    MainValue.Parent = SecValue
    MainValue.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    MainValue.BorderSizePixel = 0
    MainValue.BackgroundTransparency = 0
    -- MainValue.AnchorPoint = Vector2.new(0.5, 0.5)
    MainValue.Position = UDim2.new(0., 0, 0., 0)
    MainValue.Size = UDim2.new((de or 0) / max, 0, 0, 4)
    MainValue.BackgroundTransparency = 0
    MainValue.ClipsDescendants = false 

     
    local ConneValue = Instance.new("Frame")

    ConneValue.Name = "ConneValue"
    ConneValue.Parent = SecValue
    ConneValue.BackgroundColor3 = Color3.fromRGB(255,255, 255)
    ConneValue.Size = UDim2.new(0, 10, 0, 10)
    ConneValue.BackgroundTransparency = 0
    ConneValue.BorderSizePixel = 0 
    ConneValue.AnchorPoint = Vector2.new(0.5, 0.5)
    ConneValue.Position = UDim2.new((de or 0)/max, 0.5, 0.5,0.5, 0) 
    ConneValue.ClipsDescendants = false 

    local Conner_Conne = Instance.new("UICorner")
                    
    Conner_Conne.CornerRadius = UDim.new(0, 10)
    Conner_Conne.Name = ""
    Conner_Conne.Parent = ConneValue

            
    local ScolDown_Uiconner2 = Instance.new("UICorner")
                
    ScolDown_Uiconner2.CornerRadius = UDim.new(0, 8)
    ScolDown_Uiconner2.Name = ""
    ScolDown_Uiconner2.Parent = MainValue

    local ScolDown_Uiconner3 = Instance.new("UICorner")
        
    ScolDown_Uiconner3.CornerRadius = UDim.new(0, 8)
    ScolDown_Uiconner3.Name = ""
    ScolDown_Uiconner3.Parent = SecValue


    
    local ShowValueFarm = Instance.new("Frame")

    ShowValueFarm.Name = "ShowValueFarm"
    ShowValueFarm.Parent = SliderFrame
    ShowValueFarm.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
    ShowValueFarm.Size = UDim2.new(0, 50, 0, 14)
    ShowValueFarm.BackgroundTransparency = 1
    ShowValueFarm.BorderSizePixel = 0 
    ShowValueFarm.AnchorPoint = Vector2.new(0.5, 0.5)
    ShowValueFarm.Position = UDim2.new(0.80, 0, 0.28, 0)
    ShowValueFarm.ClipsDescendants = false

    local MheeFrameStroke1 = Instance.new("UIStroke",ShowValueFarm)
                    
    MheeFrameStroke1.Thickness = 1
    MheeFrameStroke1.LineJoinMode = Enum.LineJoinMode.Round
    MheeFrameStroke1.Color = Color3.fromRGB(255, 0, 95)
    MheeFrameStroke1.Transparency = 0

    local CustomValue = Instance.new("TextBox")

    CustomValue.Parent = ShowValueFarm
    CustomValue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    CustomValue.BorderSizePixel = 0
    CustomValue.ClipsDescendants = true
    CustomValue.AnchorPoint = Vector2.new(0.5, 0.5)
    CustomValue.Position = UDim2.new(0.5, 0, 0.5, 0)
    CustomValue.Size = UDim2.new(0, 145, 0, 26)
    CustomValue.Font = Enum.Font.GothamSemibold
    CustomValue.PlaceholderColor3 = Color3.fromRGB(222, 222, 222)
    CustomValue.PlaceholderText =  ""
    CustomValue.Text =  tostring(de and math.floor((de / max) * (max - min) + min) or 0)
    CustomValue.TextColor3 = Color3.fromRGB(255, 255, 255)
    CustomValue.TextSize = 9.000
    CustomValue.BackgroundTransparency = 1

    local ScolDown_Uiconner3222 = Instance.new("UICorner")
        
    ScolDown_Uiconner3222.CornerRadius = UDim.new(0, 4)
    ScolDown_Uiconner3222.Name = ""
    ScolDown_Uiconner3222.Parent = ShowValueFarm
    local function move(input)
        local pos =
            UDim2.new(
                math.clamp((input.Position.X - SecValue.AbsolutePosition.X) / SecValue.AbsoluteSize.X, 0, 1),
                0,
                0.5,
                0
            )
        local pos1 =
            UDim2.new(
                math.clamp((input.Position.X - SecValue.AbsolutePosition.X) / SecValue.AbsoluteSize.X, 0, 1),
                0,
                0,
                5
            )
        
            MainValue:TweenSize(pos1, "Out", "Sine", 0.2, true)

            ConneValue:TweenPosition(pos, "Out", "Sine", 0.2, true)
            local value = math.floor(((pos.X.Scale * max) / max) * (max - min) + min)
            CustomValue.Text = tostring(value)
            callback(value)

        end
        local dragging = false 
        ConneValue.InputBegan:Connect(
            function(input)
                if input.UserInputType == Enum.UserInputType.MouseButton1 then
                    dragging = true

                end
            end
        )
        ConneValue.InputEnded:Connect(
            function(input)
                if input.UserInputType == Enum.UserInputType.MouseButton1 then
                    dragging = false
                 
                end
            end
        )
            
        
        ValueFrame.InputBegan:Connect(
            function(input)
                if input.UserInputType == Enum.UserInputType.MouseButton1 then
                    dragging = true

                end
            end
        )
        ValueFrame.InputEnded:Connect(
            function(input)
                if input.UserInputType == Enum.UserInputType.MouseButton1 then
                    dragging = false
                 
                end
            end
        )


        game:GetService("UserInputService").InputChanged:Connect(
            function(input)
                if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
                    move(input)
                end
            end
            )
                   CustomValue.FocusLost:Connect(function()    
                        MainValue:TweenSize(UDim2.new((CustomValue.Text or 0) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
                        ConneValue:TweenPosition(UDim2.new((CustomValue.Text or 0)/max, 0,0.5, 0) , "Out", "Sine", 0.2, true)
                        CustomValue.Text = tostring(CustomValue.Text and math.floor((CustomValue.Text / max) * (max - min) + min) )
                        pcall(callback,tonumber( CustomValue.Text))
                        -- if  CustomValue.Text == "" then

                        --     MainValue:TweenSize(UDim2.new((CustomValue.PlaceholderText  or 0) / max, 0, 0, 2), "Out", "Sine", 0.2, true)
                        --     ConneValue:TweenPosition(UDim2.new((CustomValue.PlaceholderText  or 0)/max, 0,0, 0) , "Out", "Sine", 0.2, true)
                        --     CustomValue.Text = tostring(CustomValue.PlaceholderText  and math.floor((    CustomValue.PlaceholderText  / max) * (max - min) + min) or 0)
                        --     pcall(callback,CustomValue.PlaceholderText ) 
                        -- end
                    end)

				function SliderFunc:change(tochange)
                    MainValue:TweenSize(UDim2.new((tochange or 0) / max, 0, 0, 5), "Out", "Sine", 0.2, true)
                    ConneValue:TweenPosition(UDim2.new((tochange or 0)/max, 0,0.5, 0) , "Out", "Sine", 0.2, true)
					CustomValue.Text = tostring(tochange and math.floor((CustomValue.Text / max) * (max - min) + min) )
					pcall(callback, tonumber(tochange))
				end
                return  SliderFunc
                
end

function ems:Ti(text)
    local tiframe = Instance.new("Frame")

    tiframe.Name = "tiframe"
    tiframe.Parent = ScolPage2
    tiframe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    tiframe.BackgroundTransparency = 1
    tiframe.BorderSizePixel = 0
    tiframe.ClipsDescendants = true
    tiframe.AnchorPoint = Vector2.new(0.5, 0.5)
    tiframe.Position = UDim2.new(0.5, 0, 0.5, 0)
    tiframe.Size = UDim2.new(0, 155, 0, 20)

    local  lineframe = Instance.new("TextLabel")
                  
    lineframe.Parent = tiframe
    lineframe.BackgroundColor3 = Color3.fromRGB(255, 0 ,95)
    lineframe.BackgroundTransparency = 0
    lineframe.AnchorPoint = Vector2.new(0.6, 0.5)
    lineframe.Position = UDim2.new(0., 0, 0.4, 0)
    lineframe.BorderSizePixel = 0
    lineframe.Size = UDim2.new(0, 40, 0, 1)
    lineframe.Font = Enum.Font.GothamSemibold
    lineframe.TextColor3 = Color3.fromRGB(255, 255, 255)
    lineframe.TextSize = 13.000
    lineframe.Text = ""

    local  lineframe2 = Instance.new("TextLabel")
                  
    lineframe2.Parent = tiframe
    lineframe2.BackgroundColor3 = Color3.fromRGB(255, 0, 95)
    lineframe2.BackgroundTransparency = 0
    lineframe2.AnchorPoint = Vector2.new(0.5, 0.5)
    lineframe2.Position = UDim2.new(1, 0, 0.4, 0)
    lineframe2.BorderSizePixel = 0
    lineframe2.Size = UDim2.new(0, 40, 0, 1)
    lineframe2.Font = Enum.Font.GothamSemibold
    lineframe2.TextColor3 = Color3.fromRGB(255, 255, 255)
    lineframe2.TextSize = 11.000
    lineframe2.Text = ""

    local  lineframe3 = Instance.new("TextLabel")
                  
    lineframe3.Parent = tiframe
    lineframe3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    lineframe3.BackgroundTransparency = 1
    lineframe3.AnchorPoint = Vector2.new(0.5, 0.5)
    lineframe3.Position = UDim2.new(0.5, 0, 0.5, 0)
    lineframe3.BorderSizePixel = 0
    lineframe3.Size = UDim2.new(0, 130, 0, 20)
    lineframe3.Font = Enum.Font.GothamSemibold
    lineframe3.Text = tostring(text)
    lineframe3.TextColor3 = Color3.fromRGB(255, 100, 150)
    lineframe3.TextSize = 12.000
end

function ems:Label(text)

    local labelfuc = {}
    local  Labelxd = Instance.new("TextLabel")
                  
    Labelxd.Parent = ScolPage2
    Labelxd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Labelxd.BackgroundTransparency = 1
    Labelxd.AnchorPoint = Vector2.new(0.5, 0.5)
    Labelxd.Position = UDim2.new(0.5, 0, 0.8, 0)
    Labelxd.BorderSizePixel = 0
    Labelxd.Size = UDim2.new(0, 155, 0, 13)
    Labelxd.Font = Enum.Font.GothamSemibold
    Labelxd.Text = tostring(text)
    Labelxd.TextColor3 = Color3.fromRGB(255, 255, 255)
    Labelxd.TextSize = 12.000

    function  labelfuc:Change(text2)
        Labelxd.Text = tostring(text2)
    end
    return  labelfuc
end

    return ems 
end
    return page
end
    return tap
end
--return create
--
game.StarterGui:SetCore("SendNotification", {
    Icon = "rbxassetid://7996551096";
    Title = "NOOB HUB", 
    Text = "Sucessful"
 })
 wait(1)
local win = create:Win()
local Tab = win:addtap("Main")
local Main = Tab:addpage("Main")
Main:Ti("MAP")
Main:Label("Made BY : 03s.#4358")
Main:Label("Discord : NOOB HUB")
Main:Button("Copy Discord",function()
setclipboard("https://discord.gg/J6gQRVk48n")
game.StarterGui:SetCore("SendNotification", {
    Icon = "rbxassetid://7996551096";
    Title = "NOOBHUB : Discord", 
    Text = "Copy"
 })
 wait(.1)
end)
Main:Label("Youtube : NOOB HUB")
Main:Button("Copy Youtube",function()
   setclipboard("https://www.youtube.com/channel/UCpbG2pkTiPODfMOq_voRQDg/videos") 
game.StarterGui:SetCore("SendNotification", {
    Icon = "rbxassetid://7996551096";
    Title = "NOOBHUB : YouTube", 
    Text = "Copy"
 })
 wait(.1)
end)
local Main2 = Tab:addpage("")
Main2:Ti("Update")
Main2:Label("[+] Auto Farm")
Main2:Label("[+] Auto Jump [เอาไวกันนึ่งโตะ]")
Main2:Label("[+] Teleport")
local Tab2 = win:addtap("AutoFarm")
local AutoFarm = Tab2:addpage()
AutoFarm:Ti("AutoFarm")
function TPx(P)
    Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 1000 then
       Speed = 50
    end
    game:GetService("TweenService"):Create(
    game.Players.LocalPlayer.Character.HumanoidRootPart,
    TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
    {CFrame = P}
    ):Play()
 end
AutoFarm:Toggle("AutoFarm",false,function(s)
  _G.AutoFarmMoney = s
while _G.AutoFarmMoney do wait()
  pcall(function()
for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
if v.ClassName == "ProximityPrompt" then
          TPx(v.Parent.CFrame) 
wait(1)
fireproximityprompt(v, 20)
end
end
end)
end
end)
AutoFarm:Button("Bypass - KICK",function()
local Players = game:GetService("Players")
local OldNameCall = nil
OldNameCall = hookmetamethod(game, "__namecall", function(Self, ...)
    local NameCallMethod = getnamecallmethod()

    if tostring(string.lower(NameCallMethod)) == "kick" then
        return nil
    end
    
    return OldNameCall(Self, ...)
    end)
end)
AutoFarm:Toggle("AutoJump",false,function(s)
    _G.Jump = s
    while _G.Jump do wait()
        pcall(function()
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    end)

end
end)
AutoFarm:Toggle("OneHit",false,function(s)
_G.OneHit = s
while _G.OneHit do task.wait(.1)
pcall(function()
for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
    if v:IsA'Tool' then
        local Sadistic = require(game.Players.LocalPlayer.Character[v.Name].MainModule[1])
        Sadistic.AttackDelay = 0.1
        Sadistic["BaseDamage"][1] = 200
        Sadistic["BaseDamage"][2] = 1000
   end
end
end)
end
end)
AutoFarm:Ti("Misc")
if _G.FPSBoost then
    spawn(function()
        wait(3)
        local decalsyeeted = true -- Leaving this on makes games look shitty but the fps goes up by at least 20.
        local g = game
        local w = g.Workspace
        local l = g.Lighting
        local t = w.Terrain
        t.WaterWaveSize = 0
        t.WaterWaveSpeed = 0
        t.WaterReflectance = 0
        t.WaterTransparency = 0
        l.GlobalShadows = false
        l.FogEnd = 9e9
        l.Brightness = 0
        settings().Rendering.QualityLevel = "Level01"
        for i, v in pairs(g:GetDescendants()) do
            if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 
                v.Material = "Plastic"
                v.Reflectance = 0
            elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
                v.Transparency = 1
            elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
                v.Lifetime = NumberRange.new(0)
            elseif v:IsA("Explosion") then
                v.BlastPressure = 1
                v.BlastRadius = 1
            elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
                v.Enabled = false
            elseif v:IsA("MeshPart") then
                v.Material = "Plastic"
                v.Reflectance = 0
                v.TextureID = 10385902758728957
            end
        end
        for i, e in pairs(l:GetChildren()) do
            if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
                e.Enabled = false
            end
        end
    end)
 end
 AutoFarm:Button("FPS Boost",function(t)
    local decalsyeeted = true -- Leaving this on makes games look shitty but the fps goes up by at least 20.
    local g = game
    local w = g.Workspace
    local l = g.Lighting
    local t = w.Terrain
    t.WaterWaveSize = 0
    t.WaterWaveSpeed = 0
    t.WaterReflectance = 0
    t.WaterTransparency = 0
    l.GlobalShadows = false
    l.FogEnd = 9e9
    l.Brightness = 0
    settings().Rendering.QualityLevel = "Level01"
    for i, v in pairs(g:GetDescendants()) do
        if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 
            v.Material = "Plastic"
            v.Reflectance = 0
        elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
            v.Transparency = 1
        elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
            v.Lifetime = NumberRange.new(0)
        elseif v:IsA("Explosion") then
            v.BlastPressure = 1
            v.BlastRadius = 1
        elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
            v.Enabled = false
        elseif v:IsA("MeshPart") then
            v.Material = "Plastic"
            v.Reflectance = 0
            v.TextureID = 10385902758728957
        end
    end
    for i, e in pairs(l:GetChildren()) do
        if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
            e.Enabled = false
        end
    end
 end)
 
AutoFarm:Button("Anti-AFK", function()
    local vu = game:GetService("VirtualUser")
	game:GetService("Players").LocalPlayer.Idled:connect(function()
		vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		wait(1)
		vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
end)
 AutoFarm:Button("Rejoin", function()
 local ts = game:GetService("TeleportService")
	local p = game:GetService("Players").LocalPlayer
	ts:Teleport(game.PlaceId, p)
end)
AutoFarm:Button("Server Hop", function()
        local PlaceID = game.PlaceId
    local AllIDs = {}
    local foundAnything = ""
    local actualHour = os.date("!*t").hour
    local Deleted = false
    --[[
    local File = pcall(function()
        AllIDs = game:GetService('HttpService'):JSONDecode(readfile("NotSameServers.json"))
    end)
    if not File then
        table.insert(AllIDs, actualHour)
        writefile("NotSameServers.json", game:GetService('HttpService'):JSONEncode(AllIDs))
    end
    ]]
    function TPReturner()
        local Site;
        if foundAnything == "" then
            Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100'))
        else
            Site = game.HttpService:JSONDecode(game:HttpGet('https://games.roblox.com/v1/games/' .. PlaceID .. '/servers/Public?sortOrder=Asc&limit=100&cursor=' .. foundAnything))
        end
        local ID = ""
        if Site.nextPageCursor and Site.nextPageCursor ~= "null" and Site.nextPageCursor ~= nil then
            foundAnything = Site.nextPageCursor
        end
        local num = 0;
        for i,v in pairs(Site.data) do
            local Possible = true
            ID = tostring(v.id)
            if tonumber(v.maxPlayers) > tonumber(v.playing) then
                for _,Existing in pairs(AllIDs) do
                    if num ~= 0 then
                        if ID == tostring(Existing) then
                            Possible = false
                        end
                    else
                        if tonumber(actualHour) ~= tonumber(Existing) then
                            local delFile = pcall(function()
                                -- delfile("NotSameServers.json")
                                AllIDs = {}
                                table.insert(AllIDs, actualHour)
                            end)
                        end
                    end
                    num = num + 1
                end
                if Possible == true then
                    table.insert(AllIDs, ID)
                    wait()
                    pcall(function()
                        -- writefile("NotSameServers.json", game:GetService('HttpService'):JSONEncode(AllIDs))
                        wait()
                        game:GetService("TeleportService"):TeleportToPlaceInstance(PlaceID, ID, game.Players.LocalPlayer)
                    end)
                    wait(4)
                end
            end
        end
    end

    function Teleport()
        while wait() do
            pcall(function()
                TPReturner()
                if foundAnything ~= "" then
                    TPReturner()
                end
            end)
        end
    end

    Teleport()
end)
AutoFarm:Button("Server Hop Less",function()
local maxplayers, gamelink, goodserver, data_table = math.huge, "https://games.roblox.com/v1/games/" .. game.PlaceId .. "/servers/Public?sortOrder=Asc&limit=100"
    if not _G.FailedServerID then _G.FailedServerID = {} end

    local function serversearch()
        data_table = game:GetService"HttpService":JSONDecode(game:HttpGetAsync(gamelink))
        for _, v in pairs(data_table.data) do
            pcall(function()
                if type(v) == "table" and v.id and v.playing and tonumber(maxplayers) > tonumber(v.playing) and not table.find(_G.FailedServerID, v.id) then
                    maxplayers = v.playing
                    goodserver = v.id
                end
            end)
        end
    end

    function getservers()
        pcall(serversearch)
        for i, v in pairs(data_table) do
            if i == "nextPageCursor" then
                if gamelink:find"&cursor=" then
                    local a = gamelink:find"&cursor="
                    local b = gamelink:sub(a)
                    gamelink = gamelink:gsub(b, "")
                end
                gamelink = gamelink .. "&cursor=" .. v
                pcall(getservers)
            end
        end
    end

    pcall(getservers)
    wait()
    if goodserver == game.JobId or maxplayers == #game:GetService"Players":GetChildren() - 1 then
    end
    table.insert(_G.FailedServerID, goodserver)
    game:GetService"TeleportService":TeleportToPlaceInstance(game.PlaceId, goodserver)
end)
local AutoFarm2 = Tab2:addpage()

 ply = {}
 for i,v in pairs(game.Players:GetPlayers()) do
    table.insert(ply,v.Name)
 end
 local Dropdown = AutoFarm2:DropDown("Select Players","Select Players",ply,function(Value)
     Noobply = Value
 end)
 AutoFarm2:Button("Refresh Players",function()
     Dropdown:Clear()
 for i,v in pairs(game.Players:GetPlayers()) do
             Dropdown:Add(v.Name)
         end
 end)
  AutoFarm2:Toggle("Spectate",false, function(k)
_G.sep = k 
while _G.sep do wait()
 for i,v in pairs(game.Players:GetPlayers()) do
if v.Name == Noobply then
game.Workspace.Camera.CameraSubject = v.Character.Humanoid
end
end
end
game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
end)
 AutoFarm2:Button("Teleport", function()
 game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[Noobply].Character.HumanoidRootPart.CFrame
 end)
  AutoFarm2:Slder("WalkSpeed",1,100,16,function(s)
      SPEED = s
      end)
 AutoFarm2:Toggle("WalkSpeed",false,function(s)
    _G.Walk = s 
    while _G.Walk do wait()
        pcall(function()
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = SPEED
        end)
        end
end)
   AutoFarm2:Ti("ESP", true)
    function isnil(thing)
        return (thing == nil)
    end
    local function round(n)
        return math.floor(tonumber(n) + 0.5)
    end
    Number = math.random(1, 1000000)
    function UpdatePlayerChams()
        for i,v in pairs(game:GetService'Players':GetChildren()) do
            pcall(function()
                if not isnil(v.Character) then
                    if ESPPlayer then
                        if not isnil(v.Character.Head) and not v.Character.Head:FindFirstChild('NameEsp'..Number) then
                            local bill = Instance.new('BillboardGui',v.Character.Head)
                            bill.Name = 'NameEsp'..Number
                            bill.ExtentsOffset = Vector3.new(0, 1, 0)
                            bill.Size = UDim2.new(1,200,1,30)
                            bill.Adornee = v.Character.Head
                            bill.AlwaysOnTop = true
                            local name = Instance.new('TextLabel',bill)
                            name.Font = "GothamBold"
                            name.FontSize = "Size14"
                            name.TextWrapped = true
                            name.Text = (v.Name ..' \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M')
                            name.Size = UDim2.new(1,0,1,0)
                            name.TextYAlignment = 'Top'
                            name.BackgroundTransparency = 1
                            name.TextStrokeTransparency = 0.5
                            if v.Team == game.Players.LocalPlayer.Team then
                                name.TextColor3 = Color3.new(255, 255 ,255)
                            else
                                name.TextColor3 = Color3.new(255, 255 ,255)
                            end
                        else
                            v.Character.Head['NameEsp'..Number].TextLabel.Text = (v.Name ..'   \n'.. round((game:GetService('Players').LocalPlayer.Character.Head.Position - v.Character.Head.Position).Magnitude/3) ..' M')
                        end
                    else
                        if v.Character.Head:FindFirstChild('NameEsp'..Number) then
                            v.Character.Head:FindFirstChild('NameEsp'..Number):Destroy()
                        end
                    end
                end
            end)
        end
    end
 AutoFarm2:Toggle("ESP Player",false,function(a)
        ESPPlayer = a
        while ESPPlayer do wait()
            UpdatePlayerChams()
        end
 end)
 AutoFarm2:Button("HITBOX",function(s)
_G.HeadSize = 20
_G.Disabled = true
game:GetService('RunService').RenderStepped:connect(function()
if _G.Disabled then
for i,v in next, game:GetService('Players'):GetPlayers() do
if v.Name ~= game:GetService('Players').LocalPlayer.Name then
pcall(function()
v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
v.Character.HumanoidRootPart.Transparency = 0.7
v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really blue")
v.Character.HumanoidRootPart.Material = "Neon"
v.Character.HumanoidRootPart.CanCollide = false
end)
end
end
end
end)
end)
 AutoFarm2:Button("GODMODE",function()
loadstring(game:HttpGet("https://ghostbin.com/oWFK8/raw"))()
end)


local Tab1 = win:addtap("Teleport")
local Teleport = Tab1:addpage()
Teleport:Ti("อาวุธ")
Teleport:Button("MP5",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-342.93496704102, 1.4459328651428, -1615.4986572266)
end)
Teleport:Button("MP7",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-995.46301269531, 1.5819385051727, -599.30999755859)
end)
Teleport:Button("Hammer",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-700.57238769531, 1.5819385051727, -1074.9827880859)
end)
Teleport:Button("AK",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-583.59136962891, -11.21106338501, -678.99835205078)
end)
Teleport:Button("Colt Model 1911",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-29.980398178101, 2.011726140976, -1026.9556884766)
end)
Teleport:Button("ระเบิด",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-26.815824508667, 1.7373676300049, -797.74176025391)
end)
Teleport:Button("Aex",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-604.58294677734, 1.4159443378448, -1353.2296142578)
end)
Teleport:Button("Medkit",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1199.7928466797, 1.5819388628006, -709.15252685547)
end)
Teleport:Ti("สถานที่")
Teleport:Button("Cafe 1",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-900.84906005859, 3.3840942382812, -1350.2060546875)
end)
Teleport:Button("Cafe 2",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-304.4880065918, 3.4941623210907, -1356.4539794922)
end)
Teleport:Button("Cafe 3",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-74.688331604004, 4.0352401733398, -756.59722900391)
end)

Teleport:Button("วัด",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(305.87643432617, 1.374449133873, -1198.0916748047)
end)
local Teleport2 = Tab1:addpage()
Teleport2:Ti("สถาบรรณ")
Teleport2:Button("ประชาชื่อเทคโน",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1330.1351318359, 1.3697783946991, -1254.9200439453)
end)
Teleport2:Button("บุรณพนธ์ช่างกล",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1363.7469482422, 1.3697783946991, -782.14318847656)
end)
Teleport2:Button("โรงเรียนอินทรอาชีวศึกษา",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(187.73651123047, 1.3697783946991, -360.82940673828)
end)
Teleport2:Button("โรงเรียนกนกอาชีวศึกษา",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1021.1380004883, 1.3697783946991, -352.18399047852)
end)
else
    game.Players.LocalPlayer:Kick('Hwid Not Found')
 end
 else
    game.Players.LocalPlayer:Kick('Wrong Key')
 end
 else
    game.Players.LocalPlayer:Kick('Not Found Hwid Loaded')
 end
 else
    game.Players.LocalPlayer:Kick('Wrong License [ Set Clipboard]')
 end
