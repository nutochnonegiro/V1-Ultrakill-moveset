# V1 Ultrakill TSB moveset (wip)

--Move & Ultimate Names

local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("1").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Knucklebuster"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("2").Base

local ToolName = baseButton.ToolName


ToolName.Text = "The Ruthless Machine Barrage"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("3").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Feedbacker"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("4").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Groundslam"


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local playerGui = player:WaitForChild("PlayerGui")


local function findGuiAndSetText()

    local screenGui = playerGui:FindFirstChild("ScreenGui")

    if screenGui then

        local magicHealthFrame = screenGui:FindFirstChild("MagicHealth")

        if magicHealthFrame then

            local textLabel = magicHealthFrame:FindFirstChild("TextLabel")

            if textLabel then

                textLabel.Text = "UltimateName"

            end

        end

    end

end


playerGui.DescendantAdded:Connect(findGuiAndSetText)

findGuiAndSetText()

--[[Animations]]

--[[Move 1]]

local animationId = 18896127525


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://17838006839"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0.1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.9)


    end

end

--[[END OF MOVE 1 ANIM]]

--[[Move 2]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 18716470698


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18181589384"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF MOVE 2 ANIM]]

--[[Move 3]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 18715999597


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://17838619895"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.3


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

--[[END OF MOVE 3 ANIM]]

--[[Move 4]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 18897119503


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://16515850153"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF MOVE 4 ANIM]]

--[[Wall combo]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 18716485513


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://15943915877"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.05


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF WALL COMBO ANIM]]

--[[Ult Activation]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 18715907469


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://17106858586 "

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)

    end

end
--[[END OF ULT ACTIVATION ANIM]]

--[[Dash]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10479335397


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://13294790250"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1.3)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

--[[END OF DASH ANIM]]

--[[Uppercut]]
humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10503381238


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14900168720"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 1.3


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.7)


    end

end

--[[END OF UPPERCUT ANIM]]

--[[Downslam]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 73524008706491


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12447247483"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


wait(0.2)

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(6)


    end

end

--[[END OF DOWNSLAM ANIM]]

--[[Punch anims]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local animationIdsToStop = {

    [17859015788] = true, --downslam finisher

    [173255510002] = true, --punch1

    [17325513870] = true, --punch2

    [17325522388] = true, --punch3

    [18716001119] = true, --punch4




local replacementAnimations = {}

    ["10469493270"] = "rbxassetid://17889458563", --punch1

    ["10469630950"] = "rbxassetid://17889461810", --punch2

    ["10469639222"] = "rbxassetid://17889471098", --punch3

    ["10469643643"] = "rbxassetid://17889290569", --punch4

    ["17859015788"] = "rbxassetid://12684185971", --downslam finisher

    ["11365563255"] = "rbxassetid://14516273501" --punch idk

}


local queue = {}

local isAnimating = false


local function playReplacementAnimation(animationId)

    if isAnimating then

        table.insert(queue, animationId)

        return

    end

   

    isAnimating = true

    local replacementAnimationId = replacementAnimations[tostring(animationId)]

    if replacementAnimationId then

        local AnimAnim = Instance.new("Animation")

        AnimAnim.AnimationId = replacementAnimationId

        local Anim = humanoid:LoadAnimation(AnimAnim)

        Anim:Play()

       

        Anim.Stopped:Connect(function()

            isAnimating = false

            if #queue > 0 then

                local nextAnimationId = table.remove(queue, 1)

                playReplacementAnimation(nextAnimationId)

            end

        end)

    else

        isAnimating = false

    end

end

local function stopSpecificAnimations()

    for _, track in ipairs(humanoid:GetPlayingAnimationTracks()) do

        local animationId = tonumber(track.Animation.AnimationId:match("%d+"))

        if animationIdsToStop[animationId] then

            track:Stop()

        end

    end

end


local function onAnimationPlayed(animationTrack)

    local animationId = tonumber(animationTrack.Animation.AnimationId:match("%d+"))

    if animationIdsToStop[animationId] then

        stopSpecificAnimations()

        animationTrack:Stop()

       

        local replacementAnimationId = replacementAnimations[tostring(animationId)]

        if replacementAnimationId then

            playReplacementAnimation(animationId)

        end

    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoidRootPart = character:WaitForChild("HumanoidRootPart")


local function onBodyVelocityAdded(bodyVelocity)

    if bodyVelocity:IsA("BodyVelocity") then

        bodyVelocity.Velocity = Vector3.new(bodyVelocity.Velocity.X, 0, bodyVelocity.Velocity.Z)

    end

end


character.DescendantAdded:Connect(onBodyVelocityAdded)


for _, descendant in pairs(character:GetDescendants()) do

    onBodyVelocityAdded(descendant)

end


player.CharacterAdded:Connect(function(newCharacter)

    character = newCharacter

    humanoidRootPart = character:WaitForChild("HumanoidRootPart")

    character.DescendantAdded:Connect(onBodyVelocityAdded)

   

    for _, descendant in pairs(character:GetDescendants()) do

        onBodyVelocityAdded(descendant)

    end

end) 

--[[Adding Quote or Message when Executed]]

local player = game.Players.LocalPlayer
repeat wait() until player.Character
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local ReplicatedStorage = game:GetService("ReplicatedStorage")

-- Messages to send
local messages = {"DEVS ARE DEAD.","BLOOD IS FUEL.","THE STRONGEST BATTLEGROUNDS IS FULL."}

local function sendMessage(text)
    ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(text, "All")
end

for _, message in ipairs(messages) do
    sendMessage(message)
    wait(1.7) -- Wait time for each message
end

--[[END OF QUOTES]]

--[[Idle Animation]]

local animationId = "rbxassetid://15099756132" -- Replace with your animation ID
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:FindFirstChildOfClass("Animator") or humanoid:WaitForChild("Animator")

local animation = Instance.new("Animation")
animation.AnimationId = animationId
local animationTrack = animator:LoadAnimation(animation)

local function isMoving()
    local velocity = humanoid.MoveDirection.Magnitude
    return velocity > 0
end

while true do
    if not isMoving() then
        if not animationTrack.IsPlaying then
            animationTrack:Play()
        end
    else
        if animationTrack.IsPlaying then
            animationTrack:Stop()
        end
    end
    wait(0.1)
end


--[[END OF IDLE ANIM]]

--[[Run Anim]]

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local animationId = "rbxassetid://15962326593" -- Replace with your animation ID
local animation = Instance.new("Animation")
animation.AnimationId = animationId

local animationTrack
local isMoving = false

local function playAnimation()
    if not animationTrack then
        animationTrack = animator:LoadAnimation(animation)
    end
    
    if not isMoving then
        isMoving = true
        animationTrack:Play()
    end
end

local function stopAnimation()
    if isMoving and animationTrack then
        isMoving = false
        animationTrack:Stop()
    end
end

local function onHumanoidChanged()
    if humanoid.MoveDirection.Magnitude > 0 then
        playAnimation()
    else
        stopAnimation()
    end
end

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)

onHumanoidChanged()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local animationId = "rbxassetid://15962326593" -- Replace with your animation ID
local animation = Instance.new("Animation")
animation.AnimationId = animationId

local animationTrack
local isMoving = false

local function playAnimation()
    if not animationTrack then
        animationTrack = animator:LoadAnimation(animation)
    end
    
    if not isMoving then
        isMoving = true
        animationTrack:Play()
    end
end

local function stopAnimation()
    if isMoving and animationTrack then
        isMoving = false
        animationTrack:Stop()
    end
end

local function onHumanoidChanged()
    if humanoid.MoveDirection.Magnitude > 0 then
        playAnimation()
    else
        stopAnimation()
    end
end

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)

onHumanoidChanged()
humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local animationId = "rbxassetid://15962326593" -- Replace with your animation ID
local animation = Instance.new("Animation")
animation.AnimationId = animationId

local animationTrack
local isMoving = false

local function playAnimation()
    if not animationTrack then
        animationTrack = animator:LoadAnimation(animation)
    end
    
    if not isMoving then
        isMoving = true
        animationTrack:Play()
    end
end

local function stopAnimation()
    if isMoving and animationTrack then
        isMoving = false
        animationTrack:Stop()
    end
end

local function onHumanoidChanged()
    if humanoid.MoveDirection.Magnitude > 0 then
        playAnimation()
    else
        stopAnimation()
    end
end

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)

onHumanoidChanged()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local animationId = "rbxassetid://15962326593" -- Replace with your animation ID
local animation = Instance.new("Animation")
animation.AnimationId = animationId

local animationTrack
local isMoving = false

local function playAnimation()
    if not animationTrack then
        animationTrack = animator:LoadAnimation(animation)
    end
    
    if not isMoving then
        isMoving = true
        animationTrack:Play()
    end
end

local function stopAnimation()
    if isMoving and animationTrack then
        isMoving = false
        animationTrack:Stop()
    end
end

local function onHumanoidChanged()
    if humanoid.MoveDirection.Magnitude > 0 then
        playAnimation()
    else
        stopAnimation()
    end
end

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)

