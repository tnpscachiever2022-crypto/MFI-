# MFI Progress Report Android app project

This Android Studio project wraps the supplied MFI progress-report HTML in a local Android WebView. It works offline and keeps the original HTML report calculations and interface.

## Build the APK
1. Install Android Studio (latest stable) on a computer.
2. Extract this ZIP file.
3. In Android Studio, choose **Open** and select the `MFIProgressAndroid` folder.
4. Allow Gradle sync and install the Android SDK Platform 35 if prompted.
5. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. The debug APK will be at `app/build/outputs/apk/debug/app-debug.apk`.
7. Transfer that APK to your Android phone and install it. If Android asks, permit installing apps from that source.

Package/application ID: `in.railway.mfiprogress`
Minimum Android version: Android 6.0 (API 23)

Note: This environment has no Android SDK/Gradle build installation, so the APK binary itself could not be compiled here. The complete Android Studio source project is provided for building the APK.
