if game.PlaceId == 4791329820 then

local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = OrionLib:MakeWindow({Name = "Zetra Cheetz", HidePremium = false, SaveConfig = true, ConfigFolder = "ZetraCfg", IntroEnabled = false,})

--Valores
_G.AutoClick = true



--Funcoes

function AutoClick()
    while _G.AutoClick == true do
        local Event5= game:GetService("ReplicatedStorage").Remotes.Combat5
        Event5:FireServer()
        local Event4 = game:GetService("ReplicatedStorage").Remotes.Combat4
        Event4:FireServer()
        local Event3 = game:GetService("ReplicatedStorage").Remotes.Combat3
        Event3:FireServer()
        local Event2 = game:GetService("ReplicatedStorage").Remotes.Combat2
        Event2:FireServer()
        local Event = game:GetService("ReplicatedStorage").Remotes.Combat
        Event:FireServer()
        wait(.00000000000000000000000000000000000000000000001)
        end
end
