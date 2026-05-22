# Build APK (Android Studio)

This is a minimal Android wrapper that opens your existing web page inside a WebView.

## Web URL (online)
It loads:
- https://draco-go-89.github.io/text-walk/

## 1) Prerequisites
- Install **Android Studio**
- Install Android SDK (Android Studio usually handles this)

## 2) Open the project
- Open Android Studio
- **File > Open**
- Select folder: `android-apk`

## 3) Build
- In Android Studio: **Build > Build Bundle(s) / APK(s) > Build APK(s)**
- Output APK will be in:
  - `android-apk/app/build/outputs/apk/debug/app-debug.apk`

## 4) Install (optional)
- Connect your phone with USB and enable **Developer options / USB debugging**
- Click **Run** (installs the debug build)

## Notes
- If the WebView shows blank/blocked content, ensure the phone has internet access.
- Android WebView requires the Internet permission (included).

