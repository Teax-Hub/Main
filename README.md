# Teax Hub
Made by Teax#6287  
This github is not managed by the real Teax.  
Join the Discord Server: https://discord.com/invite/m98YJKkafz

# Updated 12/31/20
*Works on v5.5.1b*  
Unpatched  
Bug Fixes  
Performance Improvements  

This loadstring will be updated whenever Teax releases an update.  

# Phantom Forces
The loadstring DOES NOT have the settings. Make sure to copy everything below.  
Change the settings to your liking.  
```lua
getgenv().Settings = {
  SilentAim = {
    SilentAim = true,
    VisibleCheck = true,
    TargetBone = "Torso", -- "Head" or "Torso" or "Random"
    Target = "ClosestToMouse" -- "ClosestToPlayer" or "ClosestToPlayer"
  },
  Esp = {
    Boxes = true,
    Tracers = false,
    Names = true,
    Distance = true,
    HealthBars = true,
    Chams = true,
    Color = Color3.fromRGB(255, 25, 25)
  }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/Teax-Hub/Main/main/Phantom%20Forces.lua", true))()
```
