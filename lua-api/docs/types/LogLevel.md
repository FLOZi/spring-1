---
layout: default
title: LogLevel
parent: Lua API
permalink: lua-api/types/LogLevel
---

{% raw %}

# alias LogLevel
---



```lua
(alias) LogLevel = (integer|"debug"|"info"|"notice"|"warning"|"deprecated"|"error"|"fatal")
    | integer
    | "debug" -- LOG.DEBUG
    | "info" -- LOG.INFO
    | "notice" -- LOG.NOTICE (engine default)
    | "warning" -- LOG.WARNING
    | "deprecated" -- LOG.DEPRECATED
    | "error" -- LOG.ERROR
    | "fatal" -- LOG.FATAL

```




[<a href="https://github.com/beyond-all-reason/spring/blob/b05328576a1478a61eb5fe6b4b9f7a45a367b3d4/rts/Lua/LuaUtils.cpp#L1430-L1440" target="_blank">source</a>]


{% endraw %}