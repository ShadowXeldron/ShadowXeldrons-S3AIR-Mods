# No SHC Splash
The SHC only happens once a year and I don't want to spend it looking at splash text.

### This is not made with the intention of disparaging the Sonic Hacking Contest or any of it's entrants, and I respect the work of those who enter it. This script was simply made to reduce the amount of time you would have to wait before the game starts when using mods that enable the SHC splash.

A simple 5-line script that overrides the Sonic Hacking Contest splash function to replace it with a dummy variable, thus preventing it from functioning and skipping right to the title screen. This is made in anticipation of the time spent at the SHC splash being added to the game's startup sequence adding up significantly over time.

Here's a tip for those on PC, if you add the following code to your config.json (located in your sonic3air_game folder), you'll be able to skip the disclaimer and get into the game even quicker:

```
// Game
"StartPhase": "1", // 0: Disclaimer, 1: Title Screen, 2: Main Menu, 3: In-game (loading a save state)
```
