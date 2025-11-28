--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 120 | Scripts: 7 | Modules: 2 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.Mobile
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["2"]["Size"] = UDim2.new(0, 577, 0, 319);
G2L["2"]["Position"] = UDim2.new(0.14804, 0, 0.11752, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Mobile]];


-- StarterGui.ScreenGui.Mobile.LocalScript
G2L["3"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Mobile.Top
G2L["4"] = Instance.new("Frame", G2L["2"]);
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(22, 22, 22);
G2L["4"]["Size"] = UDim2.new(0, 577, 0, 35);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Name"] = [[Top]];


-- StarterGui.ScreenGui.Mobile.Top.KRNL
G2L["5"] = Instance.new("ImageLabel", G2L["4"]);
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5"]["Image"] = [[rbxassetid://125999447519604]];
G2L["5"]["Size"] = UDim2.new(0, 37, 0, 37);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["BackgroundTransparency"] = 1;
G2L["5"]["Name"] = [[KRNL]];


-- StarterGui.ScreenGui.Mobile.Top.KRNL.UIAspectRatioConstraint
G2L["6"] = Instance.new("UIAspectRatioConstraint", G2L["5"]);



-- StarterGui.ScreenGui.Mobile.Top.TextLabel
G2L["7"] = Instance.new("TextLabel", G2L["4"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["TextSize"] = 17;
G2L["7"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Size"] = UDim2.new(0, 120, 0, 36);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Text"] = [[KRNL Executor]];
G2L["7"]["Position"] = UDim2.new(0.06523, 0, 0.0203, 0);


-- StarterGui.ScreenGui.Mobile.Main
G2L["8"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["8"]["Active"] = true;
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["CanvasSize"] = UDim2.new(0, 0, 4, 0);
G2L["8"]["TopImage"] = [[]];
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(35, 35, 35);
G2L["8"]["Name"] = [[Main]];
G2L["8"]["BottomImage"] = [[]];
G2L["8"]["Size"] = UDim2.new(0, 428, 0, 215);
G2L["8"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Position"] = UDim2.new(0.03459, 0, 0.14197, 0);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.ScreenGui.Mobile.Main.Code
G2L["9"] = Instance.new("TextBox", G2L["8"]);
G2L["9"]["Name"] = [[Code]];
G2L["9"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["TextWrapped"] = true;
G2L["9"]["TextSize"] = 19;
G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9"]["MultiLine"] = true;
G2L["9"]["ClearTextOnFocus"] = false;
G2L["9"]["PlaceholderText"] = [[print("HELLO KRNL")]];
G2L["9"]["Size"] = UDim2.new(0, 585, 0, 1795);
G2L["9"]["Position"] = UDim2.new(0, 0, -5.30175, 0);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Text"] = [[]];
G2L["9"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Mobile.Main.UIListLayout
G2L["a"] = Instance.new("UIListLayout", G2L["8"]);
G2L["a"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Mobile.btn
G2L["b"] = Instance.new("Frame", G2L["2"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["Size"] = UDim2.new(0, 428, 0, 41);
G2L["b"]["Position"] = UDim2.new(0.03459, 0, 0.83964, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[btn]];
G2L["b"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Mobile.btn.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["b"]);



-- StarterGui.ScreenGui.Mobile.btn.LocalScript.API
G2L["d"] = Instance.new("ModuleScript", G2L["c"]);
G2L["d"]["Name"] = [[API]];


-- StarterGui.ScreenGui.Mobile.btn.UIListLayout
G2L["e"] = Instance.new("UIListLayout", G2L["b"]);
G2L["e"]["Padding"] = UDim.new(0, 9);
G2L["e"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["e"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["e"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.Mobile.btn.Exe
G2L["f"] = Instance.new("TextButton", G2L["b"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 22;
G2L["f"]["TextColor3"] = Color3.fromRGB(181, 181, 181);
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(55, 55, 55);
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f"]["Size"] = UDim2.new(0, 137, 0, 31);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[Execute]];
G2L["f"]["Name"] = [[Exe]];
G2L["f"]["Position"] = UDim2.new(-0, 0, 0.1213, 0);


-- StarterGui.ScreenGui.Mobile.btn.Exe.ImageLabel
G2L["10"] = Instance.new("ImageLabel", G2L["f"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["10"]["Image"] = [[rbxassetid://94640768832047]];
G2L["10"]["Size"] = UDim2.new(0, 17, 0, 17);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Position"] = UDim2.new(0.80793, 0, 0.23565, 0);


-- StarterGui.ScreenGui.Mobile.btn.Exe.ImageLabel.UIAspectRatioConstraint
G2L["11"] = Instance.new("UIAspectRatioConstraint", G2L["10"]);



-- StarterGui.ScreenGui.Mobile.btn.Inj
G2L["12"] = Instance.new("TextButton", G2L["b"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 22;
G2L["12"]["TextColor3"] = Color3.fromRGB(181, 181, 181);
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(55, 55, 55);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["Size"] = UDim2.new(0, 137, 0, 31);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[Inject]];
G2L["12"]["Name"] = [[Inj]];
G2L["12"]["Position"] = UDim2.new(0.67915, 0, 0.1213, 0);


-- StarterGui.ScreenGui.Mobile.btn.Inj.ImageLabel
G2L["13"] = Instance.new("ImageLabel", G2L["12"]);
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["13"]["Image"] = [[rbxassetid://110159304114119]];
G2L["13"]["Size"] = UDim2.new(0, 17, 0, 17);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["BackgroundTransparency"] = 1;
G2L["13"]["Position"] = UDim2.new(0.75944, 0, 0.23565, 0);


-- StarterGui.ScreenGui.Mobile.btn.Inj.ImageLabel.UIAspectRatioConstraint
G2L["14"] = Instance.new("UIAspectRatioConstraint", G2L["13"]);



-- StarterGui.ScreenGui.Mobile.btn.Clr
G2L["15"] = Instance.new("TextButton", G2L["b"]);
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextSize"] = 22;
G2L["15"]["TextColor3"] = Color3.fromRGB(181, 181, 181);
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(55, 55, 55);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["Size"] = UDim2.new(0, 137, 0, 31);
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Text"] = [[Clear]];
G2L["15"]["Name"] = [[Clr]];
G2L["15"]["Position"] = UDim2.new(0.33958, 0, 0.1213, 0);


-- StarterGui.ScreenGui.Mobile.btn.Clr.ImageLabel
G2L["16"] = Instance.new("ImageLabel", G2L["15"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["16"]["Image"] = [[rbxassetid://132971593063501]];
G2L["16"]["Size"] = UDim2.new(0, 17, 0, 17);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["BackgroundTransparency"] = 1;
G2L["16"]["Position"] = UDim2.new(0.78369, 0, 0.23565, 0);


-- StarterGui.ScreenGui.Mobile.btn.Clr.ImageLabel.UIAspectRatioConstraint
G2L["17"] = Instance.new("UIAspectRatioConstraint", G2L["16"]);



-- StarterGui.ScreenGui.Mobile.ScrollingFrame
G2L["18"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["18"]["Active"] = true;
G2L["18"]["ZIndex"] = 2;
G2L["18"]["BorderSizePixel"] = 0;
G2L["18"]["CanvasSize"] = UDim2.new(0, 0, 10, 0);
G2L["18"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["18"]["Size"] = UDim2.new(0, 113, 0, 234);
G2L["18"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["Position"] = UDim2.new(0.78693, 0, 0.21769, 0);
G2L["18"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["18"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.UICorner
G2L["19"] = Instance.new("UICorner", G2L["18"]);
G2L["19"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.UIGridLayout
G2L["1a"] = Instance.new("UIGridLayout", G2L["18"]);
G2L["1a"]["CellSize"] = UDim2.new(0, 100, 0, 200);
G2L["1a"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["1a"]["CellPadding"] = UDim2.new(0, 5, 0, 10);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example
G2L["1b"] = Instance.new("Frame", G2L["18"]);
G2L["1b"]["ZIndex"] = 2;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(91, 91, 91);
G2L["1b"]["Size"] = UDim2.new(0, 136, 0, 200);
G2L["1b"]["Position"] = UDim2.new(0, 0, 0, 0);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Name"] = [[Example]];
G2L["1b"]["BackgroundTransparency"] = 0.45;


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.TextLabel
G2L["1c"] = Instance.new("TextLabel", G2L["1b"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["ZIndex"] = 2;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextSize"] = 56;
G2L["1c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(-1.27931, 210, 0.0125, 30);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Example name]];
G2L["1c"]["Position"] = UDim2.new(0.06758, 0, 0.24121, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.TextButton
G2L["1d"] = Instance.new("TextButton", G2L["1b"]);
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["1d"]["ZIndex"] = 2;
G2L["1d"]["Size"] = UDim2.new(0.02, 51, 0.01265, 14);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[Run]];
G2L["1d"]["Position"] = UDim2.new(0.42444, 0, 0.14856, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Copy
G2L["1e"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["1e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1e"]["Image"] = [[rbxassetid://86138545569367]];
G2L["1e"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["BackgroundTransparency"] = 1;
G2L["1e"]["Name"] = [[Copy]];
G2L["1e"]["Position"] = UDim2.new(0.07702, 0, 0.80121, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Copy.UIAspectRatioConstraint
G2L["1f"] = Instance.new("UIAspectRatioConstraint", G2L["1e"]);



-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Copy.TextLabel
G2L["20"] = Instance.new("TextLabel", G2L["1e"]);
G2L["20"]["TextWrapped"] = true;
G2L["20"]["ZIndex"] = 2;
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["TextSize"] = 20;
G2L["20"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["20"]["TextScaled"] = true;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["20"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["20"]["BackgroundTransparency"] = 1;
G2L["20"]["Size"] = UDim2.new(-8.21033, 210, -0.53833, 30);
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Text"] = [[ClickToCopy]];
G2L["20"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Copy.TextButton
G2L["21"] = Instance.new("TextButton", G2L["1e"]);
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextTransparency"] = 1;
G2L["21"]["TextSize"] = 14;
G2L["21"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["21"]["BackgroundTransparency"] = 1;
G2L["21"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.COntainsKEy
G2L["22"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["22"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["22"]["Image"] = [[rbxassetid://81864026272064]];
G2L["22"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["BackgroundTransparency"] = 1;
G2L["22"]["Name"] = [[COntainsKEy]];
G2L["22"]["Position"] = UDim2.new(0.07297, 0, 0.91121, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.COntainsKEy.UIAspectRatioConstraint
G2L["23"] = Instance.new("UIAspectRatioConstraint", G2L["22"]);



-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.COntainsKEy.TextLabel
G2L["24"] = Instance.new("TextLabel", G2L["22"]);
G2L["24"]["TextWrapped"] = true;
G2L["24"]["ZIndex"] = 2;
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["TextSize"] = 20;
G2L["24"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["24"]["TextScaled"] = true;
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["24"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["24"]["BackgroundTransparency"] = 1;
G2L["24"]["Size"] = UDim2.new(-8.1865, 210, -0.53833, 30);
G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["Text"] = [[ClickToCopy]];
G2L["24"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.COntainsKEy.TextButton
G2L["25"] = Instance.new("TextButton", G2L["22"]);
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextTransparency"] = 1;
G2L["25"]["TextSize"] = 14;
G2L["25"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["25"]["BackgroundTransparency"] = 1;
G2L["25"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Count
G2L["26"] = Instance.new("TextLabel", G2L["1b"]);
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["TextSize"] = 28;
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["26"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["BackgroundTransparency"] = 1;
G2L["26"]["Size"] = UDim2.new(0, 26, 0, 38);
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Text"] = [[1]];
G2L["26"]["Name"] = [[Count]];
G2L["26"]["Position"] = UDim2.new(-0.011, 0, 0, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Logo
G2L["27"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["27"]["ZIndex"] = 2;
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["27"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["27"]["Image"] = [[rbxassetid://104649966280536]];
G2L["27"]["Size"] = UDim2.new(0, 23, 0, 42);
G2L["27"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["BackgroundTransparency"] = 1;
G2L["27"]["Name"] = [[Logo]];
G2L["27"]["Position"] = UDim2.new(0.87635, 0, 0.08106, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Logo.UICorner
G2L["28"] = Instance.new("UICorner", G2L["27"]);
G2L["28"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Logo.UIAspectRatioConstraint
G2L["29"] = Instance.new("UIAspectRatioConstraint", G2L["27"]);



-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.View
G2L["2a"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["2a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2a"]["Image"] = [[rbxassetid://104741126012073]];
G2L["2a"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["BackgroundTransparency"] = 1;
G2L["2a"]["Name"] = [[View]];
G2L["2a"]["Position"] = UDim2.new(0.08764, 0, 0.45621, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.View.UIAspectRatioConstraint
G2L["2b"] = Instance.new("UIAspectRatioConstraint", G2L["2a"]);



-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.View.TextLabel
G2L["2c"] = Instance.new("TextLabel", G2L["2a"]);
G2L["2c"]["TextWrapped"] = true;
G2L["2c"]["ZIndex"] = 2;
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["TextSize"] = 20;
G2L["2c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2c"]["TextScaled"] = true;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["2c"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["2c"]["BackgroundTransparency"] = 1;
G2L["2c"]["Size"] = UDim2.new(-8.70037, 210, -0.53833, 30);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Text"] = [[1million]];
G2L["2c"]["Position"] = UDim2.new(1.19593, 0, 0.19219, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Verify
G2L["2d"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["2d"]["BorderSizePixel"] = 0;
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["2d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2d"]["Image"] = [[rbxassetid://106324515607448]];
G2L["2d"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["BackgroundTransparency"] = 1;
G2L["2d"]["Name"] = [[Verify]];
G2L["2d"]["Position"] = UDim2.new(0.07838, 0, 0.56348, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Verify.UIAspectRatioConstraint
G2L["2e"] = Instance.new("UIAspectRatioConstraint", G2L["2d"]);



-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Verify.TextLabel
G2L["2f"] = Instance.new("TextLabel", G2L["2d"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["ZIndex"] = 2;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextSize"] = 20;
G2L["2f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["2f"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["2f"]["BackgroundTransparency"] = 1;
G2L["2f"]["Size"] = UDim2.new(-8.30942, 210, -0.53833, 30);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[ClickToCopy]];
G2L["2f"]["Position"] = UDim2.new(1.2205, 0, 0.19219, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Verify.TextButton
G2L["30"] = Instance.new("TextButton", G2L["2d"]);
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["TextTransparency"] = 1;
G2L["30"]["TextSize"] = 14;
G2L["30"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["30"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["30"]["BackgroundTransparency"] = 1;
G2L["30"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["30"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Place
G2L["31"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["31"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["31"]["Image"] = [[rbxassetid://76183981184625]];
G2L["31"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["BackgroundTransparency"] = 1;
G2L["31"]["Name"] = [[Place]];
G2L["31"]["Position"] = UDim2.new(0.07772, 0, 0.68359, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Place.UIAspectRatioConstraint
G2L["32"] = Instance.new("UIAspectRatioConstraint", G2L["31"]);



-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Place.TextLabel
G2L["33"] = Instance.new("TextLabel", G2L["31"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["ZIndex"] = 2;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextSize"] = 20;
G2L["33"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["33"]["TextScaled"] = true;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["33"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["33"]["BackgroundTransparency"] = 1;
G2L["33"]["Size"] = UDim2.new(-7.91802, 210, -0.53833, 30);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[ClickToCopy]];
G2L["33"]["Position"] = UDim2.new(1.22225, 0, 0.19219, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.Place.TextButton
G2L["34"] = Instance.new("TextButton", G2L["31"]);
G2L["34"]["BorderSizePixel"] = 0;
G2L["34"]["TextTransparency"] = 1;
G2L["34"]["TextSize"] = 14;
G2L["34"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["34"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["34"]["BackgroundTransparency"] = 1;
G2L["34"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["34"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.ImageLabel
G2L["35"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["35"]["ZIndex"] = 2;
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
G2L["35"]["ImageTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["35"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["35"]["Image"] = [[rbxassetid://104649966280536]];
G2L["35"]["Size"] = UDim2.new(0, 23, 0, 42);
G2L["35"]["Visible"] = false;
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["BackgroundTransparency"] = 1;
G2L["35"]["Position"] = UDim2.new(0.68635, 0, 0.08106, 0);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.ImageLabel.UICorner
G2L["36"] = Instance.new("UICorner", G2L["35"]);
G2L["36"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.Mobile.ScrollingFrame.Example.ImageLabel.UIAspectRatioConstraint
G2L["37"] = Instance.new("UIAspectRatioConstraint", G2L["35"]);



-- StarterGui.ScreenGui.Mobile.TextBox
G2L["38"] = Instance.new("TextBox", G2L["2"]);
G2L["38"]["ZIndex"] = 2;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(19, 19, 19);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["38"]["PlaceholderText"] = [[search your script]];
G2L["38"]["Size"] = UDim2.new(0, 97, 0, 19);
G2L["38"]["Position"] = UDim2.new(0.78426, 0, 0.14031, 0);
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Text"] = [[]];
G2L["38"]["BackgroundTransparency"] = 0.55;


-- StarterGui.ScreenGui.Mobile.ImageButton
G2L["39"] = Instance.new("ImageButton", G2L["2"]);
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["39"]["ImageColor3"] = Color3.fromRGB(71, 71, 71);
G2L["39"]["ZIndex"] = 2;
G2L["39"]["Image"] = [[rbxassetid://15985408996]];
G2L["39"]["Size"] = UDim2.new(0.03, 14, 0.02, 14);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["Rotation"] = 135;
G2L["39"]["Position"] = UDim2.new(0.9493, 0, 0.13421, 0);


-- StarterGui.ScreenGui.Mobile.ImageButton.UIAspectRatioConstraint
G2L["3a"] = Instance.new("UIAspectRatioConstraint", G2L["39"]);



-- StarterGui.ScreenGui.Mobile.UIDrag
G2L["3b"] = Instance.new("LocalScript", G2L["2"]);
G2L["3b"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.PC
G2L["3c"] = Instance.new("Frame", G2L["1"]);
G2L["3c"]["Visible"] = false;
G2L["3c"]["BorderSizePixel"] = 0;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["3c"]["Size"] = UDim2.new(0, 808, 0, 449);
G2L["3c"]["Position"] = UDim2.new(0.14804, 0, 0.11752, 0);
G2L["3c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["Name"] = [[PC]];


-- StarterGui.ScreenGui.PC.LocalScript
G2L["3d"] = Instance.new("LocalScript", G2L["3c"]);



-- StarterGui.ScreenGui.PC.Main
G2L["3e"] = Instance.new("ScrollingFrame", G2L["3c"]);
G2L["3e"]["Active"] = true;
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["CanvasSize"] = UDim2.new(0, 0, 4, 0);
G2L["3e"]["TopImage"] = [[]];
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(35, 35, 35);
G2L["3e"]["Name"] = [[Main]];
G2L["3e"]["BottomImage"] = [[]];
G2L["3e"]["Size"] = UDim2.new(0, 600, 0, 303);
G2L["3e"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Position"] = UDim2.new(0.03465, 0, 0.14197, 0);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.ScreenGui.PC.Main.Code
G2L["3f"] = Instance.new("TextBox", G2L["3e"]);
G2L["3f"]["Name"] = [[Code]];
G2L["3f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["TextSize"] = 19;
G2L["3f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["MultiLine"] = true;
G2L["3f"]["ClearTextOnFocus"] = false;
G2L["3f"]["PlaceholderText"] = [[print("HELLO KRNL")]];
G2L["3f"]["Size"] = UDim2.new(0, 585, 0, 1795);
G2L["3f"]["Position"] = UDim2.new(0, 0, -5.30175, 0);
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[]];
G2L["3f"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.PC.Main.UIListLayout
G2L["40"] = Instance.new("UIListLayout", G2L["3e"]);
G2L["40"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.PC.Page
G2L["41"] = Instance.new("Frame", G2L["3c"]);
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["Size"] = UDim2.new(0, 600, 0, 20);
G2L["41"]["Position"] = UDim2.new(0.03465, 0, 0.13586, 0);
G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["41"]["Name"] = [[Page]];
G2L["41"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.PC.Page.UIListLayout
G2L["42"] = Instance.new("UIListLayout", G2L["41"]);
G2L["42"]["Padding"] = UDim.new(0, 1);
G2L["42"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["42"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["42"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.PC.btn
G2L["43"] = Instance.new("Frame", G2L["3c"]);
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["43"]["Size"] = UDim2.new(0, 600, 0, 58);
G2L["43"]["Position"] = UDim2.new(0.03465, 0, 0.83964, 0);
G2L["43"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["43"]["Name"] = [[btn]];
G2L["43"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.PC.btn.LocalScript
G2L["44"] = Instance.new("LocalScript", G2L["43"]);



-- StarterGui.ScreenGui.PC.btn.LocalScript.API
G2L["45"] = Instance.new("ModuleScript", G2L["44"]);
G2L["45"]["Name"] = [[API]];


-- StarterGui.ScreenGui.PC.btn.UIListLayout
G2L["46"] = Instance.new("UIListLayout", G2L["43"]);
G2L["46"]["Padding"] = UDim.new(0, 12);
G2L["46"]["VerticalAlignment"] = Enum.VerticalAlignment.Center;
G2L["46"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["46"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.ScreenGui.PC.btn.Exe
G2L["47"] = Instance.new("TextButton", G2L["43"]);
G2L["47"]["BorderSizePixel"] = 0;
G2L["47"]["TextSize"] = 22;
G2L["47"]["TextColor3"] = Color3.fromRGB(181, 181, 181);
G2L["47"]["BackgroundColor3"] = Color3.fromRGB(55, 55, 55);
G2L["47"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["47"]["Size"] = UDim2.new(0, 192, 0, 44);
G2L["47"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["47"]["Text"] = [[Execute]];
G2L["47"]["Name"] = [[Exe]];
G2L["47"]["Position"] = UDim2.new(0, 0, 0.07759, 0);


-- StarterGui.ScreenGui.PC.btn.Exe.ImageLabel
G2L["48"] = Instance.new("ImageLabel", G2L["47"]);
G2L["48"]["BorderSizePixel"] = 0;
G2L["48"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["48"]["Image"] = [[rbxassetid://94640768832047]];
G2L["48"]["Size"] = UDim2.new(0, 25, 0, 44);
G2L["48"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["48"]["BackgroundTransparency"] = 1;
G2L["48"]["Position"] = UDim2.new(0.80729, 0, 0.23455, 0);


-- StarterGui.ScreenGui.PC.btn.Exe.ImageLabel.UIAspectRatioConstraint
G2L["49"] = Instance.new("UIAspectRatioConstraint", G2L["48"]);



-- StarterGui.ScreenGui.PC.btn.Clr
G2L["4a"] = Instance.new("TextButton", G2L["43"]);
G2L["4a"]["BorderSizePixel"] = 0;
G2L["4a"]["TextSize"] = 22;
G2L["4a"]["TextColor3"] = Color3.fromRGB(181, 181, 181);
G2L["4a"]["BackgroundColor3"] = Color3.fromRGB(55, 55, 55);
G2L["4a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4a"]["Size"] = UDim2.new(0, 192, 0, 44);
G2L["4a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4a"]["Text"] = [[Clear]];
G2L["4a"]["Name"] = [[Clr]];
G2L["4a"]["Position"] = UDim2.new(0.33997, 0, 0.07759, 0);


-- StarterGui.ScreenGui.PC.btn.Clr.ImageLabel
G2L["4b"] = Instance.new("ImageLabel", G2L["4a"]);
G2L["4b"]["BorderSizePixel"] = 0;
G2L["4b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["4b"]["Image"] = [[rbxassetid://132971593063501]];
G2L["4b"]["Size"] = UDim2.new(0, 25, 0, 44);
G2L["4b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4b"]["BackgroundTransparency"] = 1;
G2L["4b"]["Position"] = UDim2.new(0.80729, 0, 0.23455, 0);


-- StarterGui.ScreenGui.PC.btn.Clr.ImageLabel.UIAspectRatioConstraint
G2L["4c"] = Instance.new("UIAspectRatioConstraint", G2L["4b"]);



-- StarterGui.ScreenGui.PC.btn.Inj
G2L["4d"] = Instance.new("TextButton", G2L["43"]);
G2L["4d"]["BorderSizePixel"] = 0;
G2L["4d"]["TextSize"] = 22;
G2L["4d"]["TextColor3"] = Color3.fromRGB(181, 181, 181);
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(55, 55, 55);
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4d"]["Size"] = UDim2.new(0, 192, 0, 44);
G2L["4d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["Text"] = [[Inject]];
G2L["4d"]["Name"] = [[Inj]];
G2L["4d"]["Position"] = UDim2.new(0.67993, 0, 0.07759, 0);


-- StarterGui.ScreenGui.PC.btn.Inj.ImageLabel
G2L["4e"] = Instance.new("ImageLabel", G2L["4d"]);
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["4e"]["Image"] = [[rbxassetid://110159304114119]];
G2L["4e"]["Size"] = UDim2.new(0, 25, 0, 44);
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["BackgroundTransparency"] = 1;
G2L["4e"]["Position"] = UDim2.new(0.80729, 0, 0.23455, 0);


-- StarterGui.ScreenGui.PC.btn.Inj.ImageLabel.UIAspectRatioConstraint
G2L["4f"] = Instance.new("UIAspectRatioConstraint", G2L["4e"]);



-- StarterGui.ScreenGui.PC.ScrollingFrame
G2L["50"] = Instance.new("ScrollingFrame", G2L["3c"]);
G2L["50"]["Active"] = true;
G2L["50"]["ZIndex"] = 2;
G2L["50"]["BorderSizePixel"] = 0;
G2L["50"]["CanvasSize"] = UDim2.new(0, 0, 10, 0);
G2L["50"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["Size"] = UDim2.new(0, 159, 0, 330);
G2L["50"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["50"]["Position"] = UDim2.new(0.78829, 0, 0.21769, 0);
G2L["50"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["50"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.PC.ScrollingFrame.UICorner
G2L["51"] = Instance.new("UICorner", G2L["50"]);
G2L["51"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.PC.ScrollingFrame.UIGridLayout
G2L["52"] = Instance.new("UIGridLayout", G2L["50"]);
G2L["52"]["CellSize"] = UDim2.new(0, 190, 0, 200);
G2L["52"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["52"]["CellPadding"] = UDim2.new(0, 5, 0, 10);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example
G2L["53"] = Instance.new("Frame", G2L["50"]);
G2L["53"]["ZIndex"] = 2;
G2L["53"]["BorderSizePixel"] = 0;
G2L["53"]["BackgroundColor3"] = Color3.fromRGB(91, 91, 91);
G2L["53"]["Size"] = UDim2.new(0, 392, 0, 124);
G2L["53"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["53"]["Name"] = [[Example]];
G2L["53"]["BackgroundTransparency"] = 0.45;


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.TextLabel
G2L["54"] = Instance.new("TextLabel", G2L["53"]);
G2L["54"]["TextWrapped"] = true;
G2L["54"]["ZIndex"] = 2;
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["TextSize"] = 56;
G2L["54"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["54"]["TextScaled"] = true;
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["54"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["BackgroundTransparency"] = 1;
G2L["54"]["Size"] = UDim2.new(-0.41629, 210, 0.12521, 30);
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Text"] = [[Example name]];
G2L["54"]["Position"] = UDim2.new(0.06758, 0, 0.13972, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.TextButton
G2L["55"] = Instance.new("TextButton", G2L["53"]);
G2L["55"]["BorderSizePixel"] = 0;
G2L["55"]["TextSize"] = 14;
G2L["55"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["55"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["55"]["ZIndex"] = 2;
G2L["55"]["Size"] = UDim2.new(0.22, 51, 0.02, 14);
G2L["55"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["55"]["Text"] = [[Run]];
G2L["55"]["Position"] = UDim2.new(0.11444, 0, 0.03621, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Copy
G2L["56"] = Instance.new("ImageLabel", G2L["53"]);
G2L["56"]["BorderSizePixel"] = 0;
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["56"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["56"]["Image"] = [[rbxassetid://86138545569367]];
G2L["56"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["56"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["BackgroundTransparency"] = 1;
G2L["56"]["Name"] = [[Copy]];
G2L["56"]["Position"] = UDim2.new(0.07702, 0, 0.80121, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Copy.UIAspectRatioConstraint
G2L["57"] = Instance.new("UIAspectRatioConstraint", G2L["56"]);



-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Copy.TextLabel
G2L["58"] = Instance.new("TextLabel", G2L["56"]);
G2L["58"]["TextWrapped"] = true;
G2L["58"]["ZIndex"] = 2;
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["TextSize"] = 20;
G2L["58"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["58"]["TextScaled"] = true;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["58"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["58"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["58"]["BackgroundTransparency"] = 1;
G2L["58"]["Size"] = UDim2.new(-4.9395, 210, -0.53833, 30);
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Text"] = [[ClickToCopy]];
G2L["58"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Copy.TextButton
G2L["59"] = Instance.new("TextButton", G2L["56"]);
G2L["59"]["BorderSizePixel"] = 0;
G2L["59"]["TextTransparency"] = 1;
G2L["59"]["TextSize"] = 14;
G2L["59"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["59"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["59"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["59"]["BackgroundTransparency"] = 1;
G2L["59"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["59"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["59"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.COntainsKEy
G2L["5a"] = Instance.new("ImageLabel", G2L["53"]);
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5a"]["Image"] = [[rbxassetid://81864026272064]];
G2L["5a"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["BackgroundTransparency"] = 1;
G2L["5a"]["Name"] = [[COntainsKEy]];
G2L["5a"]["Position"] = UDim2.new(0.07297, 0, 0.91121, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.COntainsKEy.UIAspectRatioConstraint
G2L["5b"] = Instance.new("UIAspectRatioConstraint", G2L["5a"]);



-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.COntainsKEy.TextLabel
G2L["5c"] = Instance.new("TextLabel", G2L["5a"]);
G2L["5c"]["TextWrapped"] = true;
G2L["5c"]["ZIndex"] = 2;
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["TextSize"] = 20;
G2L["5c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5c"]["TextScaled"] = true;
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["5c"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["5c"]["BackgroundTransparency"] = 1;
G2L["5c"]["Size"] = UDim2.new(-4.75641, 210, -0.53833, 30);
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["Text"] = [[ClickToCopy]];
G2L["5c"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.COntainsKEy.TextButton
G2L["5d"] = Instance.new("TextButton", G2L["5a"]);
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["TextTransparency"] = 1;
G2L["5d"]["TextSize"] = 14;
G2L["5d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5d"]["BackgroundTransparency"] = 1;
G2L["5d"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["5d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Count
G2L["5e"] = Instance.new("TextLabel", G2L["53"]);
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextSize"] = 28;
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["5e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["BackgroundTransparency"] = 1;
G2L["5e"]["Size"] = UDim2.new(0, 26, 0, 38);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[1]];
G2L["5e"]["Name"] = [[Count]];
G2L["5e"]["Position"] = UDim2.new(-0.011, 0, 0, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Logo
G2L["5f"] = Instance.new("ImageLabel", G2L["53"]);
G2L["5f"]["ZIndex"] = 2;
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["5f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5f"]["Image"] = [[rbxassetid://104649966280536]];
G2L["5f"]["Size"] = UDim2.new(0, 23, 0, 42);
G2L["5f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["BackgroundTransparency"] = 1;
G2L["5f"]["Name"] = [[Logo]];
G2L["5f"]["Position"] = UDim2.new(0.68635, 0, 0.08106, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Logo.UICorner
G2L["60"] = Instance.new("UICorner", G2L["5f"]);
G2L["60"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Logo.UIAspectRatioConstraint
G2L["61"] = Instance.new("UIAspectRatioConstraint", G2L["5f"]);



-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.View
G2L["62"] = Instance.new("ImageLabel", G2L["53"]);
G2L["62"]["BorderSizePixel"] = 0;
G2L["62"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["62"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["62"]["Image"] = [[rbxassetid://104741126012073]];
G2L["62"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["62"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["BackgroundTransparency"] = 1;
G2L["62"]["Name"] = [[View]];
G2L["62"]["Position"] = UDim2.new(0.08764, 0, 0.45621, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.View.UIAspectRatioConstraint
G2L["63"] = Instance.new("UIAspectRatioConstraint", G2L["62"]);



-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.View.TextLabel
G2L["64"] = Instance.new("TextLabel", G2L["62"]);
G2L["64"]["TextWrapped"] = true;
G2L["64"]["ZIndex"] = 2;
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["TextSize"] = 20;
G2L["64"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["64"]["TextScaled"] = true;
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["64"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["64"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["64"]["BackgroundTransparency"] = 1;
G2L["64"]["Size"] = UDim2.new(-5.69334, 210, -0.53833, 30);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["Text"] = [[1million]];
G2L["64"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Verify
G2L["65"] = Instance.new("ImageLabel", G2L["53"]);
G2L["65"]["BorderSizePixel"] = 0;
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["65"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["65"]["Image"] = [[rbxassetid://106324515607448]];
G2L["65"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["65"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["BackgroundTransparency"] = 1;
G2L["65"]["Name"] = [[Verify]];
G2L["65"]["Position"] = UDim2.new(0.07838, 0, 0.56348, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Verify.UIAspectRatioConstraint
G2L["66"] = Instance.new("UIAspectRatioConstraint", G2L["65"]);



-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Verify.TextLabel
G2L["67"] = Instance.new("TextLabel", G2L["65"]);
G2L["67"]["TextWrapped"] = true;
G2L["67"]["ZIndex"] = 2;
G2L["67"]["BorderSizePixel"] = 0;
G2L["67"]["TextSize"] = 20;
G2L["67"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["67"]["TextScaled"] = true;
G2L["67"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["67"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["67"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["67"]["BackgroundTransparency"] = 1;
G2L["67"]["Size"] = UDim2.new(-4.98053, 210, -0.53833, 30);
G2L["67"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["67"]["Text"] = [[ClickToCopy]];
G2L["67"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Verify.TextButton
G2L["68"] = Instance.new("TextButton", G2L["65"]);
G2L["68"]["BorderSizePixel"] = 0;
G2L["68"]["TextTransparency"] = 1;
G2L["68"]["TextSize"] = 14;
G2L["68"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["68"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["68"]["BackgroundTransparency"] = 1;
G2L["68"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["68"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["68"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Place
G2L["69"] = Instance.new("ImageLabel", G2L["53"]);
G2L["69"]["BorderSizePixel"] = 0;
G2L["69"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["69"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["69"]["Image"] = [[rbxassetid://76183981184625]];
G2L["69"]["Size"] = UDim2.new(0, 17, 0, 31);
G2L["69"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["69"]["BackgroundTransparency"] = 1;
G2L["69"]["Name"] = [[Place]];
G2L["69"]["Position"] = UDim2.new(0.07772, 0, 0.68359, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Place.UIAspectRatioConstraint
G2L["6a"] = Instance.new("UIAspectRatioConstraint", G2L["69"]);



-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Place.TextLabel
G2L["6b"] = Instance.new("TextLabel", G2L["69"]);
G2L["6b"]["TextWrapped"] = true;
G2L["6b"]["ZIndex"] = 2;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextSize"] = 20;
G2L["6b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6b"]["TextScaled"] = true;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["6b"]["TextColor3"] = Color3.fromRGB(235, 235, 235);
G2L["6b"]["BackgroundTransparency"] = 1;
G2L["6b"]["Size"] = UDim2.new(-4.26692, 210, -0.53833, 30);
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[ClickToCopy]];
G2L["6b"]["Position"] = UDim2.new(1.23488, 0, 0.19219, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.Place.TextButton
G2L["6c"] = Instance.new("TextButton", G2L["69"]);
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["TextTransparency"] = 1;
G2L["6c"]["TextSize"] = 14;
G2L["6c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6c"]["BackgroundTransparency"] = 1;
G2L["6c"]["Size"] = UDim2.new(0, 76, 0, 21);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Position"] = UDim2.new(-0, 0, 0, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.ImageLabel
G2L["6d"] = Instance.new("ImageLabel", G2L["53"]);
G2L["6d"]["ZIndex"] = 2;
G2L["6d"]["BorderSizePixel"] = 0;
G2L["6d"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
G2L["6d"]["ImageTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["6d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6d"]["Image"] = [[rbxassetid://104649966280536]];
G2L["6d"]["Size"] = UDim2.new(0, 23, 0, 42);
G2L["6d"]["Visible"] = false;
G2L["6d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6d"]["BackgroundTransparency"] = 1;
G2L["6d"]["Position"] = UDim2.new(0.68635, 0, 0.08106, 0);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.ImageLabel.UICorner
G2L["6e"] = Instance.new("UICorner", G2L["6d"]);
G2L["6e"]["CornerRadius"] = UDim.new(0, 25);


-- StarterGui.ScreenGui.PC.ScrollingFrame.Example.ImageLabel.UIAspectRatioConstraint
G2L["6f"] = Instance.new("UIAspectRatioConstraint", G2L["6d"]);



-- StarterGui.ScreenGui.PC.TextBox
G2L["70"] = Instance.new("TextBox", G2L["3c"]);
G2L["70"]["ZIndex"] = 2;
G2L["70"]["BorderSizePixel"] = 0;
G2L["70"]["TextSize"] = 14;
G2L["70"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["70"]["BackgroundColor3"] = Color3.fromRGB(19, 19, 19);
G2L["70"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["70"]["PlaceholderText"] = [[search your script]];
G2L["70"]["Size"] = UDim2.new(0, 137, 0, 27);
G2L["70"]["Position"] = UDim2.new(0.78562, 0, 0.14031, 0);
G2L["70"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["70"]["Text"] = [[]];
G2L["70"]["BackgroundTransparency"] = 0.55;


-- StarterGui.ScreenGui.PC.ImageButton
G2L["71"] = Instance.new("ImageButton", G2L["3c"]);
G2L["71"]["BorderSizePixel"] = 0;
G2L["71"]["BackgroundTransparency"] = 1;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["71"]["BackgroundColor3"] = Color3.fromRGB(30, 30, 30);
G2L["71"]["ImageColor3"] = Color3.fromRGB(71, 71, 71);
G2L["71"]["ZIndex"] = 2;
G2L["71"]["Image"] = [[rbxassetid://15985408996]];
G2L["71"]["Size"] = UDim2.new(0, 21, 0, 21);
G2L["71"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["Rotation"] = 135;
G2L["71"]["Position"] = UDim2.new(0.96096, 0, 0.14433, 0);


-- StarterGui.ScreenGui.PC.ImageButton.UIAspectRatioConstraint
G2L["72"] = Instance.new("UIAspectRatioConstraint", G2L["71"]);



-- StarterGui.ScreenGui.PC.Top
G2L["73"] = Instance.new("Frame", G2L["3c"]);
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(22, 22, 22);
G2L["73"]["Size"] = UDim2.new(0, 808, 0, 50);
G2L["73"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["Name"] = [[Top]];


-- StarterGui.ScreenGui.PC.Top.KRNL
G2L["74"] = Instance.new("ImageLabel", G2L["73"]);
G2L["74"]["BorderSizePixel"] = 0;
G2L["74"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["74"]["Image"] = [[rbxassetid://125999447519604]];
G2L["74"]["Size"] = UDim2.new(0, 57, 0, 53);
G2L["74"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["74"]["BackgroundTransparency"] = 1;
G2L["74"]["Name"] = [[KRNL]];


-- StarterGui.ScreenGui.PC.Top.KRNL.UIAspectRatioConstraint
G2L["75"] = Instance.new("UIAspectRatioConstraint", G2L["74"]);



-- StarterGui.ScreenGui.PC.Top.TextLabel
G2L["76"] = Instance.new("TextLabel", G2L["73"]);
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["TextSize"] = 17;
G2L["76"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["76"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["BackgroundTransparency"] = 1;
G2L["76"]["Size"] = UDim2.new(0, 169, 0, 52);
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["Text"] = [[KRNL Executor]];
G2L["76"]["Position"] = UDim2.new(0.06535, 0, 0.02, 0);


-- StarterGui.ScreenGui.PC.UIDrag
G2L["77"] = Instance.new("LocalScript", G2L["3c"]);
G2L["77"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Runner
G2L["78"] = Instance.new("LocalScript", G2L["1"]);
G2L["78"]["Name"] = [[Runner]];


-- Require G2L wrapper
local G2L_REQUIRE = require;
local G2L_MODULES = {};
local function require(Module:ModuleScript)
    local ModuleState = G2L_MODULES[Module];
    if ModuleState then
        if not ModuleState.Required then
            ModuleState.Required = true;
            ModuleState.Value = ModuleState.Closure();
        end
        return ModuleState.Value;
    end;
    return G2L_REQUIRE(Module);
end

G2L_MODULES[G2L["d"]] = {
Closure = function()
    local script = G2L["d"];local M = {}

local Button = {
	clear = script.Parent.Parent.Clr,
	execute = script.Parent.Parent.Exe,
	inject = script.Parent.Parent.Inj
}

local function notify(Title, msg, duration)
	game.StarterGui:SetCore("SendNotification", {
		Title = Title,
		Text = msg,
		Duration = duration or 5,
	})
end

function M.LoadAPI(textbox)
	Button.execute.MouseButton1Click:Connect(function()
		loadstring(textbox.Text)()
	end)
	
	Button.clear.MouseButton1Click:Connect(function()
		textbox.Text = ""
	end)
	
	Button.inject.MouseButton1Click:Connect(function()
		notify("Krnl", "injecting please wait!", 5)
		task.wait(5)
		local remote = game.ReplicatedStorage:FindFirstChild("__KRNL")
		if remote then
			notify("Krnl", "Already injected", 5)
		else
			local newRemote = Instance.new("RemoteFunction")
			newRemote.Name = "__KRNL"
			newRemote.Parent = game.ReplicatedStorage
			notify("Krnl", "Successfully injected", 5)
		end
	end)
end

return M


end;
};
G2L_MODULES[G2L["45"]] = {
Closure = function()
    local script = G2L["45"];local M = {}

local Button = {
	clear = script.Parent.Parent.Clr,
	execute = script.Parent.Parent.Exe,
	inject = script.Parent.Parent.Inj
}

local function notify(Title, msg, duration)
	game.StarterGui:SetCore("SendNotification", {
		Title = Title,
		Text = msg,
		Duration = duration or 5,
	})
end

function M.LoadAPI(textbox)
	Button.execute.MouseButton1Click:Connect(function()
		loadstring(textbox.Text)()
	end)
	
	Button.clear.MouseButton1Click:Connect(function()
		textbox.Text = ""
	end)
	
	Button.inject.MouseButton1Click:Connect(function()
		notify("Krnl", "injecting please wait!", 5)
		task.wait(5)
		local remote = game.ReplicatedStorage:FindFirstChild("__KRNL")
		if remote then
			notify("Krnl", "Already injected", 5)
		else
			local newRemote = Instance.new("RemoteFunction")
			newRemote.Name = "__KRNL"
			newRemote.Parent = game.ReplicatedStorage
			notify("Krnl", "Successfully injected", 5)
		end
	end)
end

return M


end;
};
-- StarterGui.ScreenGui.Mobile.LocalScript
local function C_3()
local script = G2L["3"];
	local Example = script.Parent.ScrollingFrame:FindFirstChild("Example")
	local Searchbtn = script.Parent:FindFirstChild("ImageButton")
	local search = script.Parent:FindFirstChild("TextBox")
	
	local HttpService = game:GetService("HttpService")
	
	if Example then
		Example.Visible = false
	end
	
	local function clearResults()
		local scrollingFrame = script.Parent.ScrollingFrame
		local children = scrollingFrame:GetChildren()
		for i = #children, 1, -1 do
			local child = children[i]
			if child.Name ~= "Example" and child:IsA("Frame") then
				child:Destroy()
			elseif child.Name == "Example" and child ~= Example then
				child:Destroy()
			end
		end
	end
	
	local function SearchScripts(txt)
		clearResults()
		local ok, response = pcall(function()
			return game:HttpGet("https://scriptblox.com/api/script/search?q="..txt.."&page=1&max=1000")
		end)
		if not ok or not response then return end
	
		local data = HttpService:JSONDecode(response)
		if not data.result or not data.result.scripts or #data.result.scripts == 0 then
			if Example then
				local noResult = Example:Clone()
				noResult.Name = "NoResult"
				noResult.Parent = script.Parent.ScrollingFrame
				noResult.Visible = true
				noResult.Size = UDim2.new(1,-10,0,40)
				local textLabel = noResult:FindFirstChild("TextLabel")
				if textLabel then
					textLabel.Text = "No results found."
				end
				local textButton = noResult:FindFirstChild("TextButton")
				if textButton then
					textButton.Visible = false
				end
			end
			return
		end
	
		for i = 1, #data.result.scripts do
			local info = data.result.scripts[i]
			if Example then
				local holder = Example:Clone()
				holder.Name = "Result_"..tostring(i)
				holder.Parent = script.Parent.ScrollingFrame
				holder.Visible = true
				holder.Size = UDim2.new(1,-10,0,40)
	
				if info.key == false then
					holder.COntainsKEy.TextLabel.Text = " Dont Contains Key!!"
				elseif info.key == true then
					holder.COntainsKEy.TextLabel.Text = "Contains Key!!"
				end
	
				if info.verified == false then
					holder.Verify.TextLabel.Text = "Not Verified!"
				elseif info.verified == true then
					holder.Verify.TextLabel.Text = "Verified!"
				end
	
				
				local countLabel = holder:FindFirstChild("Count")
				if countLabel and countLabel:IsA("TextLabel") then
					countLabel.Text = tostring(i)
				end
	
				holder.Place.TextLabel.Text = tostring(info.game._id)
				holder.Copy.TextButton.MouseButton1Click:Connect(function()
					setclipboard(tostring(info.script))
				end)
	
				local viewLabel = holder:FindFirstChild("View")
				if viewLabel and viewLabel:FindFirstChild("TextLabel") then
					viewLabel.TextLabel.Text = tostring(info.views or "0")
				end
	
				local textLabel = holder:FindFirstChild("TextLabel")
				if textLabel then
					textLabel.Text = info.title or "No Title"
				end
	
				local textButton = holder:FindFirstChild("TextButton")
				if textButton then
					textButton.Visible = true
					textButton.MouseButton1Click:Connect(function()
						pcall(function()
							loadstring(info.script)()
						end)
					end)
				end
	
				local imageLabel = holder:FindFirstChild("ImageLabel")
				if imageLabel then
					imageLabel.Image = "rbxassetid://"..tostring(info.imageUrl)
				end
			end
		end
	end
	
	if Searchbtn then
		Searchbtn.MouseButton1Click:Connect(function()
			if search and search.Text ~= "" then
				SearchScripts(search.Text)
			end
		end)
	end
	
	
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Mobile.btn.LocalScript
local function C_c()
local script = G2L["c"];
	local re = require(script.API)
	local textbox = script.Parent.Parent.Main.Code
	
	re.LoadAPI(textbox)
end;
task.spawn(C_c);
-- StarterGui.ScreenGui.Mobile.UIDrag
local function C_3b()
local script = G2L["3b"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end;
task.spawn(C_3b);
-- StarterGui.ScreenGui.PC.LocalScript
local function C_3d()
local script = G2L["3d"];
	local Example = script.Parent.ScrollingFrame:FindFirstChild("Example")
	local Searchbtn = script.Parent:FindFirstChild("ImageButton")
	local search = script.Parent:FindFirstChild("TextBox")
	
	local HttpService = game:GetService("HttpService")
	
	if Example then
		Example.Visible = false
	end
	
	local function clearResults()
		local scrollingFrame = script.Parent.ScrollingFrame
		local children = scrollingFrame:GetChildren()
		for i = #children, 1, -1 do
			local child = children[i]
			if child.Name ~= "Example" and child:IsA("Frame") then
				child:Destroy()
			elseif child.Name == "Example" and child ~= Example then
				child:Destroy()
			end
		end
	end
	
	local function SearchScripts(txt)
		clearResults()
		local ok, response = pcall(function()
			return game:HttpGet("https://scriptblox.com/api/script/search?q="..txt.."&page=1&max=1000")
		end)
		if not ok or not response then return end
	
		local data = HttpService:JSONDecode(response)
		if not data.result or not data.result.scripts or #data.result.scripts == 0 then
			if Example then
				local noResult = Example:Clone()
				noResult.Name = "NoResult"
				noResult.Parent = script.Parent.ScrollingFrame
				noResult.Visible = true
				noResult.Size = UDim2.new(1,-10,0,40)
				local textLabel = noResult:FindFirstChild("TextLabel")
				if textLabel then
					textLabel.Text = "No results found."
				end
				local textButton = noResult:FindFirstChild("TextButton")
				if textButton then
					textButton.Visible = false
				end
			end
			return
		end
	
		for i = 1, #data.result.scripts do
			local info = data.result.scripts[i]
			if Example then
				local holder = Example:Clone()
				holder.Name = "Result_"..tostring(i)
				holder.Parent = script.Parent.ScrollingFrame
				holder.Visible = true
				holder.Size = UDim2.new(1,-10,0,40)
	
				if info.key == false then
					holder.COntainsKEy.TextLabel.Text = " Dont Contains Key!!"
				elseif info.key == true then
					holder.COntainsKEy.TextLabel.Text = "Contains Key!!"
				end
	
				if info.verified == false then
					holder.Verify.TextLabel.Text = "Not Verified!"
				elseif info.verified == true then
					holder.Verify.TextLabel.Text = "Verified!"
				end
	
				
				local countLabel = holder:FindFirstChild("Count")
				if countLabel and countLabel:IsA("TextLabel") then
					countLabel.Text = tostring(i)
				end
	
				holder.Place.TextLabel.Text = tostring(info.game._id)
				holder.Copy.TextButton.MouseButton1Click:Connect(function()
					setclipboard(tostring(info.script))
				end)
	
				local viewLabel = holder:FindFirstChild("View")
				if viewLabel and viewLabel:FindFirstChild("TextLabel") then
					viewLabel.TextLabel.Text = tostring(info.views or "0")
				end
	
				local textLabel = holder:FindFirstChild("TextLabel")
				if textLabel then
					textLabel.Text = info.title or "No Title"
				end
	
				local textButton = holder:FindFirstChild("TextButton")
				if textButton then
					textButton.Visible = true
					textButton.MouseButton1Click:Connect(function()
						pcall(function()
							loadstring(info.script)()
						end)
					end)
				end
	
				local imageLabel = holder:FindFirstChild("ImageLabel")
				if imageLabel then
					imageLabel.Image = "rbxassetid://"..tostring(info.imageUrl)
				end
			end
		end
	end
	
	if Searchbtn then
		Searchbtn.MouseButton1Click:Connect(function()
			if search and search.Text ~= "" then
				SearchScripts(search.Text)
			end
		end)
	end
	
	
end;
task.spawn(C_3d);
-- StarterGui.ScreenGui.PC.btn.LocalScript
local function C_44()
local script = G2L["44"];
	local re = require(script.API)
	local textbox = script.Parent.Parent.Main.Code
	
	re.LoadAPI(textbox)
end;
task.spawn(C_44);
-- StarterGui.ScreenGui.PC.UIDrag
local function C_77()
local script = G2L["77"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end;
task.spawn(C_77);
-- StarterGui.ScreenGui.Runner
local function C_78()
local script = G2L["78"];
	local usertype = game:GetService("UserInputService")
	
	if usertype.KeyboardEnabled  then
		script.Parent.Mobile.Visible = false
		script.Parent.PC.Visible = true
		
	elseif usertype.TouchEnabled then
		script.Parent.Mobile.Visible = true
		script.Parent.PC.Visible = false
	end
end;
task.spawn(C_78);

return G2L["1"], require;
