# Defold Tiny-ECS

This project packages the tiny-ecs Lua library into a defold library project. The tiny-ecs version packaged is 1.3-3

## Setup

You can use the extension in your own project by adding this project as a [Defold library dependency](http://www.defold.com/manuals/libraries/). Open your game.project file and in the dependencies field under project add:

https://github.com/britzl/defold-input/archive/refs/heads/master.zip

Or point to the ZIP file of a specific [release](https://github.com/ivanquirino/defold-tiny-ecs/releases).

## Usage

```lua
local tiny = require("tinyecs.tiny")
```

Please refer to the tiny-ecs repository for documentation: https://github.com/bakpakin/tiny-ecs/

Check this example game implemented with tiny-ecs: https://github.com/Insality/shooting_circles

Happy Defolding!

---