onHumanoidChanged()

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local animationId = "rbxassetid://15962326593" -- Replace with your animation ID
local animation = Instance.new("Animation")
animation.AnimationId = animationId

local animationTrack
local isMoving = false

local function playAnimation()
    if not animationTrack then
        animationTrack = animator:LoadAnimation(animation)
    end
    
    if not isMoving then
        isMoving = true
        animationTrack:Play()
    end
end

local function stopAnimation()
    if isMoving and animationTrack then
        isMoving = false
        animationTrack:Stop()
    end
end

local function onHumanoidChanged()
    if humanoid.MoveDirection.Magnitude > 0 then
        playAnimation()
    else
        stopAnimation()
    end
end

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)

onHumanoidChanged()

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local animator = humanoid:WaitForChild("Animator")

local animationId = "rbxassetid://15962326593" -- Replace with your animation ID
local animation = Instance.new("Animation")
animation.AnimationId = animationId

local animationTrack
local isMoving = false

local function playAnimation()
    if not animationTrack then
        animationTrack = animator:LoadAnimation(animation)
    end
    
    if not isMoving then
        isMoving = true
        animationTrack:Play()
    end
end

local function stopAnimation()
    if isMoving and animationTrack then
        isMoving = false
        animationTrack:Stop()
    end
end

local function onHumanoidChanged()
    if humanoid.MoveDirection.Magnitude > 0 then
        playAnimation()
    else
        stopAnimation()
    end
end

humanoid:GetPropertyChangedSignal("MoveDirection"):Connect(onHumanoidChanged)

onHumanoidChanged()

--[[RUN ANIM END]]

--[[Execute Anims (Animations when you execute script]]

local p = game.Players.LocalPlayer
local Humanoid = p.Character:WaitForChild("Humanoid")

for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do
    animTrack:Stop()
end

local AnimAnim = Instance.new("Animation")
AnimAnim.AnimationId = "rbxassetid://14611879113" -- Replace with your animation ID

local Anim = Humanoid:LoadAnimation(AnimAnim)

local startTime = 0.05

Anim:Play()
Anim:AdjustSpeed(0)
Anim.TimePosition = startTime
Anim:AdjustSpeed(1)

--[[END OF EXECUTE ANIMS]]
