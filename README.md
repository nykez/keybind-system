# keybind-system

A simple keybind system. This is a pure cilent-side implementation. 


```keybinds.loadBinds()``` // Load player binds if they have them saved

```keybinds.saveBinds()``` // Save the player binds if they have modified values from the defaults.


```keybinds.RegisterBind(strUnique, helpText, enumKey, funcDown, funcUp)```

```lua
keybinds.RegisterBind("doSomething", "Using this button will do something.", KEY_G, 
// Button down func
function()
  print("hello world")
end,
// Button up func
function()
  print("hello world")
end)
```
