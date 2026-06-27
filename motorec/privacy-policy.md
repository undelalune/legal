# Privacy Policy – MotoRec

| | |
|---|---|
| **Effective date** | 1 July 2026 |
| **App** | MotoRec (Android) |
| **Developer / contact** | undelalune · [motorec-dev@outlook.com](mailto:motorec-dev@outlook.com) |

---

> **In short:** MotoRec keeps all your data on your device. We – the developer – do not operate any servers and never receive your recordings, locations, transcripts, or any other content you create in the app. Speech-to-text runs entirely on your phone. The app contains advertising served by Google AdMob, which collects certain data as described in [section 6](#6-when-the-app-connects-to-the-internet-and-third-parties). You can remove ads with an in-app purchase.

---

## 1. Who is responsible

This app is published by an individual developer ("we", "us"). For any privacy question you can reach us at [motorec-dev@outlook.com](mailto:motorec-dev@outlook.com).

---

## 2. What data the app handles and where it is stored

Everything you create or capture in MotoRec is stored **only in the app's storage on your device**:

| Data | Format | Stored |
|---|---|---|
| Audio recordings | `.m4a` | Device only |
| GPS tracks | `.gpx` | Device only – optional |
| Transcripts | `.txt` / `.jsonl` | Device only |
| Tags, titles, metadata | – | Device only |
| App settings | – | Device only |

We do not have a copy of any of this. It does not leave your device unless **you** explicitly share or export it (see [section 7](#7-sharing-and-export)).

---

## 3. Microphone

The app records audio only while you actively start a recording. Recordings are written to local files on your device and are never uploaded to us or to any third party automatically.

---

## 4. Location and GPS tracks

If you start a GPS track, the app uses your device's location (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`) to record the route to a local `.gpx` file alongside the recording. This location data:

- is used solely to draw and replay **your** track;
- is stored only on your device;
- is never transmitted to us.

You can record audio without granting location access – only the GPS-track feature needs it.

---

## 5. Speech-to-text (transcription)

Transcription is performed **entirely on your device** using an on-device speech-recognition engine (whisper.cpp). Your audio is **not** uploaded anywhere for transcription.

To make transcription work, the first time you use it the app downloads a speech-recognition **model file** (see [section 6](#6-when-the-app-connects-to-the-internet-and-third-parties)).

---

## 6. When the app connects to the internet, and third parties

MotoRec uses the network only for the features listed below. In each case the request does not include your personal data, but the third party will – like any web server – see your IP address and the specifics of the request. Their own privacy policies apply.

| Feature | Third party | What is sent | Policy |
|---|---|---|---|
| Speech model download | [Hugging Face](https://huggingface.co) | Download of a public file – no content or personal data | [Privacy policy](https://huggingface.co/privacy) |
| Map tiles | [CARTO](https://carto.com) / [OpenStreetMap](https://www.openstreetmap.org) | IP address + approximate map area | [CARTO](https://carto.com/privacy/) · [OSM](https://www.openstreetmap.org/copyright) |
| Open track externally | External map app of your choice (e.g. Google Maps) | Track coordinates, handed to the app you select | App's own policy |
| Crash reporting | [Firebase Crashlytics / Google](https://firebase.google.com/products/crashlytics) | Stack trace, device model, Android version, app version, crash time – **not** recordings, transcripts, or GPS tracks | [Google Privacy Policy](https://policies.google.com/privacy) |
| Advertising (free version) | [Google AdMob](https://admob.google.com) | Advertising ID, IP address, device info, general location derived from IP | [Google Privacy Policy](https://policies.google.com/privacy) · [Ads Policy](https://policies.google.com/technologies/ads) |

> **Advertising note:** On first launch in the European Economic Area and UK, the app shows a consent dialog. Ads are personalised only if you consent; otherwise non-personalised ads are shown. You can remove all ads permanently with the **"Remove ads"** in-app purchase.

---

## 7. Sharing and export

When you use Share or Export, your data leaves the app only at that moment and only to the destination **you** pick (a messaging app, file manager, email, etc.). MotoRec does not send your data anywhere on its own.

---

## 8. What we do NOT do

- We do **not** use analytics or user-tracking SDKs beyond what is described in [section 6](#6-when-the-app-connects-to-the-internet-and-third-parties).
- We do **not** require an account or sign-in.
- We do **not** sync to any cloud or to us.
- We do **not** sell or share your data – we never have it.

---

## 9. Permissions and why they are used

| Permission | Purpose |
|---|---|
| `RECORD_AUDIO` | To record audio |
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | To record an optional GPS track |
| `BLUETOOTH` / `BLUETOOTH_CONNECT` | To use a connected Bluetooth microphone or headset for recording and playback routing |
| `INTERNET` / Network state | To download the speech model, load map tiles, and display advertising |
| Notifications | To show the ongoing recording/playback notification |
| Foreground service | So recording, playback, and transcription continue reliably while the app is in the background |

---

## 10. Data retention and deletion

Because all data lives on your device, you are in full control:

- Delete an individual recording (and its track/transcript) from within the app.
- Uninstalling MotoRec removes all of its data from your device.

We hold no copies, so there is nothing for us to delete on your behalf.

---

## 11. Children

MotoRec is not directed at children and does not knowingly collect data from anyone. As described above, we do not collect personal data at all.

---

## 12. Changes to this policy

We may update this policy as the app evolves (for example if a future version adds new features). The current version is always available at this page, and the "Effective date" above reflects the latest revision.

---

## 13. Contact

Questions about this policy: [motorec-dev@outlook.com](mailto:motorec-dev@outlook.com)
