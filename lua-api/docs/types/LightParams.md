---
layout: default
title: LightParams
parent: Lua API
permalink: lua-api/types/LightParams
---

{% raw %}

# class LightParams





Parameters for lighting

[<a href="https://github.com/beyond-all-reason/spring/blob/b05328576a1478a61eb5fe6b4b9f7a45a367b3d4/rts/Lua/LuaUnsyncedCtrl.cpp#L1514-L1540" target="_blank">source</a>]





## fields


### LightParams.position

```lua
LightParams.position : { pz: number,px: number,py: number }
```




### LightParams.direction

```lua
LightParams.direction : { dz: number,dx: number,dy: number }
```




### LightParams.ambientColor

```lua
LightParams.ambientColor : { green: number,blue: number,red: number }
```




### LightParams.diffuseColor

```lua
LightParams.diffuseColor : { red: number,green: number,blue: number }
```




### LightParams.specularColor

```lua
LightParams.specularColor : { blue: number,green: number,red: number }
```




### LightParams.intensityWeight

```lua
LightParams.intensityWeight : { ambientWeight: number,diffuseWeight: number,specularWeight: number }
```




### LightParams.ambientDecayRate

```lua
LightParams.ambientDecayRate : { ambientBlueDecay: number,ambientGreenDecay: number,ambientRedDecay: number }
```



Per-frame decay of `ambientColor` (spread over TTL frames)


### LightParams.diffuseDecayRate

```lua
LightParams.diffuseDecayRate : { diffuseGreenDecay: number,diffuseRedDecay: number,diffuseBlueDecay: number }
```



Per-frame decay of `diffuseColor` (spread over TTL frames)


### LightParams.specularDecayRate

```lua
LightParams.specularDecayRate : { specularRedDecay: number,specularGreenDecay: number,specularBlueDecay: number }
```



Per-frame decay of `specularColor` (spread over TTL frames)


### LightParams.decayFunctionType

```lua
LightParams.decayFunctionType : { diffuseDecayType: number,specularDecayType: number,ambientDecayType: number }
```



If value is `0.0` then the `*DecayRate` values will be interpreted as linear, otherwise exponential.


### LightParams.radius

```lua
LightParams.radius : number
```




### LightParams.fov

```lua
LightParams.fov : number
```




### LightParams.ttl

```lua
LightParams.ttl : number
```




### LightParams.priority

```lua
LightParams.priority : number
```




### LightParams.ignoreLOS

```lua
LightParams.ignoreLOS : boolean
```






{% endraw %}