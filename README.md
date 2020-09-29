# UI-Animator

A module with useful functions to animate your ROBLOX studio UIs.

To use, you must first put a copy of the module in your game.

Use example:

```
local UiAnimator = require(00000)
local MyUi = script.Parent

UiAnimator(MyUi, "Bounce", 0.2, 0.15) --[[
The last and second last paramter is optional, 
the second last lets you choose what degree the animation should change the ui by,
and the last lets you choose the length of the animation.
]]
```
