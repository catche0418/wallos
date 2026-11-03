# WallOS

Calm wall-mounted calendar that behaves like a tiny operating system for an iPad mini (or any tablet).

**Phase 1** single-file implementation — no build step, no dependencies.

## Live demo

Once GitHub Pages is enabled (Settings → Pages → Deploy from branch `main` / root):

**https://catche0418.github.io/wallos/**

## Install on iPad

1. Open the Pages URL (or this repo’s `index.html`) in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Launch only from the home-screen icon (removes browser chrome).
4. Settings → Display & Brightness → **Auto-Lock → Never**.
5. Optionally turn on **Guided Access** for a locked kiosk experience.

> Opening the file from the Files app preview shows the iPadOS toolbar on every tap. Always use the home-screen icon.

## Features (Phase 1)

- Ambient / Home / App shell with zoom transitions
- Today, Month, Countdown and Tasks widgets
- Full Calendar app (Month + Day views, event editor, quick-add, long-press actions)
- Tasks & Countdowns apps
- Clock app
- Settings (Display + Data)
- Theme (light/dark), text size, 12/24h, week start
- localStorage persistence + backup import/export
- Night mode & ambient timeout skeleton
- Strict ES5 + iOS 12 Safari-safe CSS

## License

MIT — use freely on your wall.
