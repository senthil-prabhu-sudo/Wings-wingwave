# 🪽 WingsPlayer (WingWave)

<div align="center">

![Platform](https://img.shields.io/badge/Platform-Android%20(API%2023+)-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Build](https://img.shields.io/badge/Build-Universal%20APK-02569B?style=for-the-badge&logo=flutter&logoColor=white)
[![Latest Release](https://img.shields.io/github/v/release/senthil-prabhu-sudo/Wings-wingwave?style=for-the-badge&color=blue&label=Release)](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

<br/>

**A sleek, modern, and high-performance all-in-one Audio & Video Media Player for Android.**

[**📥 Download Latest APK**](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest/download/WingsPlayer-universal.apk) • [**✨ Features**](#-features) • [**📥 Installation Guide**](#-installation-guide) • [**📱 System Requirements**](#-system-requirements)

</div>

---

## 📖 Overview

**WingsPlayer** (developed under the *Wings / WingWave* brand) is a feature-rich, high-fidelity media player designed to deliver an exceptional audio and video playback experience on Android devices. Powered by industry-standard playback engines (`just_audio` and `media_kit`), WingsPlayer seamlessly manages local audio/video libraries, provides advanced media editing utilities, features a private vault, and offers a clean, fluid Material Design interface.

---

## ✨ Features

### 🎵 Advanced Audio Playback
- **High-Fidelity Audio**: Smooth, crisp playback supporting standard formats (MP3, AAC, FLAC, WAV, M4A, OGG).
- **Background Playback**: Continuous background listening with system lock-screen and notification controls powered by `just_audio_background`.
- **Custom Equalizer**: Interactive multi-band equalizer with rich frequency presets and visualizer animation.
- **Queue & Playlists**: Reorderable playback queues, shuffle, repeat (all/single), and intuitive custom playlist creation.
- **Sleep Timer**: Built-in sleep timer with customizable duration to pause playback automatically.

### 🎬 Next-Gen Video Player
- **Hardware-Accelerated Engine**: Ultra-smooth video rendering powered by `media_kit` (libmpv).
- **Picture-in-Picture (PiP)**: Keep videos playing in a floating window while multitasking.
- **Intuitive Gestures**: Swipe controls for vertical volume, brightness adjustment, and horizontal seek scrubbing.
- **Subtitles & Audio Tracks**: Easy subtitle selection and multi-audio track switching.
- **Variable Playback Speed**: Finely tune playback speeds from **0.25x** up to **2.0x**.

### 🛠️ Built-in Media Tools
- **Audio Extractor**: Extract audio tracks from video files directly on device.
- **Audio Trimmer**: Precision trimming to create custom clips or ringtones.
- **Video Trimmer**: Fast, lossless video clipping and export.
- **Recent Exports**: Dedicated manager to view, play, and share exported media.

### 🔒 Secure Privacy Vault
- Hide sensitive videos and audio tracks in a password-protected vault kept secure from the device gallery.

### 🌐 Online Music & Discovery
- Stream and explore online tracks with metadata caching and search functionality.

### 🎨 Modern & Responsive Design
- Clean Material Design 3 interface with adaptive dark/light themes.
- Grid and list views for media files, folders, and albums.
- Fast search and instantaneous filtering across your entire library.

---

## 📱 System Requirements

| Specification | Details |
| :--- | :--- |
| **Operating System** | Android 6.0 (Marshmallow, API 23) or higher |
| **Target SDK** | Android 15 ready (API 36) |
| **Package Architecture** | Universal APK (`arm64-v8a`, `armeabi-v7a`, `x86_64`) |
| **App Size** | ~96.9 MB (Self-contained media engines included) |

---

## 📥 Installation Guide

### Option 1: Direct APK Download (Recommended)
1. Click the button below to download the latest universal release package:
   <br/><br/>
   <a href="https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest/download/WingsPlayer-universal.apk">
     <img src="https://img.shields.io/badge/Download_APK-WingsPlayer-2ea44f?style=for-the-badge&logo=android&logoColor=white" alt="Download APK" />
   </a>
   <br/><br/>
2. Once the download finishes, tap the downloaded APK notification or open it from your file manager.
3. If prompted by Android, grant permission to **"Install Unknown Apps"** for your browser or file manager.
4. Tap **Install** and enjoy WingsPlayer!

### Option 2: Browse GitHub Releases
Visit the [**GitHub Releases Page**](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest) to inspect version notes, SHA-256 checksums, and previous releases.

---

## 🔒 Permissions & Privacy

WingsPlayer is designed with privacy and security in mind:
- **Audio & Video Access**: Needed exclusively to scan and play your local music and video files.
- **Foreground Service**: Needed to maintain audio playback when the app is in the background or device screen is locked.
- **No Unnecessary Telemetry**: Your local media stays strictly on your device.

---

## 🛠️ Technical Overview

- **Core Framework**: Flutter (Dart)
- **Audio Engine**: `just_audio` with `just_audio_background` MediaSession integration
- **Video Engine**: `media_kit` (high-performance libmpv hardware decoding)
- **Design System**: Material Design 3

---

## 📞 Support & Feedback

If you encounter any issues, have feature suggestions, or need assistance:
- Submit an issue on the [**GitHub Issues Page**](https://github.com/senthil-prabhu-sudo/Wings-wingwave/issues).
- Please include your device model and Android version when reporting a bug.

---

## 👤 Author

Developed by **[senthil-prabhu-sudo](https://github.com/senthil-prabhu-sudo)**

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
