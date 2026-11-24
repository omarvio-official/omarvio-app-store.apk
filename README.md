# OMARVIO App Store — Official Android APK Releases

Official signed Android release channel for **OMARVIO App Store** (`app.omarvio.appstore`), synchronized live with [https://omarvio-app.pages.dev](https://omarvio-app.pages.dev).

- **Latest Signed APK:** [Download from Releases](https://github.com/omarvio-official/omarvio-app-store.apk/releases/latest)
- **Official Web Store:** [https://omarvio-app.pages.dev](https://omarvio-app.pages.dev)
- **Target Platform:** Android 15 (API 35) · Supports Android 7.0+ (API 24+)

---

## Privacy & Security Summary

OMARVIO App Store is built around a **Zero-Telemetry** architecture so users can browse and install verified apps safely:

1. **Zero Tracking or Ad SDKs:** The app does not collect personal analytics, advertising IDs, device telemetry, or behavioral profiles, and contains no third-party tracking SDKs.
2. **Minimal Android Permissions:**
   - `INTERNET` & `ACCESS_NETWORK_STATE` — load live store listings and download packages.
   - `REQUEST_INSTALL_PACKAGES` — prompted only when you explicitly choose to install a downloaded `.apk`.
   - `POST_NOTIFICATIONS` *(optional)* — download completion notifications on Android 13+.
   - **Never requested:** Contacts, SMS, Call Logs, Location, Camera, or Microphone.
3. **Local-Only User History:** Saved preferences, bookmarks, and download records stay locally on your device and can be cleared anytime inside **Settings**.
4. **Verified Package Origins & Signing:** Every app update is verified against official upstream repositories (F-Droid, IzzyOnDroid, GitHub Releases, Flathub, official developer portals) with SHA-256 verification. All official OMARVIO APKs are signed with the same permanent RSA-4096 release key for safe in-place updates.
5. **Consumer-Only Client:** Administrative panels are completely disabled inside the public Android APK and remain protected on the server-authenticated web admin interface.

**Support & Privacy Contact:** `omarvio.official@gmail.com`
