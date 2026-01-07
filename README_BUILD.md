# QR Master (Android Project)

## Prerequisites
1. JDK 17 or higher installed.
2. Android SDK installed.

## Build Instructions
Open a terminal in the project root folder and run:

```bash
chmod +x gradlew
./gradlew assembleDebug
```

The APK will be generated at:
`app/build/outputs/apk/debug/app-debug.apk`

## Features
- **Modern UI:** Built with Jetpack Compose and Material 3.
- **QR Scanning:** Fast CameraX integration with ZXing decoding.
- **QR Generation:** Custom color QR code generation.
- **Theming:** Dark mode support and Arabic localization UI.