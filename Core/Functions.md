# Core.Functions
Library functions that can only be accessed through the Core and are unable to be imported. These functions may alter your script's environment.


## Core:import
**Core:import([table])**

Inserts given libraries into the environment.

```lua
local Libraries = {"math", "string"}
Core:import(Libraries)
```
