# M-S Android App

This repository is now a native Android app built with Kotlin and Jetpack Compose.

## Open in Android Studio

1. Open this folder in Android Studio.
2. Let Android Studio sync the Gradle project.
3. Select the `app` run configuration.
4. Run it on an emulator or Android device.

## Project Structure

- `app/src/main/java/com/ms/app/MainActivity.kt` contains the Compose UI.
- `app/src/main/AndroidManifest.xml` defines the launcher activity.
- `app/build.gradle.kts` contains the Android app configuration and dependencies.

## Requirements

- Android Studio with JDK support
- Android SDK 35 or newer installed through Android Studio

## Build From Terminal

If Gradle and the Android SDK are available on your PATH:

```powershell
gradle :app:assembleDebug
```
