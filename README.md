# Gemini Web for Android

A sleek, lightweight, privacy-focused Android wrapper for the Google Gemini web experience.

<p align="center">
  <img src="assets/logo.png" alt="Gemini Web Logo" width="128" height="128" />
</p>

## ✨ Highlights

- **Full Gemini Web Experience:** Smooth rendering with support for file attachments and interactive prompts.
- **Privacy & Data Focused:** Zero third-party telemetry, restricted cross-site trackers, and isolated local storage.
- **Lightweight Architecture:** Optimized footprint without bulky native service overhead.
- **Modern Android Support:** Built with modern SDK targets and edge-to-edge system integration.

## 📦 Package Details

- **Package Name:** `com.arisuu2007.wgemini`
- **Main Activity:** `com.arisuu2007.wgemini.MainActivity`
- **Platform:** Android 4.2+ (Jelly Bean) to Android 16 (Target SDK 36)

## 🛠️ Building & Installation

### Option A: Using Apktool / Apktool M
1. Clone the repository:
   ```bash
   git clone [https://github.com/arisuu2007/wgemini.git](https://github.com/arisuu2007/wgemini.git)
   ```
2. Build the APK:
   ```bash
   apktool b wgemini -o GeminiWeb.apk
   ```
3. Sign the APK using `apksigner` or your preferred tool:
   ```bash
   apksigner sign --ks your-release-key.jks GeminiWeb.apk
   ```

### Option B: Releases
Download the latest signed APK directly from the **Releases** section.

## 🔒 Privacy & Disclaimers

This is an unofficial, independent web wrapper application. Gemini and Google are trademarks of Google LLC. Interacting with Gemini remains subject to Google's standard Terms of Service and Privacy Policy.

## 📄 License
This project is licensed under the [MIT License](LICENSE).
