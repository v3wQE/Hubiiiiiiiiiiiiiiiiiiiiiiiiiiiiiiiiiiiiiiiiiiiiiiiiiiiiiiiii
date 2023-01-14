hookfunction(game.Players.LocalPlayer.IsInGroup, function() return true end)

 local function callback(Text)
 if Text == "Button1 text" then
  print ("Answer")
elseif Text == ("Button2 text") then
 print ("Answer2")
 end
end

local NotificationBindable = Instance.new("BindableFunction")
NotificationBindable.OnInvoke = callback
--
game.StarterGui:SetCore("SendNotification",  {
 Title = "Made By v3w#9205";
 Text = "I Hope You Enjoin :)";
 Icon = "";
 Duration = 5;
 Callback = NotificationBindable;
})

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Dx9Ware", "Synapse")

local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Main")
Section:NewButton("Fly", "Enjoin My Script:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/v3wQE/flying/main/README.md"))();
end)

Section:NewButton("AdminFly", "Enjoin My Script:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/22kristina/swag/main/admin_fly"))()
end)

Section:NewButton("TarGet", "Enjoin My Script:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GS21Official/DH-VictimMenu-Script/main/Dh%20VictimMenu%3A%20Script"))()
end)

Section:NewButton("Antistomp", "Enjoin My Script:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/v3wQE/flying/main/README.md"))();
end)

Section:NewButton("Antibag", "Enjoin My Script:)", function()
      local LP = game.Players.LocalPlayer;

    for i,v in ipairs(LP.Character:GetDescendants()) do
        if v.Name == "Christmas_Sock" then v:Destroy()
            end
        end
            
        LP.Character.ChildAdded:Connect(function()
        wait(0.3)
        for i,v in ipairs(LP.Character:GetDescendants()) do
        if v.Name == "Christmas_Sock" then v:Destroy()
        end
        end
        end)
end)


local Tab = Window:NewTab("Aimlock")
local Section = Tab:NewSection("Aimlock")
Section:NewButton("Camlock", "Enjoin My Script:)", function()
    getgenv().RecurringPoint = "UpperTorso"
getgenv().Hitbox = "UpperTorso"
getgenv().Keybind = "q"
getgenv().AimbotStrengthAmount = 1
getgenv().PredictionAmount = 10
getgenv().Radius = 25
getgenv().UsePrediction = true
getgenv().AimbotStrength = true
getgenv().FirstPerson = true
getgenv().ThirdPerson = true
getgenv().TeamCheck = false
getgenv().Enabled = true


-- // main script use with silent aim / / -- 

loadstring(game:HttpGet("https://raw.githubusercontent.com/tenaaki/GenericAimbot/main/v1.0.0"))()

end)

Section:NewButton("Balant", "Enjoin My Script:)", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/v3wQE/Balant-locking/main/README.md"))();

end)

Section:NewButton("Nodeley", "Enjoin My Script:)", function()
    local ReplicatedStorage = game.ReplicatedStorage
local Network = game.Network
local Delay = ReplicatedStorage.BulletHole.Delay

Delay.Position:Destroy()
Delay.Position = 0
end)

local Tab = Window:NewTab("Fun")
local Section = Tab:NewSection("Fun")
Section:NewButton("Headless", "Enjoin My Script:)", function()
    game.Players.LocalPlayer.Character.Head.Transparency = 1
game.Players.LocalPlayer.Character.Head.Transparency = 1
for i,v in pairs(game.Players.LocalPlayer.Character.Head:GetChildren()) do
if (v:IsA("Decal")) then
v.Transparency = 1
end
end
end)

Section:NewButton("KorBlox", "Enjoin My Script:)", function()
local ply = game.Players.LocalPlayer
local chr = ply.Character
chr.RightLowerLeg.MeshId = "902942093"
chr.RightLowerLeg.Transparency = "1"
chr.RightUpperLeg.MeshId = "http://www.roblox.com/asset/?id=902942096"
chr.RightUpperLeg.TextureID = "http://roblox.com/asset/?id=902843398"
chr.RightFoot.MeshId = "902942089"
chr.RightFoot.Transparency = "1"
end)

Section:NewButton("HeadlessAndKorblox", "Enjoin My Script:)", function()
    local L_393_ = game.Players.LocalPlayer.Character
    local L_394_ = L_393_:WaitForChild("Head")
    local L_395_ = L_394_:WaitForChild("face")
    L_395_.Transparency = 1 --Texture = "rbxassetid://209712379"
    L_394_.Transparency = 1
    local L_396_ = game.Players.LocalPlayer.Character
    local L_397_ = game.Players.LocalPlayer.Character
    local L_398_ = L_396_.Head
    local L_399_ = L_398_.face
    local L_400_ = L_397_.RightFoot
    local L_401_ = L_397_.RightLowerLeg
    local L_402_ = L_397_.RightUpperLeg
    local L_403_ = L_397_.LeftFoot
    local L_404_ = L_397_.LeftLowerLeg
    local L_405_ = L_397_.LeftUpperLeg
    L_400_.MeshId = "http://www.roblox.com/asset/?id=902942093"
    L_401_.MeshId = "http://www.roblox.com/asset/?id=902942093"
    L_402_.MeshId = "http://www.roblox.com/asset/?id=902942096"
    L_402_.TextureID = "http://roblox.com/asset/?id=902843398"
    L_400_.Transparency = 1
    L_401_.Transparency = 1
end)


