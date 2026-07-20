# SimpMusic v1.7.1

> Release for v1.7.1. Added support for Windows standalone `.exe` installer.

## ✨ New
- **Windows EXE installer support** — we now package the app as a standalone `.exe` installer (`SimpMusic-1.7.1.exe`) for Windows, simplifying the setup process.

## 🛠️ Installer / packaging
- Version bump **1.7.0 → 1.7.1** (version-code 57 → 58). This flows through to every installer:
  - **Windows** — `SimpMusic-1.7.1.exe` (executable installer) or `SimpMusic-1.7.1-windows-amd64.msix` + `install.bat` (offline sideload, cert bundled)
  - **macOS** — `SimpMusic-1.7.1-mac-aarch64.dmg` and `SimpMusic-1.7.1-mac-amd64.dmg` (drag-to-Applications, volume icon via `wrap-mac-dmg.sh`)
  - **Linux** — `SimpMusic-1.7.1-linux-amd64.AppImage`

## 📦 Install
- **Android**: install the APK, or update via F-Droid / IzzyOnDroid / the in-app updater.
- **Windows**: run the `SimpMusic-1.7.1.exe` installer, or download the `.msix` and run `install.bat`.
- **macOS**: open the `.dmg` and drag SimpMusic to Applications.
- **Linux**: make the `.AppImage` executable (`chmod +x`) and run it.

## 🔗 Pull request
- #2 — `feat(desktop): support Windows EXE installer format`

---
*SimpMusic is a FOSS YouTube Music client. This is a fork release; upstream lives at maxrave-dev/SimpMusic.*
