# Update
```lua
All Update this Show here.

Add Functions
+ Line
+ Modal
+ KeyBind Toggle UI
```
# Loadstring & Toggle UI
```lua

_G.Settings = {
	UI = {
		Key = Enum.KeyCode.RightControl,
	}
}

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/SixZensED/Discord-Library/main/Library"))()
```
## Create UI Library Window
```lua
local main = Library:create({
	Name = "Xova's Team"
})
```
## Create Tab
```lua
local tab = main:createtab({
	Name = "Tab"
})
```
## Create Section
```lua
local section = tab:createsection({
Name = "Section"
})
```
## Create Page
```lua
local page = section:createpage()
```
## Create Label
```lua
a = page:Label({
	Title = "Xova's Team",
})
-- Functions
-- a:Update("Xova's Team Best UI")
```
## Create Button
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
## Create Toggle
```lua
page:Toggle({
	Title = "Toggle By Xova's Team",
	Default = true,
	callback = function(v)
		print(v)
	end,
})
```
## Create SelectChoice
```lua
page:SelectChoice({
	Item = {"Dark","Sun"},
	Default = "Sun",
	callback = function(v)
		print(v)
	end,
})
```
## Create Dropdown
```lua
b = page:Dropdown({
	Title = "Dropdown",
	Item = {1,2,3,4,5},
	Default = 1,
	callback = function(v)
		print(v)
	end,
})
-- Functions
-- b:Add(math.random(0,555))
-- b:Clear()
```
## Create Slider
```lua
c = page:Slider({
	Title = "Slider",
	Min = 0,
	Max = 500,
	Default = 10,
	Dec = true,
	callback = function(v)
		print(v)
	end,
	
})
-- Functions
-- c:Update(50)
```
## Create Line
```lua
page:Line()
```
## Create Modal
```lua
page:Modal({
	Title = "Modal"
})
```
