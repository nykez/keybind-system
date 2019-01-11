# keybind-system

A simple keybind system.


br_base.keybinds.loadBinds() // Load player binds if they have them saved
br_base.keybinds.saveBinds() // Save the player binds if they have modified values from the defaults.

br_base.keybinds.RegisterBind(strUnique, helpText, enumKey, funcDown, funcUp)

br_base.keybinds.RegisterBind("doSomething", "Using this button will do something.", KEY_G, 
// Button down func
function()
  print("hello world")
end,
// Button up func
function()
  print("hello world")
end)
