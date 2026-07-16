# dmf-mpk
A levilamina mod for minecraft bedrock parkour  
`J` key to open hud editor (default)

## Installation

1. Download and install [LeviLauncher](https://github.com/LiteLDev/LeviLauncher/releases) ([installation guide](https://www.youtube.com/watch?v=Y6wD0sHRYwo))
3. Download the latest release from [Releases](https://github.com/mihiro13/dmf-mpk/releases)
4. Extract the zip file
5. Copy the `dmf-mpk` folder to `mods`

## Commands
prefix: `/mpk`
|Command|Syntax     |Explanation|
|-------|-----------|-----------|
|`check`|`/mpk check [airtime?: int]`|Set position checker tick, omit the argument to toggle position checker|
|`clearlb`|`/mpk clearlb`|Clear landing block|
|`clearpb`|`/mpk clearpb`|Clear pb|
|`color1`|`/mpk color1 [color: string]`|Set label color|
|`color1`|`/mpk color2 [color: string]`|Set value color|
|`config`|`/mpk config`|Open config GUI|
|`is`|`/mpk is`|Open InputChecker Editor GUI|
|`df`|`/mpk df [df: int]`|Set value decimal precision|
|`df`|`/mpk prefix [prefix: string]`|Set prefix|
|`reload`|`/mpk reload`|Reload config|
|`resetdefault`|`/mpk resetdefault`|Reset all setting and label positions|
|`setlb`|`/mpk setlb [type?: hit\|target\|x\|z\|zneo\|]`|Set landing block|
|`setmm`|`/mpk setmm [type?: hit\|target\|x\|z\|zneo\|]`|Set momentum block|
|`setbox`|`/mpk setlb [start: x y z] [end: x y z]`|Set landing box|
|`togglesprint`|`/mpk togglesprint`|Turns togglesprint on/off|
|`os`|`/mpk os <rotation: float>`|Optimize Sensitivity|
|`ss`|`/mpk ss <sensitivity: 0.0 ~ 1.0>`|Set Sensitivity|
