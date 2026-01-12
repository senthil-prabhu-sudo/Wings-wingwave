# WingWave Music Player

[![Download APK](https://img.shields.io/badge/Download-APK-blue.svg)](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases/latest/download/app-release.apk)
[![Version](https://img.shields.io/badge/Version-2.0-green.svg)](https://github.com/senthil-prabhu-sudo/Wings-wingwave/releases)
[![Min SDK](https://img.shields.io/badge/Min%20SDK-23-orange.svg)]()

A sleek and powerful Android music player that brings your local music collection to life with modern design and advanced playback features.

## ✨ Features

### 🎵 Core Playback
- **Seamless Audio Playback**: High-quality audio playback using ExoPlayer
- **Background Service**: Continuous music playback even when the app is minimized
- **Embedded Album Art**: Automatic display of album artwork from audio files
- **Real-time Progress**: Live seekbar updates and time display

### 🎛️ Playback Controls
- **Mini Player**: Compact bottom player for quick controls
- **Full-Screen Player**: Immersive now-playing experience
- **Play/Pause/Next/Previous**: Standard playback controls
- **Seekbar Control**: Intuitive scrubbing through tracks

### 🔄 Advanced Features
- **Shuffle Mode**: Random playback order with visual indicator
- **Repeat Mode**: Single track or playlist repeat options
- **Playback Speed**: Adjust speed from 0.5x to 2x (0.5x, 1x, 1.5x, 2x)
- **Volume Control**: Built-in volume slider in full-screen player

### 📱 User Interface
- **Search Functionality**: Find songs by title or artist instantly
- **Fast Scroller**: Alphabetical quick navigation through large libraries
- **Material Design**: Modern, intuitive interface following Android design guidelines
- **Swipe Gestures**: Swipe down to hide mini player
- **Dark/Light Themes**: Adaptive theming support

### 🔒 Privacy & Permissions
- **Minimal Permissions**: Only requests necessary audio access permissions
- **No Internet Required**: Fully offline music player
- **Secure Storage Access**: Respects Android's scoped storage guidelines

## 📥 Installation

### Option 1: Direct APK Download (Recommended)
1. Click the "Download APK" button above
2. Download the latest release APK file
3. On your Android device, enable "Install from Unknown Sources" in Settings
4. Open the downloaded APK file and install

### Option 2: Build from Source
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/WingsMusicPlayer.git
   ```
2. Open the project in Android Studio
3. Build and run on your device or emulator

### Requirements
- Android 6.0 (API 23) or higher
- Storage permission for accessing music files

## 📸 Screenshots

*Add screenshots of your app here*

- Main song list with search
- Full-screen player with controls
- Mini player interface

## 🛠️ Build Instructions

### Prerequisites
- Android Studio Arctic Fox or later
- JDK 17 or higher
- Android SDK API 36

### Building
1. Open the project in Android Studio
2. Wait for Gradle sync to complete
3. Select `Build > Build Bundle(s)/APK(s) > Build APK(s)`
4. Find the APK in `app/release/app-release.apk`

### Dependencies
- **ExoPlayer**: For robust media playback
- **Glide**: For efficient image loading and caching
- **Material Components**: For modern UI components

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔧 Technical Details

- **Language**: Java
- **Architecture**: MVVM-inspired structure
- **Media Framework**: Android Media3 (ExoPlayer)
- **UI Framework**: AndroidX, Material Design 3
- **Minimum SDK**: API 23 (Android 6.0)
- **Target SDK**: API 36 (Android 14)

## 📞 Support

If you encounter any issues or have suggestions:
- Open an issue on GitHub
- Check the existing issues for similar problems
- Provide detailed information about your device and Android version

---

**Enjoy your music with WingWave! 🎧**
