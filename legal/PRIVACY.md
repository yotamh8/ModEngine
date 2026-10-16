# ModEngine Privacy Policy

Version 1.0.0 - 2026

**Short version: ModEngine collects nothing. It has no accounts, no analytics, no ads and no online features,
and it never sends anything about you or your games over the internet. Everything it remembers stays on your PC.**

## What ModEngine stores, and where

All of it is on your own computer, in your user folder under `.modengine`:

| File / folder | What it is |
|---|---|
| `settings.json` | Your choices: Simple/Advanced mode, tips on/off, favorites, the games you modded (name, exe location, when last played), and which version of the Terms you accepted |
| `games\` | The mods you saved for each game: names, hotkeys, groups, values |
| `icons\` | Game icons taken from the game's own exe, so the library loads fast |
| `webview\` | The app window's own browser storage (Microsoft Edge WebView2) |
| `unity\`, `renpy\`, `godot\` | Helper files ModEngine loads into those games, and small port files so it can reconnect |
| `logo.ico` | The app icon |

For Godot games, ModEngine also adds one line to the game's `override.cfg` (see the Terms of Use, section 5).

## What ModEngine does not do

- It does not create an account or ask for your name, email or any personal information.
- It does not send telemetry, crash reports, usage statistics or anything else to us or anyone else.
- It does not show ads or use trackers.
- It does not read your files, browser data or anything outside the games you choose and its own folder.
- The only network connections it makes are to its own helpers on your computer (address 127.0.0.1); nothing
  leaves your PC.

## Microsoft Edge WebView2

ModEngine's window is drawn by Microsoft Edge WebView2, a part of Windows. WebView2 is Microsoft software covered
by Microsoft's own privacy statement and your Windows diagnostic-data settings. ModEngine does not load any web
pages from the internet in it.

## Removing your data

- One game: open it in ModEngine, "..." menu > "Forget this game". This deletes its saved mods and icon and,
  for Godot games, removes the `override.cfg` line.
- Everything: quit ModEngine and delete the `.modengine` folder in your user folder
  (`%USERPROFILE%\.modengine`). Deleting the ModEngine program does not remove this folder automatically.

## Children

ModEngine does not knowingly collect information from anyone, including children, because it collects no
information at all.

## Contact and changes

If we ever change how ModEngine handles data, this policy will be updated and shown in the app before the
change applies. Questions: https://github.com/yotamh8/ModEngine/issues
