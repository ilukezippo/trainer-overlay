# Trainer Overlay

A lightweight **Windows overlay** for managing and using game trainers with a **controller-friendly UI** (XInput + DirectInput), **system tray support**, and a **JSON-based trainer library**.

> ⚠️ Use responsibly. Intended for **offline / single-player** games. Do not use in competitive/online environments.

---

## Features

- 🎮 **Controller-first navigation**
  - Works with **XInput** (Xbox/ROG Ally) and **DirectInput** (PS4/PS5 via DInput)
  - D-Pad + analog stick navigation, hold-repeat scrolling, and jump scrolling (L1/R1)
- 🧩 **Trainer + cheat library**
  - Trainers are described using a **JSON format** (game name, trainer exe, categories, cheats)
  - Cheats support **Toggle** and **Pulse (Apply)** style actions (and optional value sliders if enabled in your build)
- ☁️ **Download trainers from GitHub**
  - The app reads the `remote_trainers` folder using the GitHub API and downloads `.zip` trainers directly
- 🪟 **Overlay UX**
  - Slide-in overlay animation
  - Always-on-top + borderless overlay window
  - Designed to **not steal focus** (no-activate behavior)
- 🔔 **System tray**
  - Left-click tray icon to open/close overlay
  - Right-click tray icon for menu (Open / Exit)
- 🔊 **Steam-style UI sounds**
  - Open/close/move/select/back audio cues

---

## Controls

### Keyboard
- **Hotkey:** `Shift + Insert` → Toggle overlay
- **Esc:** Close popup (if open) or toggle overlay

### Controller
- **Toggle overlay combo XInput:** `L2 + R2 + L3 + R3`
- **Toggle overlay combo DInput:** `L2 + R2 + Start + Select`
- **Navigate:** D-Pad / Left Stick
- **Select:** `A`
- **Back:** `B`
- **Jump scroll:** `L1 / R1` (jump by 5 items)

---

## Download

Get the latest build from **Releases**:
- **Latest Release:** https://github.com/ilukezippo/trainer-overlay/releases/latest

You can use either the **Installer (SFX)** or the **Portable** version.

---

## Option 1 — Installer (SFX RAR)

1. Download: **`TrainerOverlay_v1.0_installer.exe`** from Releases  
   (this is a self-extracting RAR / installer)
2. Run it as Administrator (recommended).
3. Choose an install folder (example: `C:\TrainerOverlay\`)
4. Launch `Trainer Overlay` Desktop Shortcut

> Windows SmartScreen may warn on first run (common for unsigned apps).  
> Click **More info → Run anyway** if you trust the download source.

---

## Option 2 — Portable

1. Download: **`<YOUR_PORTABLE_FILE_NAME>.zip`** from Releases
2. Extract anywhere (example: `D:\Apps\TrainerOverlay\`)
3. Run `TrainerOverlayExternal.exe`

✅ Portable version keeps everything in the same folder (recommended for handheld PCs like ROG Ally).

---

## Runtime Folder Layout

Make sure these exist next to the exe (or inside the same folder structure):



