# Patch Notes

A 2D platformer by **Buggy Games YT** where every level is impossible... unless you use glitches. Clip through walls, wall jump, dupe keys, ledge clip, launch off crates, walk under the map, hyper jump, dash through spikes, keep keys after dying. 100 levels randomly generated for every player (their own set, so no memorizing routes), each one long side-scrolling level with up to 5 glitch puzzles in a row (checkpoint at each), with a hidden bug in every level that only shows up after you pause. Then the dev posts patch notes and patches the glitch you used, so you have to find a new one.

▶ **Play in your browser:** https://buggygamesyt.github.io/patchnotes/
📱 **Android:** grab the APK from [Releases](https://github.com/BuggyGamesYT/PatchNotes/releases).

## Controls
- Keyboard: ← → or A/D move, Space/W jump, Shift dash, E grab, P pause
- Touch: on-screen ◀ ▶, JUMP, DASH, GRAB and ⏸

## Project layout
- `web/` – the game (plain HTML + JavaScript, no libraries). `core.js` is the physics, levels and glitches; `index.html` is the screen, controls and menus.
- `android/` – a tiny WebView wrapper that bundles `web/` into an APK. It's built, signed and released by GitHub Actions when a `v*` tag is pushed.

Made by Buggy · [YouTube](https://www.youtube.com/@BuggyGamesYT)
