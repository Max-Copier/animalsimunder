local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/forumsLib/main/source.lua"))()
local Forums = Library.new("Storm Cheats | Free")

local Farm = Forums:NewSection("Auto Farm")
local Stingray = Forums:NewSection("Stingray")
local Octopus = Forums:NewSection("Octopus")
local Dolphin = Forums:NewSection("Dolphin")
local Turtle = Forums:NewSection("Turtle")
local Shark = Forums:NewSection("Shark")
local ClownFish = Forums:NewSection("Clown Fish")
local Orca = Forums:NewSection("Orca")
local Crocodile = Forums:NewSection("Crocodile")
local Axolotl = Forums:NewSection("Axolotl")


local isToggled1 = false
local isToggled2 = false
local isToggled3 = false
local isToggled4 = false
local isToggled5 = false
local isToggled6 = false
local isToggled7 = false
local isToggled8 = false
local isToggled9 = false
local isToggled10 = false
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled1 then
        local args = {
            multiply = 1,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy1.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 1", function(state)
    isToggled1 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled2 then
        local args = {
            multiply = 2,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy2.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 2", function(state)
    isToggled2 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled3 then
        local args = {
            multiply = 3,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy3.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 3", function(state)
    isToggled3 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled4 then
        local args = {
            multiply = 4,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy4.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 4", function(state)
    isToggled4 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled5 then
        local args = {
            multiply = 5,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy5.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 5", function(state)
    isToggled5 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled6 then
        local args = {
            multiply = 6,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy6.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 6", function(state)
    isToggled6 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled7 then
        local args = {
            multiply = 7,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy7.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 7", function(state)
    isToggled7 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled8 then
        local args = {
            multiply = 8,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy8.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 8", function(state)
    isToggled8 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled9 then
        local args = {
            multiply = 9,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy9.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 9", function(state)
    isToggled9 = state
end)
--
game:GetService("RunService").Heartbeat:Connect(function()
    if isToggled10 then
        local args = {
            multiply = 10,
            action = "hit",
            enemyHum = workspace.dummies.TrainingDummy10.Humanoid
        }
        game:GetService("ReplicatedStorage").DamageEvent:FireServer(args)
    end
end)

Farm:NewToggle("Dummy 10", function(state)
    isToggled10 = state
end)






Stingray:NewButton("||Stingray||", function()
    print("s")
end)

Stingray:NewButton("Stingray Magma", function()
    local args = {
        [1] = "Stingray",
        [2] = "stingray6",
        [3] = "Stingray"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Stingray:NewButton("Stingray Alien", function()
    local args = {
        [1] = "Stingray",
        [2] = "stingray7",
        [3] = "Stingray"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Stingray:NewButton("Stingray Poseidon", function()
    local args = {
        [1] = "Stingray",
        [2] = "stingray8",
        [3] = "Stingray"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Stingray:NewButton("Stingray Futuristic", function()
    local args = {
        [1] = "Stingray",
        [2] = "stingray9",
        [3] = "Stingray"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Stingray:NewButton("Stingray Futuristic 2", function()
    local args = {
        [1] = "Stingray",
        [2] = "stingray10",
        [3] = "Stingray"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Octopus:NewButton("||Octopus||", function()
    print("s")
end)

Octopus:NewButton("Octopus Poseidon", function()
    local args = {
        [1] = "Octopus",
        [2] = "octopus6",
        [3] = "Octopus"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Octopus:NewButton("Octopus Green Alien", function()
    local args = {
        [1] = "Octopus",
        [2] = "octopus7",
        [3] = "Octopus"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Octopus:NewButton("Octopus Red Alien", function()
    local args = {
        [1] = "Octopus",
        [2] = "octopus8",
        [3] = "Octopus"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Octopus:NewButton("Octopus Yellow Terminator", function()
    local args = {
        [1] = "Octopus",
        [2] = "octopus9",
        [3] = "Octopus"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Octopus:NewButton("Octopus Red Terminator", function()
    local args = {
        [1] = "Octopus",
        [2] = "octopus10",
        [3] = "Octopus"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Dolphin:NewButton("||Dolphin||", function()
    print("s")
end)

Dolphin:NewButton("Dolphin Zombie", function()
    local args = {
        [1] = "Dolphin",
        [2] = "dolphin6",
        [3] = "Dolphin"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Dolphin:NewButton("Dolphin Futuristic", function()
    local args = {
        [1] = "Dolphin",
        [2] = "dolphin7",
        [3] = "Dolphin"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Dolphin:NewButton("Dolphin Poseidon", function()
    local args = {
        [1] = "Dolphin",
        [2] = "dolphin8",
        [3] = "Dolphin"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Dolphin:NewButton("Dolphin Mechanic", function()
    local args = {
        [1] = "Dolphin",
        [2] = "dolphin9",
        [3] = "Dolphin"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Dolphin:NewButton("Dolphin Unicorn", function()
    local args = {
        [1] = "Dolphin",
        [2] = "dolphin10",
        [3] = "Dolphin"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Turtle:NewButton("||Turtle||", function()
    print("s")
end)

Turtle:NewButton("Turtle Apachi", function()
    local args = {
        [1] = "Turtle",
        [2] = "turtle6",
        [3] = "Turtle"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Turtle:NewButton("Turtle Watermelon", function()
    local args = {
        [1] = "Turtle",
        [2] = "turtle7",
        [3] = "Turtle"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Turtle:NewButton("Turtle Aqua", function()
    local args = {
        [1] = "Turtle",
        [2] = "turtle8",
        [3] = "Turtle"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Turtle:NewButton("Turtle Mountain", function()
    local args = {
        [1] = "Turtle",
        [2] = "turtle9",
        [3] = "Turtle"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Turtle:NewButton("Turtle Islands", function()
    local args = {
        [1] = "Turtle",
        [2] = "turtle10",
        [3] = "Turtle"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Shark:NewButton("||Shark||", function()
    print("s")
end)

Shark:NewButton("Shark Yin", function()
    local args = {
        [1] = "Shark",
        [2] = "shark6",
        [3] = "Shark"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Shark:NewButton("Shark Dream", function()
    local args = {
        [1] = "Shark",
        [2] = "shark7",
        [3] = "Shark"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Shark:NewButton("Shark Nightmare", function()
    local args = {
        [1] = "Shark",
        [2] = "shark8",
        [3] = "Shark"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Shark:NewButton("Shark Aqua", function()
    local args = {
        [1] = "Shark",
        [2] = "shark9",
        [3] = "Shark"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Shark:NewButton("Shark Freeze", function()
    local args = {
        [1] = "Shark",
        [2] = "shark10",
        [3] = "Shark"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

ClownFish:NewButton("||Clown Fish||", function()
    print("s")
end)

ClownFish:NewButton("Clown Fish Futuristic", function()
    local args = {
        [1] = "Clownfish",
        [2] = "clownfish6",
        [3] = "Clownfish"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

ClownFish:NewButton("Clown Fish Futuristic 2", function()
    local args = {
        [1] = "Clownfish",
        [2] = "clownfish7",
        [3] = "Clownfish"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

ClownFish:NewButton("Clown Fish Clown", function()
    local args = {
        [1] = "Clownfish",
        [2] = "clownfish8",
        [3] = "Clownfish"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

ClownFish:NewButton("Clown Fish Emerald", function()
    local args = {
        [1] = "Clownfish",
        [2] = "clownfish9",
        [3] = "Clownfish"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

ClownFish:NewButton("Clown Fish Diamond", function()
    local args = {
        [1] = "Clownfish",
        [2] = "clownfish10",
        [3] = "Clownfish"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Orca:NewButton("||Orca||", function()
    print("s")
end)

Orca:NewButton("Orca", function()
    local args = {
        [1] = "Orca",
        [2] = "orca1",
        [3] = "Orca"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Orca:NewButton("Orca Aqua", function()
    local args = {
        [1] = "Orca",
        [2] = "orca2",
        [3] = "Orca"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Crocodile:NewButton("||Crocodile||", function()
    print("s")
end)

Crocodile:NewButton("Crocodile Islands", function()
    local args = {
        [1] = "Crocodile",
        [2] = "crocodile6",
        [3] = "Crocodile"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Crocodile:NewButton("Crocodile Crozen", function()
    local args = {
        [1] = "Crocodile",
        [2] = "crocodile7",
        [3] = "Crocodile"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Crocodile:NewButton("Crocodile Pink", function()
    local args = {
        [1] = "Crocodile",
        [2] = "crocodile8",
        [3] = "Crocodile"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Crocodile:NewButton("Crocodile Blue", function()
    local args = {
        [1] = "Crocodile",
        [2] = "crocodile9",
        [3] = "Crocodile"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Crocodile:NewButton("Crocodile Magma", function()
    local args = {
        [1] = "Crocodile",
        [2] = "crocodile10",
        [3] = "Crocodile"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Axolotl:NewButton("||Axolotl||", function()
    print("s")
end)

Axolotl:NewButton("Axolotl Pink", function()
    local args = {
        [1] = "Axolotl",
        [2] = "axolotl8",
        [3] = "Axolotl"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Axolotl:NewButton("Axolotl Rainbow", function()
    local args = {
        [1] = "Axolotl",
        [2] = "axolotl9",
        [3] = "Axolotl"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Axolotl:NewButton("Axolotl Dreamcore", function()
    local args = {
        [1] = "Axolotl",
        [2] = "axolotl10",
        [3] = "Axolotl"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Axolotl:NewButton("Axolotl Forest", function()
    local args = {
        [1] = "Axolotl",
        [2] = "axolotl11",
        [3] = "Axolotl"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Axolotl:NewButton("Axolotl Magma", function()
    local args = {
        [1] = "Axolotl",
        [2] = "axolotl12",
        [3] = "Axolotl"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Axolotl:NewButton("Axolotl Storm", function()
    local args = {
        [1] = "Axolotl",
        [2] = "axolotl13",
        [3] = "Axolotl"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)

Axolotl:NewButton("Axolotl Frozen Dragon", function()
    local args = {
        [1] = "Axolotl",
        [2] = "axolotl14",
        [3] = "Axolotl"
    }
    game:GetService("ReplicatedStorage").Events.SpawnEvent:FireServer(unpack(args))
end)
