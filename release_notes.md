# SimpMusic v1.7.0

> Release for v1.7.0. Built installers (`.exe`, `.msix`, `.dmg`, `.AppImage`) and the Android APK.

## ✨ New
- **Named color palettes** — a new **Palette** option under *Settings → Theme color*. Pick from ten curated, named seeds (Ocean, Sunset, Forest, Lavender, Rose, Amber, Mono, Mint, Berry, Sky) that recolor the entire app in both the AMOLED-dark and neutral-light schemes. Your selection is remembered across restarts and shared between the Android and Desktop apps.

## 🛠️ Installer / packaging
- Version bump **1.6.0 → 1.7.0** (version-code 55 → 57). This flows through to every installer:
  - **Windows** — `SimpMusic-1.7.0.exe` (executable installer) or `SimpMusic-1.7.0-windows-amd64.msix` + `install.bat` (offline sideload, cert bundled)
  - **macOS** — `SimpMusic-1.7.0-mac-aarch64.dmg` and `SimpMusic-1.7.0-mac-amd64.dmg` (drag-to-Applications, volume icon via `wrap-mac-dmg.sh`)
  - **Linux** — `SimpMusic-1.7.0-linux-amd64.AppImage`

## 📦 Install
- **Android**: install the APK, or update via F-Droid / IzzyOnDroid / the in-app updater.
- **Windows**: run the `SimpMusic-1.7.0.exe` installer, or download the `.msix` and run `install.bat`.
- **macOS**: open the `.dmg` and drag SimpMusic to Applications.
- **Linux**: make the `.AppImage` executable (`chmod +x`) and run it.

## 🔗 Pull request
- #1 — `feat(theme): add named color palettes + v1.7.0 release`

---
*SimpMusic is a FOSS YouTube Music client. This is a fork release; upstream lives at maxrave-dev/SimpMusic.*
