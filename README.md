# SixSlot — Minimalist Dark Android Launcher

SixSlot is a private, local-only Android launcher engineered for calm, intentional phone use:
- **Dual Clock (`clock: both`)**: Crisp analog dial paired beside a tabular digital clock, date, and live battery indicator. Tap to open system Alarms.
- **Upper Focus Timer**: Positioned directly above your 6 apps with instant presets (`5m`, `15m`, `25m`, `45m`), pause/reset controls, and vibration/tone alert.
- **Six Customizable App Slots (`app drawer: none`)**: Zero app drawer and zero infinite scrolling. Long-press any of the 6 slots to swap its assigned app or toggle a 3-second mindful breathing pause.
- **Pure Dark Theme (`theme: dark`)**: True OLED dark slate palette (`#090B10`) running 100% locally on your phone with zero servers, analytics, or internet permissions.
- **One-Tap Exit Launcher Button**: Dedicated bottom button that cleanly steps down from the Android `CATEGORY_HOME` alias and launches your phone's stock normal launcher immediately. Tapping the **SixSlot** icon in your normal launcher re-arms it anytime.
- **Helpful Daily Extras**: One-line intention scratchpad, swipe-down anywhere for notifications, and system Back-button home protection.

## How to Build & Install on Your Phone

### Option 1: Zero-Install Cloud APK Build (GitHub Actions — ~2 Minutes)
If you don't want to install Android Studio on a computer:
1. Create a free private repository on GitHub and upload all files from this folder (including `.github/workflows/build-apk.yml`).
2. Open the **Actions** tab in your GitHub repository -> click **Build SixSlot Android APK** -> download **SixSlotLauncher-Installable-APK** directly on your phone.
3. Tap `app-debug.apk` on your Android phone to install.

### Option 2: Android Studio (USB or Wireless Debugging)
1. Open this `android-launcher` folder in **Android Studio Ladybug (or newer)**.
2. Wait for Gradle Sync to finish automatically.
3. Connect your Android phone with **USB Debugging** (or **Wireless Debugging**) enabled and click **Run ('app')**.

### Option 3: Command Line (Gradle + ADB)
```bash
gradle installDebug
```
