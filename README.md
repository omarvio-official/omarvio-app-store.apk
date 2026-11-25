# OMARVIO App Store — Official Android APK Releases

Official signed Android release channel for **OMARVIO App Store** (`app.omarvio.appstore`), synchronized live with **[https://omarvio-app.pages.dev](https://omarvio-app.pages.dev)**.

> **Note:** This public repository publishes verified compiled `.apk` releases and user documentation only. Source code and administrative systems remain private and protected.

- **Latest Signed APK:** [Download Latest Release](https://github.com/omarvio-official/omarvio-app-store.apk/releases/latest)
- **Official Web Store:** [https://omarvio-app.pages.dev](https://omarvio-app.pages.dev)
- **Package ID:** `app.omarvio.appstore`
- **Target Platform:** Android 15 (API 35) · Supports Android 7.0+ (API 24+)
- **Permanent Signing Certificate (SHA-256):** `CC:1B:E2:D7:4E:C8:20:82:E0:D0:6D:28:EE:47:85:E2:4A:8E:2D:2E:61:F9:17:6B:16:59:A2:9E:69:FB:BA:41`

---

## User Installation & Update Guideline

### 1. Installing on Android Phones (100% Verified Steps)
1. Open the [Latest Release](https://github.com/omarvio-official/omarvio-app-store.apk/releases/latest) and download **`omarvio-app-store.apk`**.
2. Tap the downloaded `.apk` file from your browser or Android **Files / Downloads** app.
3. When Android asks for permission, tap **Settings** and enable **Allow from this source** (`Install unknown apps`).
4. **If Google Play Protect shows *"Harmful app blocked"*:**
   - Play Protect automatically warns on independently signed direct-download APKs that are not distributed via the Google Play Store.
   - Tap **Install anyway** (or **More details -> Install anyway**) to complete installation safely.
   - You can verify the APK authenticity anytime against our permanent SHA-256 certificate fingerprint listed above.

### 2. Installing Apps Inside OMARVIO App Store
- Every app inside OMARVIO is fetched directly from official developer releases (F-Droid, IzzyOnDroid, GitHub Releases, Flathub, official project CDNs) with automatic architecture matching (`arm64-v8a`, `armeabi-v7a`, `universal`) and SHA-256 integrity checks.
- When downloading an `.apk` inside the OMARVIO Android app, Android's native Download Manager downloads the package securely and automatically opens the system installer upon completion.
- Allow **Install unknown apps** for **OMARVIO App Store** once so future app installations and updates launch smoothly in one tap.

### 3. Live Website Sync & Automatic Update Notifications
- **100% Live Catalog Parity:** Catalog updates deployed to `omarvio-app.pages.dev` appear immediately inside the Android app on startup or pull-to-refresh.
- **Smart APK Update Alerts:** The Android app compares your installed native version against the latest GitHub Release. An update notification appears **strictly only** when a newer APK build exists, and automatically disappears as soon as you install the update.
- **In-Place Upgrades:** All future releases are signed with the exact same lifetime RSA-4096 certificate, so updates install smoothly without uninstalling or losing local data.

---

## Privacy Policy & Security Architecture

OMARVIO App Store is engineered around a strict **Zero-Telemetry** policy:

1. **Zero Tracking, Ads, or Profiling:** No ad SDKs, advertising IDs, crash surveillance, or behavioral analytics are embedded in the web store or Android APK.
2. **Minimal Device Permissions:**
   - `INTERNET` & `ACCESS_NETWORK_STATE` — load live catalog listings and download verified app packages.
   - `REQUEST_INSTALL_PACKAGES` — used strictly when you explicitly tap to install a downloaded `.apk`.
   - `POST_NOTIFICATIONS` *(optional)* — native Android download progress and completion notifications on Android 13+.
   - **Never requested:** Contacts, SMS, Call Logs, GPS Location, Camera, Microphone, or Background Accessibility services.
3. **Local-Only User Preferences:** Theme, language, saved bookmarks, sound preference, and installed version history remain solely on your device and can be cleared anytime from **Settings**.
4. **Verified Supply Chain:** Downloads route strictly from verified upstream release endpoints with cryptographic checksum inspection where provided.
5. **Strict Admin Separation:** Administrative management portals exist exclusively on the authenticated web admin interface and are completely blocked from the Android consumer APK.

**Official Support & Privacy Contact:** `omarvio.official@gmail.com`
