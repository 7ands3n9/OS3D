# ⚠️ UNMAINTAINED PROJECT NOTICE

**This repository is published solely as a portfolio piece by Lands End Studios Inc.**

This project is completely unmaintained and archived.

- 🚫 **No pull requests** will be reviewed or merged.
- 🚫 **No issues** will be answered.
- 🚫 **No support** or feature updates will be provided.

## You are welcome to fork this repository and modify it under the terms of the GNU GPLv3 license included in this project, but Lands End Studios Inc. will not provide any assistance.

## Launch

### Windows desktop app (recommended)

Open `release`, then double-click **OS3D.exe**. The desktop app starts immediately and displays your Windows system audio in real time.

### Browser fallback

Double-click **index.html** to open the oscilloscope in your default browser. Demo mode works immediately. Browser security rules may require you to approve microphone or system-audio capture.

## Source layout

- `index.html` — complete oscilloscope interface and renderer
- `main.js` — desktop application launcher
- `icon.ico` — OS3D application icon
- `package.json` and `pnpm-lock.yaml` — reproducible desktop build metadata

## Rebuilding the portable app

With Node.js and pnpm installed, run `pnpm install` followed by `pnpm dist`. The finished executable is written to `release/OS3D.exe`.
