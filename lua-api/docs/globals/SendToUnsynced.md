---
layout: default
title: SendToUnsynced
parent: Lua API
permalink: lua-api/globals/SendToUnsynced
---

{% raw %}

# global SendToUnsynced


```lua
function SendToUnsynced(...: (nil|boolean|number|string))
```
@param `...` - Arguments. Typically the first argument is the name of a function to call.







Invoke `UnsyncedCallins:RecvFromSynced` callin with the given arguments.

[<a href="https://github.com/beyond-all-reason/spring/blob/b05328576a1478a61eb5fe6b4b9f7a45a367b3d4/rts/Lua/LuaHandleSynced.cpp#L1966-L1972" target="_blank">source</a>]
 See: UnsyncedCallins:RecvFromSynced



{% endraw %}