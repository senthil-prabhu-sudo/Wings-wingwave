# 🪽 WingsPlayer (WingWave)

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-3.44+-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.12+-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-API%2023+-3DDC84?style=for-the-badge&logo=android&logoColor=white)
[![Latest Release](https://img.shields.io/github/v/release/senthil-prabhu-sudo/Wings-wingwave?style=for-the-badge&color=blue&label=Release)](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

<br/>

**A sleek, modern, and high-performance all-in-one Audio & Video Media Player for Android.**

[**📥 Download Latest APK**](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest/download/WingsPlayer-universal.apk) • [**✨ Features**](#-features) • [**🚀 Getting Started**](#-getting-started) • [**🛠️ Tech Stack**](#-tech-stack)

</div>

---

## 📖 Overview

**WingsPlayer** (developed under the *Wings / WingWave* brand) is a feature-rich, high-fidelity media player designed to deliver an exceptional audio and video playback experience. Built with **Flutter** and powered by industry-standard playback engines (`just_audio` and `media_kit`), WingsPlayer seamlessly manages local audio/video libraries, provides advanced media editing utilities, features a privacy vault, and offers a clean, fluid Material Design interface.

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
- **Intuitive Gestures**: Swipe controls for vertical volume, brightness adjustment, and horizontal seek scrub.
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

| Specification | Requirement |
| :--- | :--- |
| **Operating System** | Android 6.0 (Marshmallow, API 23) or higher |
| **Target SDK** | Android 15 ready (API 36) |
| **Architectures** | Universal APK (`arm64-v8a`, `armeabi-v7a`, `x86_64`) |
| **Permissions** | Audio & Video read permissions for local media scanning |

---

## 📥 Installation

1. Go to the [**Releases Page**](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest).
2. Download the latest **`WingsPlayer-universal.apk`**.
3. On your Android device, allow installation from unknown sources if prompted.
4. Open the downloaded file and install WingsPlayer.

---

## 🛠️ Tech Stack & Architecture

- **Framework**: [Flutter](https://flutter.dev) (Dart 3.x)
- **State Management**: [Provider](https://pub.dev/packages/provider)
- **Media Engines**:
  - [media_kit](https://pub.dev/packages/media_kit) (libmpv for high-performance video & audio decoding)
  - [just_audio](https://pub.dev/packages/just_audio) & [just_audio_background](https://pub.dev/packages/just_audio_background)
  - [video_player](https://pub.dev/packages/video_player)
- **Storage & State**: `shared_preferences`, `path_provider`
- **Device Integration**: `wakelock_plus`, `screen_brightness`, `permission_handler`, `share_plus`

---

## 🚀 Getting Started (Build from Source)

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.44.0 or later)
- Android SDK (API 36 recommended)
- Java Development Kit (JDK 17 or later)

### Build Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/senthil-prabhu-sudo/Wings-wingwave.git
   cd Wings-wingwave
   ```

2. **Install Flutter dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run in Debug Mode:**
   ```bash
   flutter run
   ```

4. **Build Universal Release APK:**
   ```bash
   flutter build apk --release
   ```
   The generated APK will be located at `build/app/outputs/flutter-apk/app-release.apk`.

---

## 🤝 Contributing

Contributions, feedback, and suggestions are welcome!
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/MyFeature`)
3. Commit your changes (`git commit -m 'feat: Add MyFeature'`)
4. Push to the branch (`git push origin feature/MyFeature`)
5. Open a Pull Request

---

## 👤 Author

Developed by **[senthil-prabhu-sudo](https://github.com/senthil-prabhu-sudo)**

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
