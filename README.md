<div align="center">

# 🎵 Membrane

**A modern, lightweight, open-source music player built for Linux, Windows, and Android.**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platforms-Linux%20%7C%20Windows%20%7C%20Android-green.svg)](#platforms)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

*The surface where sound vibrates.*

</div>

---

## 🌊 Overview

**Membrane** is a cross-platform music player designed with speed, privacy, and seamless multi-device experience at its core. Whether you are organizing a massive local FLAC library on your Linux desktop, listening during work on Windows, or playing offline tracks on Android, Membrane provides an intuitive, distraction-free environment.

### ✨ Key Goals & Features
- 🚀 **Cross-Platform:** Consistent, beautiful experience on **Linux**, **Windows**, and **Android**.
- 🪶 **Lightweight & Fast:** Instant startup, low memory footprint, and responsive library indexing.
- 🎧 **High-Fidelity Audio:** Gapless playback, 10-band equalizer, bit-perfect output, and replay gain support.
- 📁 **Local-First & Private:** No telemetry, no forced accounts. Your files stay on your hardware.
- 🎨 **Adaptive Modern UI:** Smooth animations, dynamic color themes (Material You on Android, Libadwaita-inspired dark/light modes on desktop).
- 🔄 **Seamless Sync (Roadmap):** Lightweight local Wi-Fi sync between your PC and Android phone for playlists and play counts.

---

## 📱 Platforms

| Platform | Target Formats | Distribution Target |
| :--- | :--- | :--- |
| **Linux** | Flatpak, AppImage, AUR | Flathub |
| **Windows** | Portable `.zip`, MSIX / Installer | WinGet, GitHub Releases |
| **Android** | APK | F-Droid, GitHub Releases |

---

## 🛠️ Architecture & Tech Stack

> *Tech stack selection in progress. Potential candidates:*
> - **Flutter** (Dart + C++ audio engine via `miniaudio` or `libsoundio`)
> - **Tauri v2** (Rust audio core + web frontend)
> - **Kotlin Multiplatform (KMP) / Compose Multiplatform**

---

## 🚀 Getting Started

### Prerequisites
*(Setup instructions will be added once the base framework is initialized)*

### Cloning the Repository
```bash
git clone https://github.com/abd2k3-debug/membrane.git
cd membrane
```

---

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome!
Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [GNU General Public License v3.0](LICENSE).
