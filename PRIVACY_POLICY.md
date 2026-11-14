# Privacy Policy for Sayasky Voice

*Last Updated: November 2026*

**Hosted Privacy Policy URL:**
[https://sayasky-s.github.io/sayasky-voice-policy/](https://sayasky-s.github.io/sayasky-voice-policy/)

---

Welcome to **Sayasky Voice** ("we", "our", or "us"). We respect your privacy and are committed to protecting it. This Privacy Policy explains our data practices for the Sayasky Voice mobile application (Package Name: `com.sayasky.voice`).

Sayasky Voice helps learners turn photos of English textbook pages or worksheets into interactive, word-synchronized pronunciation lessons with Arabic support.

---

## 1. Information We Do NOT Collect
- **No User Accounts or Personal Identifiers:** We do not require registration or login. We do not collect names, email addresses, phone numbers, postal addresses, or contacts.
- **No Microphone Recording:** Microphone recording (`RECORD_AUDIO`) is disabled in the release app. Audio features play back synthesized pronunciation audio only.
- **No Location Tracking:** We do not request or collect GPS, fine location, or coarse location data.
- **No Financial Data or Third-Party Ads:** We do not collect payment card information, display third-party advertisements, or share data with ad networks or data brokers.

---

## 2. How Page Photos & Study Text Are Processed
When you choose **Camera** or **Import from Gallery** (restricted to images only):
- **EXIF Metadata Stripping:** Before upload, your selected page image is resized on-device (maximum 1600px) and re-encoded as a JPEG, stripping EXIF camera/location metadata.
- **Ephemeral Text Recognition (OCR):** The prepared image is sent over encrypted HTTPS/TLS to extract interactive English word boxes for your reading canvas. Photos are processed strictly for core app functionality and are not linked to a user identity or profile.
- **Word-Synchronized Speech & L1 Tips:** Recognized English text or curated story phrases are processed to deliver US/UK pronunciation playback and Arabic articulation tips. Repeated audio clips may be cached anonymously by content hash to reduce latency.

---

## 3. On-Device Local Data
Your current session state, accent speed settings (`0.65x`, `0.85x`, `1x`), and local study items stay stored on your device. Built-in sample lessons work offline without sending any data off-device.

---

## 4. Android System Permissions
Sayasky Voice requests only minimal permissions required for reading and audio playback:
- `android.permission.INTERNET`: Connect over HTTPS to analyze captured page photos and stream English pronunciation audio.
- `android.permission.MODIFY_AUDIO_SETTINGS`, `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`: Manage speech playback and audio controls.
- `android.permission.VIBRATE`: Standard UI feedback.
- `android.permission.READ_EXTERNAL_STORAGE` / `WRITE_EXTERNAL_STORAGE` (`maxSdkVersion="32"`): Scoped legacy image picker compatibility on Android 12 and lower only.

---

## 5. Google Play Data Safety Summary

| Data Category | Collected? | Shared? | Processing Purpose | Linked to User? |
| :--- | :--- | :--- | :--- | :--- |
| **Personal Identifiers** | No | No | No accounts required | N/A |
| **Location Data** | No | No | Not requested | N/A |
| **Audio / Microphone** | No | No | Playback only | N/A |
| **Photos** (User-Selected Page Images) | Yes | No | Core OCR App Functionality | No |

- **Encryption in Transit:** All network communication uses HTTPS/TLS.
- **Data Deletion:** Because no user accounts exist, you can remove all local app data at any time via **Android Settings > Apps > Sayasky Voice > Storage > Clear Data**, or by uninstalling the app.

---

## 6. Children's Privacy
Sayasky Voice is an educational language utility intended for general audiences aged 13 and above. We do not knowingly collect personal information from children under 13.

---

## 7. Contact & Publisher
- **Publisher / Developer:** SayaSky
- **Package ID:** `com.sayasky.voice`
- **Support Email:** [alsheikh0202@gmail.com](mailto:alsheikh0202@gmail.com)
- **Live Policy Page:** [https://sayasky-s.github.io/sayasky-voice-policy/](https://sayasky-s.github.io/sayasky-voice-policy/)
