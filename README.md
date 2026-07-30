# Vitrine

**One page, on display.** A tray-only kiosk webview for Windows: a frameless
WebView2 window that shows one page, with no taskbar button and no window
chrome. Point it at a dashboard, a smart-home panel, a Proxmox console — it
sits on a wall display or in a corner of your desk like a piece behind glass.

### [Download Vitrine](https://leifclaesson.github.io/vitrine/)

Or grab the bundle straight from
[the latest release](https://github.com/leifclaesson/vitrine/releases/latest).
Windows 10 and 11, 64-bit, signed exe.

## What it does

- Frameless, taskbar-free kiosk window for any URL — dashboards, panels, consoles
- A GUI configurator (`vitrine --configure`) to set up and manage kiosks without
  hand-editing JSON
- Per-kiosk favicon fetch, baked into the shortcut and window/tray icon
- Dark/light theming, accent colours, an overlay HUD (zoom, lock, quit) that
  fades out of the way
- Offline retry with a local error page when the target host drops
- Periodic auto-reload to keep a long-running dashboard's memory from creeping
- No installer — portable folder app, unzip and run

## About this repository

This repo is the **public face**: the landing page and the releases. The source
code is not public and is not included. Vitrine is free to use, for personal
and commercial purposes alike, under the terms in [LICENSE.txt](LICENSE.txt).

Please link people here rather than mirroring the download, so nobody ends up
running a stale copy.

Part of a small family of sharp little tools. The rest are on their way.
