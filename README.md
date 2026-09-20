# droid-os

A fake desktop OS that runs in the browser — boot screen, desktop icons
(Terminal, Files, Text Editor, Calculator, Settings, System Monitor,
Image Viewer), windows, notifications, and a taskbar clock.

Single-file static site: `index.html` (no build step, no dependencies).

## Run

```sh
python3 -m http.server 8125
# open http://localhost:8125/index.html
```

## Live

https://droid-os.vercel.app

This repo is the source of truth. The Vercel project deploys from it.
