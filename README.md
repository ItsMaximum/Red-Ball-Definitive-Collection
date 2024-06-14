# Red Ball - Definitive Collection

This is a collection of the best versions of every single Red Ball flash game, including various mods, IGT Editions, practice hacks, and TAS hacks

## ActiveX Flash Player (Windows Only)
ActiveX Flash Player is a wrapper created by Maximum that is powered by the included .ocx plugin. This wrapper adds some features over the standard Flash player, including a change quality hotkey and a window size modifier. It also provides access to 64-bit Flash 11.5, which features improved performance compared to versions 11.7 and beyond and is necessary to perform some strategies in the Red Ball games. If you need 32-bit Flash for whatever reason, it is recommended to use the Flash Player 11.4 executable included in the "Other Flash Players" folder. However, keep in mind that the autosplitter will only work when using the ActiveX player.
### [ActiveX Flash Player Setup Tutorial](https://youtu.be/fEYReWZnD-E)

### Keybinds
- **Ctrl + Shift + F** - Enable / Disable Fullscreen
- **Ctrl + Shift + Q** - Cycle Quality Option (Low, Medium, High)
- **Ctrl + Shift + K** - Open Window Size Dialog (Disabled in Fullscreen)
- **Ctrl + Shift + P** - Trigger the Flash "Play" Function (May be Needed to Start Some Games)
- **Ctrl + Shift + Right / Left** - Cycle Through the Red Ball Games (Full Series.exe only)

## Usage
The provided .swf files can be opened in multiple ways, but it is recommended to do the following:

1. Right-click one of the .swf files
2. Select Properties
3. Click "Change"
4. Browse for the provided "ActiveX Flash Player.exe"
5. Select "Apply" and then "Ok"

If you find that the game lags too much at a higher resolution, try setting the quality to medium or low and/or reduce your monitor resolution.


## Autosplitting
Maximum created a unified autosplitter which supports the individual and multi-game categories for all of the mainline Red Ball games. Side game support is planned to be added later. The autosplitter mirrors the in-game timers and automatically starts, splits, and resets when needed. To activate the autosplitter, select the applicable game in the "Edit Splits" menu of [LiveSplit](https://livesplit.org/downloads/) and click the "Activate" button. The "Settings" menu contains the following options:

#### Freeze after Levels 12 and 20 in Red Ball 1 and 2
- By default, the timer will freeze after reaching the last split or after completing the last level in any of the games, whichever comes first. If you are running Red Ball 1-3 Any% or Full Series Any%, you need the timer to freeze after Level 12 in Red Ball and Level 20 in Red Ball 2 to properly transition between games.
#### Only split after finishing each game
- While you should have a split for each level when running the multi-game categories, if you only have a split for each game, then this is the option for you.
#### Start the timer upon entering any level
- Normally, the timer only starts once the in-game timer activates in Level 1 in any of the games. This prevents the timer from starting over and over again if you decide to practice for a bit. However, if you are running either of the bonus level categories, then you need to enable this option to get the timer to reset and start in levels 13 and 21.

## Issues
- If you have any issues with setting up the ActiveX Flash Player, please ask for help [here.](https://discord.com/channels/669649577846243328/1241932927257018439)
- If you have any issues with setting up the autosplitter, please ask for help [here.](https://discord.com/channels/669649577846243328/1241932927257018439)
- If you find any bugs in the games or the autosplitter, please create an issue on the [GitHub repo.](https://github.com/ItsMaximum/Red-Ball-Definitive-Collection/issues)
- If you want an updated version of a game to be included in the next Definitive Collection release, please open a [pull request](https://github.com/ItsMaximum/Red-Ball-Definitive-Collection/pulls), including the new version as an attachment.