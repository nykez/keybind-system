
Release:https://github.com/nykeztv/keybind-system/releases

# keybind-system

A simple keybind system. This is a pure cilent-side implementation. I wrote this for a side project, and thought maybe, it would be useful to somebody.



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
