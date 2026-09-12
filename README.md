# NIKHILVERSE Android App

Ready-to-build Android Studio project for the NIKHILVERSE website.

- App name: NIKHILVERSE
- Package: com.nikhilverse.app
- Version: 1.0 (1)
- Website: https://nikhilverse.onrender.com/

## Build APK
1. Install Android Studio.
2. Open this folder as an existing Gradle project.
3. Let Gradle sync/download the Android Gradle Plugin.
4. Select **Build > Build App Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK will be under `app/build/outputs/apk/debug/`.

For a Play Store release use **Build > Generate Signed App Bundle / APK** and create a signing key.

## Important
The app is a WebView wrapper, so the website/backend remain on Render. Keep the Render site live and HTTPS enabled.
