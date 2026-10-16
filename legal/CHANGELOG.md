# What's new

## 1.0.0 - first official release

**Mod games you own, offline**
- Game library with real game icons, favorites, and "Forget this game".
- Ready-made mods for supported games; your own finds are remembered per game, with hotkeys, favorites,
  categories and groups (change several values at once).
- Find values: guided search ("it went up / down / didn't change"), likely range, negative numbers, and
  "Find the real one" for games that keep hidden copies.
- Record & guess: just play, and ModEngine guesses which values are health, stamina, money and ammo.
- Scanner (Advanced): numbers, text, byte patterns and groups of values, with filters.

**Engines**
- Unreal Engine 4.25+ and UE5: values by name, game speed, position and teleport (save spot / go back),
  inventory items. No injection.
- Godot 3 and 4: values by name through a one-line `override.cfg` helper; game speed, position, inventory.
- Unity (Mono), Ren'Py and Java games through in-game helpers.

**Safety**
- Warns you when a game is running anti-cheat (it doesn't hide from it - using it there is your risk).
- Never reads or changes purchase or membership values.
- Fully offline: no accounts, no telemetry, nothing sent over the internet.

**App**
- Modern window with its own title bar, tray icon (mods keep working while it's hidden), one-file portable exe.
- Keyboard and screen-reader support, zoom, reduced motion, WCAG AA contrast.
- Inter and Outfit fonts built in - nothing is downloaded.
