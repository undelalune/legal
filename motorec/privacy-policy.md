# Privacy Policy for MotoRec

**Effective date:** 1 July 2026
**App:** MotoRec (Android)
**Developer / contact:** undelalune (motorec-dev@outlook.com)

## Short version

MotoRec is built to keep your data on your device. We — the developer — do
not operate any servers, do not collect your personal data, and never receive
your recordings, locations, transcripts, or any other content you create in the
app. Speech-to-text runs entirely on your phone. The app connects to the
internet only for a few clearly described features, and even then it does not
send us anything.

## 1. Who is responsible

This app is published by an individual developer ("we", "us"). For any privacy
question you can reach us at **motorec-dev@outlook.com**.

## 2. What data the app handles and where it is stored

Everything you create or capture in MotoRec is stored **only in the app's
storage on your device**:

- **Audio recordings** (`.m4a` files) captured from the microphone.
- **GPS tracks** (`.gpx` files) — only if you choose to record a track.
- **Transcripts** (`.txt` / `.jsonl` files) generated from your recordings.
- **Tags, titles, and metadata** you add to recordings.
- **App settings** (preferences).

We do not have a copy of any of this. It does not leave your device unless
**you** explicitly share or export it (see section 7).

## 3. Microphone

The app records audio only while you actively start a recording. Recordings are
written to local files on your device and are never uploaded to us or to any
third party automatically.

## 4. Location and GPS tracks

If you start a GPS track, the app uses your device's location
(`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`) to record the route to a
local `.gpx` file alongside the recording. This location data:

- is used solely to draw and replay **your** track;
- is stored only on your device;
- is never transmitted to us.

You can record audio without granting location access; only the GPS-track
feature needs it.

## 5. Speech-to-text (transcription)

Transcription is performed **entirely on your device** using an on-device
speech-recognition engine (whisper.cpp). Your audio is **not** uploaded
anywhere for transcription.

To make transcription work, the first time you use it the app downloads a
speech-recognition **model file** (see section 6).

## 6. When the app connects to the internet, and third parties

MotoRec uses the network only for the following features. In each case the
request is a normal web request that does not include your personal data, but
the third party will, like any web server, see your IP address and the specifics
of the request. Their own privacy policies apply.

- **Speech model download (Hugging Face).** The first time you use
  transcription, the app downloads a model file from Hugging Face
  (`huggingface.co`). No content or personal data is sent — it is a download of
  a public file. See Hugging Face's privacy policy:
  https://huggingface.co/privacy
- **Map tiles (CARTO / OpenStreetMap).** When you view a recorded track on the
  map, the map background images are fetched from CARTO's tile servers
  (`basemaps.cartocdn.com`), based on OpenStreetMap data. The tile requests
  reveal to CARTO your IP address and the approximate map area you are viewing.
  See: https://carto.com/privacy/ and https://www.openstreetmap.org/copyright
- **Opening a track in an external map app.** If you tap "open externally", the
  track's coordinates are handed to the external map application you choose
  (for example Google Maps). From that point the external app and its privacy
  policy govern that data.

## 7. Sharing and export

When you use Share or Export, your data leaves the app only at that moment and
only to the destination **you** pick (a messaging app, file manager, email,
etc.). MotoRec does not send your data anywhere on its own.

## 8. What we do NOT do

- We do **not** use analytics or tracking SDKs.
- We do **not** require an account or sign-in.
- We do **not** sync to any cloud or to us.
- We do **not** sell or share your data — we never have it.

## 9. Permissions and why they are used

- **Microphone (RECORD_AUDIO)** — to record audio.
- **Location (FINE/COARSE)** — to record an optional GPS track.
- **Bluetooth (BLUETOOTH / BLUETOOTH_CONNECT)** — to use a connected Bluetooth
  microphone/headset for recording and playback routing.
- **Internet / Network state** — to download the speech model and load map
  tiles, as described above.
- **Notifications** — to show the ongoing recording/playback notification.
- **Foreground service** — so recording, playback, and transcription continue
  reliably while the app is in the background.

## 10. Data retention and deletion

Because all data lives on your device, you are in full control:

- Delete an individual recording (and its track/transcript) from within the app.
- Uninstalling MotoRec removes all of its data from your device.

We hold no copies, so there is nothing for us to delete on your behalf.

## 11. Children

MotoRec is not directed at children and does not knowingly collect data from
anyone. As described above, we do not collect personal data at all.

## 12. Changes to this policy

We may update this policy as the app evolves (for example if a future version
adds new features). The current version is always available at this page, and
the "Effective date" above reflects the latest revision.

## 13. Contact

Questions about this policy: **motorec-dev@outlook.com**
