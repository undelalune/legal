# Privacy Policy – ICD-11 Global

| | |
|---|---|
| **Effective date** | 30 October 2026 |
| **App** | ICD-11 Global (Android and iOS) |
| **Developer / contact** | undelalune · [support@undelalune.com](mailto:support@undelalune.com) |

---

> **In short:** ICD-11 Global is an offline reference for the ICD-11 classification. There is no account, and what you do in the app – searches, favorites, history – stays on your device; we never receive it. The app goes online to download the classification data, and for the services that keep it free: a banner ad from Google AdMob after an ad-free period at the start, crash reports through Firebase Crashlytics, and two settings for the ad-free period from Firebase Remote Config. On iPhone and iPad the system asks before ads may use your advertising identifier. Each of them is listed in [section 3](#3-when-the-app-connects-to-the-internet), with what it receives. A one-time in-app purchase removes the ads.

---

## 1. Who is responsible

This app is published by an individual developer ("we", "us"). For any privacy question you can reach us at [support@undelalune.com](mailto:support@undelalune.com).

---

## 2. What the app keeps, and where

| Data | Stored |
|---|---|
| Favorites (entries and sections you star) | Device only |
| History (the 50 entries you opened last) | Device only |
| Settings (the language of the classification, the theme) | Device only |
| The classification data you downloaded | Device only |
| Whether you bought "Remove ads" | Device only (Google Play or the App Store keeps its own record of the purchase) |
| The dates of the ad-free period | Device only (on iOS in the Keychain, see the ad-free period note below) |
| What you type into search | Kept only while the search screen is open; never saved and never sent |

We do not have a copy of any of this. Your searches, favorites and history are never sent to us or to any of the services below.

---

## 3. When the app connects to the internet

In each case the request carries none of your searches, favorites or history, but the service will – like any web server – see your IP address and the details of the request. Their own privacy policies apply.

| Feature | Third party | What is sent | Policy |
|---|---|---|---|
| Checking for newer classification data (once per app start) and downloading the data you choose in *Settings → ICD-11 data* | Our data files on [Cloudflare R2](https://www.cloudflare.com/developer-platform/products/r2/), run by Cloudflare, Inc. | A plain request for a file: IP address, time, and the system's standard user agent (on Android the Android version and device model; on iOS the app version and the versions of the system's network libraries). No identifier | [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/) |
| Advertising, after the ad-free period | [Google AdMob](https://admob.google.com) | Advertising ID (only if you consent), IP address, device information, general location derived from the IP address | [Google Privacy Policy](https://policies.google.com/privacy) · [How Google uses data from apps](https://policies.google.com/technologies/partner-sites) |
| Crash reporting | [Firebase Crashlytics / Google](https://firebase.google.com/products/crashlytics) | Stack trace, device model, Android or iOS version, app version, time of the crash, a Firebase installation ID – **not** your searches, favorites or history | [Google Privacy Policy](https://policies.google.com/privacy) |
| Ad-free period settings | [Firebase Remote Config / Google](https://firebase.google.com/products/remote-config) | Firebase installation ID (a random identifier for this install), app version, Android or iOS version, device language and country | [Google Privacy Policy](https://policies.google.com/privacy) |
| In-app purchase ("Remove ads") | [Google Play Billing / Google](https://play.google.com) on Android, the [App Store / Apple](https://www.apple.com/app-store/) on iOS | Handled by the store and tied to your Google account or your Apple Account. The app only reads whether the item is owned; we never see your name, payment details or billing address | [Google Privacy Policy](https://policies.google.com/privacy) · [Apple Privacy Policy](https://www.apple.com/legal/privacy/) |
| *Open in the WHO browser* in an entry's menu | The WHO's ICD-11 website, opened in your own browser | Whatever your browser sends when it opens a web page | The WHO website's own privacy policy |

> **Consent for ads:** In the European Economic Area and the UK, the app asks for your consent before the first ad is requested. If you consent, ads may be personalised and your advertising ID is used. If you decline, the advertising ID is not used and nothing is stored on or read from your device for advertising; you may still see ads, chosen without a profile of you (Google calls these limited ads). You can review or change your choice at any time in **Settings → Ad privacy settings**.
>
> On iOS, after that form, the system itself asks whether ICD-11 Global may track you across other companies' apps and websites (App Tracking Transparency). The app explains the request in one line: "Ads in the app can be matched to your interests. What you look up stays on your phone either way." If you choose *Ask App Not to Track*, the app does not use your advertising identifier (IDFA), and ads are not personalised with it. You can change the answer later in the iOS Settings app, under *Privacy & Security → Tracking*; the app has no switch of its own for it.
>
> Crash reporting and the ad-free period settings start only after that form has been shown (or was not needed).

> **Ad-free period:** For a period after installation the app shows no ads and makes no advertising requests. Its length is set by us and fetched through Firebase Remote Config; it may change or be withdrawn at any time and is not part of any agreement with you. The dates the app keeps to track it (when the period started, how long it is, and the last day the app saw) are stored on your device. On Android they are in the app's settings and part of your device backup. On iOS they are in the device's Keychain: the system keeps them when the app is deleted, so a reinstall does not start a new period, and moves them to a new device with an encrypted backup. They are not synced through iCloud Keychain and are never sent anywhere. Nothing but those dates is stored there. When the period ends, the app says so once.

> **Remove ads:** The one-time purchase in *Settings → Remove ads* removes the banner, and with it the advertising requests, for good. On iOS, *Restore purchase* brings the purchase back on a new device or after a reinstall.

---

## 4. Backups

Android may include the app's favorites, history and settings in your device's own Google backup, or move them to a new phone during a device-to-device transfer. On iOS, the same data goes into your iCloud backup or a backup on your computer, if you have those turned on. This is a system feature controlled by your device's backup settings, not by us, and it is covered by [Google's](https://policies.google.com/privacy) or [Apple's](https://www.apple.com/legal/privacy/) privacy policy. The downloaded classification data is left out of the backup on both systems: it is large, and it can be downloaded again.

---

## 5. What we do not do

- No account or sign-in.
- No analytics or tracking SDKs beyond those in [section 3](#3-when-the-app-connects-to-the-internet).
- We never receive your searches, favorites or history, and we do not sell data.

---

## 6. Permissions

**Android**

| Permission | Why |
|---|---|
| Internet (`INTERNET`) | To download the classification data, show ads, send crash reports, fetch the ad-free period settings and check the purchase (see [section 3](#3-when-the-app-connects-to-the-internet)) |
| Advertising ID (`AD_ID`) | Read by the Google Mobile Ads SDK, and used only if you consent (see above) |
| Google Play billing (`BILLING`) | To offer and check the "Remove ads" purchase |

**iOS**

| Permission | Why |
|---|---|
| Tracking (App Tracking Transparency) | Asked once ads are about to be shown, to let them use your advertising identifier; see the consent note in [section 3](#3-when-the-app-connects-to-the-internet) |

On iOS the app needs no permission to use the internet. Apart from what is described above, it uses only the system interfaces Apple asks apps to declare for their own settings (UserDefaults), for checking free space before a download, and for the dates of the downloaded data files, all on the device. The app's own code collects no data. The services in [section 3](#3-when-the-app-connects-to-the-internet) declare what they collect, including any use of the advertising identifier, in their own privacy manifests.

---

## 7. Keeping and deleting your data

Everything the app keeps lives on your device, so you are in control of it: *Settings → Clear history* removes the history, the star on an entry removes it from favorites, and *Settings → ICD-11 data* removes a downloaded language. Uninstalling the app removes all of its data from your device, with one exception on iOS: the dates of the ad-free period stay in the Keychain (see [section 3](#3-when-the-app-connects-to-the-internet)). Copies in your device's Google or iCloud backup stay until you delete them there.

**If you email us.** *Settings → Send feedback* opens your own email app with a message addressed to us; nothing leaves your device until you send it there yourself. The draft ends with one technical line – the app version, the Android or iOS version, the device model, the ICD-11 release and the language of the classification – which you can see and delete before sending. From an email we get your address and what you wrote, and we use them only to reply and to fix what you report. The email stays in our mailbox while the conversation is useful, and we delete it if you ask us to. It is not added to any list and not shared with anyone.

Apart from emails you send us, we hold nothing about you. Crash reports, advertising data and Cloudflare's server logs are kept by Google and Cloudflare under their own policies and retention rules, linked in [section 3](#3-when-the-app-connects-to-the-internet).

---

## 8. Children

The app is a professional reference and is not directed at children. We collect no personal data from anyone, apart from emails people choose to send us.

---

## 9. Changes to this policy

We may update this policy as the app changes. The current version is always at this page, and the effective date above shows the latest revision.

---

## 10. Contact

Questions about this policy: [support@undelalune.com](mailto:support@undelalune.com)
