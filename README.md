# Update
```lua
All Update this Show here.

Add Functions
+ Label [ Can Refresh ]
+ Toggle [ Can Set Defualt]
+ Dropdown [ Can Clear , Add ]
+ Button [ Add Mode(Theme) , Auto Size ]
+ Slider [ Can Update ]
+ Select Choice [ Can Set Defualt ]
```
# Loadstring
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/SixZensED/Discord-Library/main/Library"))()
```
# Create UI Library Window
```lua
local main = Library:create({
	Name = "Xova's Team"
})
```
# Create Tab
```lua
local tab = main:createtab({
	Name = "Tab"
})
```
# Create Section
```lua
local section = tab:createsection({
Name = "Section"
})
```
# Create Page
```lua
local page = section:createpage()
```
# Create Label
```lua
a = page:Label({
	Title = "Xova's Team",
})
-- Functions
-- a:Update("Xova's Team Best UI")
```
# Create Button
```lua
page:Button({
	Title = "Refresh Label",
	Mode = "Defualt",
	AutoSize = true,
	callback = function()

	end,
  -- Theme Mode {"Defualt","Delete","Delete Fill"}
})
```
