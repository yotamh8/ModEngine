# Accessibility Statement / הצהרת נגישות

Version 1.0.0 - updated 2026

ModEngine is meant to be usable by everyone - including players who use it *because* of a disability, to slow a
game down, make it easier, or skip parts they can't physically play. We aim to meet the **Web Content
Accessibility Guidelines (WCAG) 2.1, level AA**, the basis of the Israeli standard **IS 5568**, for the app's
own window.

## What we did

- **Keyboard only**: everything can be reached with Tab / Shift+Tab and used with Enter or Space. Escape closes
  dialogs and menus. Dialogs keep the keyboard focus inside them and return it where it was when they close.
- **Visible focus**: the element that has the keyboard focus always has a clear outline.
- **Screen readers** (Windows Narrator, NVDA, JAWS): buttons, switches and fields have names; on/off switches
  report their state; dialogs are announced as dialogs; notifications are read out automatically, errors right
  away.
- **Contrast**: text meets the WCAG AA contrast ratio (4.5:1 for normal text) against its background.
- **Zoom**: Ctrl and + / Ctrl and - / Ctrl and 0 make everything bigger or smaller.
- **Less motion**: if Windows' "Animation effects" setting is off, ModEngine turns its animations off too.
- **Not colour alone**: states are shown with words as well as colour ("On" / "Off", "Lock", warnings in text).
- **Hotkeys**: every mod can get a keyboard hotkey that works inside the game.

## Known limitations

- Values inside the games themselves, and in-game overlays such as Creature ESP, are drawn by the game; their
  accessibility depends on the game.
- Some technical views in Advanced mode (memory addresses, byte patterns, the Objects browser) are dense tables
  meant for experienced users; they work with the keyboard and screen readers but are not simplified.
- The "Record & guess" helper relies on you playing the game while it records.

## Tell us about a problem / פנייה בנושא נגישות

If something in ModEngine is hard or impossible for you to use, please tell us: open an issue at
https://github.com/yotamh8/ModEngine/issues and describe what you tried, which assistive technology you use, and what happened. We aim to
answer within 14 days.

אם נתקלתם בבעיית נגישות ב-ModEngine, נשמח לשמוע: פתחו פנייה בכתובת https://github.com/yotamh8/ModEngine/issues ותארו מה ניסיתם
לעשות, באיזו טכנולוגיה מסייעת אתם משתמשים ומה קרה. אנו שואפים להשיב תוך 14 יום.
