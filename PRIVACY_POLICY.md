# InkWave — Privacy Policy

**Effective date:** September 2025
**Applies to:** InkWave V1 (comic reader) for Android
**Developer:** InkWave
**Contact:** [YOUR EMAIL HERE]

---

## The short version

InkWave is an offline-first app. It does not collect, store, transmit, or share
any personal data. Everything you do in the app stays on your device. There are
no accounts, no analytics, no ads, and no tracking of any kind.

---

## 1. What InkWave does NOT collect

- No name, email address, or any account information (there is no sign-up)
- No analytics or usage statistics
- No advertising or advertising identifiers
- No location data
- No crash reports sent to third parties
- No device identifiers
- No contacts, photos, or files beyond what you explicitly import

## 2. Your library stays on your device

All comics, reading progress, bookmarks, settings, and preferences are stored
in a local database on your device only. InkWave never uploads your library,
file names, or reading habits anywhere.

Imported comic files are opened through Android's Storage Access Framework
(SAF). The app reads only the files you explicitly select, and writes nothing
to shared storage.

## 3. Network access

InkWave uses the internet for **exactly one purpose**: downloading the optional
narration voice packs (Kokoro, Piper) that **you** explicitly choose in
Settings. Voice downloads are:

- **User-initiated only** — the app never connects to the network on its own
- **One-time** — once a voice is downloaded, it lives on your device and the
  network is never touched again for it
- **Anonymous** — downloads are plain file fetches from the voice-model host;
  no account, identifier, or personal data is sent with the request

There is no other network activity: no analytics, no ads, no telemetry, no
crash reporting, no background connections.

**About future advertising:** InkWave may introduce ads in a future version.
If that happens, this policy will be updated *before* that version ships, the
in-app experience will clearly disclose it, and any data the ad provider
collects will be described here. The current version contains no advertising
and no advertising SDKs.

## 4. Permissions explained

| Permission | Why it's needed | What actually happens |
|---|---|---|
| Internet | To download optional narration voice packs you select | Plain anonymous file downloads, initiated by you only; no other network use |
| Storage / SAF file access | To open the comic files you choose | Reads only files you explicitly pick; nothing is scanned or uploaded |
| Notifications | Playback controls for ambient audio | Local notifications only; no push notifications |
| Foreground service | Keep ambient audio playing while reading | Runs only while you use the feature |

## 5. Third-party services

InkWave uses **no third-party services** — no ad networks, no analytics
SDKs, no crash reporting services, no social SDKs. All processing (including
on-device OCR for narration and voice synthesis) happens locally. OCR uses
Google ML Kit's on-device APIs, which do not send image data off the device,
and downloaded voice packs run entirely on-device via ONNX Runtime.

## 6. Children's privacy

InkWave does not collect data from anyone, including children. Content
imported into the app is chosen and managed entirely by the user.

## 7. Data retention and deletion

Because no data leaves your device, you hold all of it:

- Deleting the app (or clearing app data in Android settings) permanently
  removes your library database, progress, bookmarks, and settings.
- Your original comic files are never modified or deleted by the app unless
  you explicitly delete them through the app's library screen.

## 8. Security

App settings that may hold sensitive values are encrypted using the Android
Keystore (AES-256). The app disables Android auto-backup of its private data
and never permits cleartext network traffic.

## 9. Changes to this policy

If InkWave's data practices ever change, this policy will be updated before
the change ships, with a new effective date and a note in the app's release
notes. The app will never silently begin collecting data.

## 10. Contact

Questions about this policy: **[YOUR EMAIL HERE]**

---

*This policy applies to InkWave V1. Last updated: September 2025.*
