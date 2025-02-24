# ECO

Simple external crosshair overlay, requires .Net v4.5

In some games like CSGO, this will work on fullscreen-windowed/windowed mode only.
Whereas in games like UT2004, all display modes will be supported.

Download [here](https://github.com/tweakrrr/ECO/releases).

## Features

- [x] custom sized crosshair
- [x] choose crosshair color(for primary crosshair only)
- [x] change crosshair transparency
- [x] display crosshair on selected process
- [x] entirely in C# (no DirectX dependencies)
- [x] supports custom crosshair option(png/jpeg images - other formats experimental)
- [x] set the crosshair offset manually(__Hotkey : "-"(Minus key) [Movement: Arrows/WASD]__)
- [x] saving of configuration based on the target game
- [x] toggle display of crosshair while in-game using "=" key
- [x] DPI aware

#### Note : Configs are stored at `%APPDATA%\CrosshairOverlay` folder. Delete files to hard-reset the config.

### Crosshair Scaling by lower values

To make minor adjustments, focus the slider by clicking it, then press the buttons left/right arrow keys(or up/down) 
It should change by 0.01 points in that case, whereas clicking on either side of the slider with mouse should change by 0.1 points
