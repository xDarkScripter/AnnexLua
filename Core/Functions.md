# Core.Functions
Library functions that can only be accessed through the Core and are unable to be imported. These functions may alter your script's environment.


## Core:import
**Core:import(_..._)**

Inserts given libraries into the environment. Unfortunately, if not defined, some syntax highlighters may give a warning for unknown variables.

```lua
Core:import("math", "string")
```
