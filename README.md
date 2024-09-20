# proohio_lib

# -----------------------

# how to use

# -----------------------

# 1. first load the lib
```lua
local lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/ChimeraLle/proohio_lib/refs/heads/main/source"))()
```

# 2. create a window
```lua
lib.CreateWindow("ExploitName")
```

# 3. create a tab
```lua
lib.CreateTab("image")
```

# 4. create a label
```lua
lib.CreateLabel("Text of Label")
```

# 5. create a button
```lua
lib.CreateButton({"Text of Button", function()
	print("prints when button clicked!")
end})
```

# 6. create a input
```lua
lib.CreateInput({"Text of Input", function(input)
	print("The Input Was: " .. input)
end})
```

# 7. create a toggle
```lua
lib.CreateToggle({"Text of Toggle", false, function(Boolean)
	if Boolean then
		print("Bool Is True")
	else
		print("Bool Is False")
	end
end})
```
