# Trustrium Mining - Android WebView Wrapper

## Professional Build Instructions (No Android Studio Required)

This project is architected for **Cloud CI/CD**. You do not need to install Android Studio to get your APK/AAB.

### Option 1: Automated Build via GitHub Actions (Recommended)
1. Create a new repository on GitHub.
2. Push this source code to the `main` branch.
3. Go to the **Actions** tab in your repository.
4. The build will start automatically.
5. Once finished, download your **APK** or **AAB** from the artifacts section at the bottom of the run page.

### Option 2: Local Command Line Build
If you have Java 17 and Android SDK installed but don't want to use the Android Studio UI:
```bash
chmod +x gradlew
./gradlew assembleRelease
```
The APK will be generated at `app/build/outputs/apk/release/app-release-unsigned.apk`.

## Features
- **Progressive Loading**: Professional horizontal progress bar.
- **Deep Linking**: Handles WhatsApp, Email, and Phone links natively.
- **Security**: ProGuard obfuscation enabled for release builds.
- **Hardware Acceleration**: Enabled for smooth 60FPS web rendering.
- **File Uploads**: Support for gallery and system file picking.
- **Custom Branding**: Fully configurable app icon and theme colors.
