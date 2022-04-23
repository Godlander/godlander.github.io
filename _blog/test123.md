---
layout: default
title:  "test 123"
tags: Minecraft
---

lets try mcfunction highlighting mayb

```mcfunction
execute if score @s blah == @p test run say hi
scoreboard players operation @s blah *= 5 const
setblock ~ ~ ~ minecraft:dirt
summon item ~ ~ ~ {Item:{id:"minecraft:stick",Count:1}}
```

i guess mcfunction doesnt work