local Tab = Window:NewTab("Speed")
local Section = Tab:NewSection("Speed")
Section:NewButton("Cframe", "Very OP Enjoin:)", function()
          local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Speed", "DarkTheme")

local speed = Window:NewTab("Speed")
local rs = speed:NewSection("CFrame Speed")
rs:NewButton("CFrame Guns FIX", "ButtonInfo", function()
    for _, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
        if v:IsA("Script") and v.Name ~= "Health" and v.Name ~= "Sound" and v:FindFirstChild("LocalScript") then
            v:Destroy()
        end
    end
    game.Players.LocalPlayer.CharacterAdded:Connect(function(char)
        repeat
            wait()
        until game.Players.LocalPlayer.Character
        char.ChildAdded:Connect(function(child)
            if child:IsA("Script") then 
                wait(0.1)
                if child:FindFirstChild("LocalScript") then
                    child.LocalScript:FireServer()
                end
            end
        end)
    end)
end)
rs:NewButton("CFrame Speed (N)", "ButtonInfo", function()
        repeat
        wait()
    until game:IsLoaded()
    local L_134_ = game:service('Players')
    local L_135_ = L_134_.LocalPlayer
    repeat
        wait()
    until L_135_.Character
    local L_136_ = game:service('UserInputService')
    local L_137_ = game:service('RunService')
    getgenv().Multiplier = 0.5
    local L_138_ = true
    local L_139_
    L_136_.InputBegan:connect(function(L_140_arg0)
        if L_140_arg0.KeyCode == Enum.KeyCode.LeftBracket then
            Multiplier = Multiplier + 0.01
            print(Multiplier)
            wait(0.2)
            while L_136_:IsKeyDown(Enum.KeyCode.LeftBracket) do
                wait()
                Multiplier = Multiplier + 0.01
                print(Multiplier)
            end
        end
        if L_140_arg0.KeyCode == Enum.KeyCode.RightBracket then
            Multiplier = Multiplier - 0.01
            print(Multiplier)
            wait(0.2)
            while L_136_:IsKeyDown(Enum.KeyCode.RightBracket) do
                wait()
                Multiplier = Multiplier - 0.01
                print(Multiplier)
            end
        end
        if L_140_arg0.KeyCode == Enum.KeyCode.N then
            L_138_ = not L_138_
            if L_138_ == true then
                repeat
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame + game.Players.LocalPlayer.Character.Humanoid.MoveDirection * Multiplier
                    game:GetService("RunService").Stepped:wait()
                until L_138_ == false
            end
        end
    end)
end)
rs:NewSlider("CFrame Speed ", "SliderInfo", 5, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    getgenv().Multiplier = s
end)
rs:NewKeybind("Toggle UI", "KeybindInfo", Enum.KeyCode.RightControl, function()
    Library.ToggleUI()
end)
end)

local Tab = Window:NewTab("Godmode")
local Section = Tab:NewSection("Godmode")
Section:NewButton("Godmode Gun", "Very OP Enjoin:)", function()
              local localPlayer = game:GetService('Players').LocalPlayer;
                local localCharacter = localPlayer.Character;
                localCharacter:FindFirstChildOfClass('Humanoid').Health = 0;
                local newCharacter = localPlayer.CharacterAdded:Wait();
                local spoofFolder = Instance.new('Folder');
                spoofFolder.Name = 'FULLY_LOADED_CHAR';
                spoofFolder.Parent = newCharacter;
                newCharacter:WaitForChild('RagdollConstraints'):Destroy();
                local spoofValue = Instance.new('BoolValue', newCharacter);
                spoofValue.Name = 'RagdollConstraints';
                local name = game.Players.LocalPlayer.Name
                local lol =    game.Workspace:WaitForChild(name)
                local money = Instance.new("Folder",game.Players.LocalPlayer.Character);money.Name = "FULLY_LOADED_CHAR"
                lol.Parent = game.Workspace.Players
                game.Players.LocalPlayer.Character:WaitForChild("BodyEffects")
                game.Players.LocalPlayer.Character.BodyEffects.BreakingParts:Destroy()
end)

local Tab = Window:NewTab("Misc")
local Section = Tab:NewSection("Misc")
Section:NewButton("Rejoin", "Very OP Enjoin:)", function()
          loadstring(game:HttpGet("https://raw.githubusercontent.com/v3wQE/En/main/README.md"))();
end)

local Tab = Window:NewTab("Toggle")
local Section = Tab:NewSection("Toggle")
Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.V, function()
	Library:ToggleUI()
end)
