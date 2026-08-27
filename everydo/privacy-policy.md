# Privacy Policy – Everydo

| | |
|---|---|
| **Effective date** | 27 August 2026 |
| **App** | Everydo (Android) |
| **Developer / contact** | undelalune · [undelalune-dev@outlook.com](mailto:undelalune-dev@outlook.com) |

---

> **In short:** Everydo keeps your tasks on your device. We – the developer – do not operate any servers and never receive your tasks, notes, or anything else you create in the app. There is no account and no cloud sync. The free version shows advertising served by Google AdMob, the app reports crashes through Firebase Crashlytics, and it fetches two settings for its ad-free period through Firebase Remote Config; all three collect certain data, described in [section 3](#3-when-the-app-connects-to-the-internet-and-third-parties). You can remove ads with a one-time in-app purchase. If you use the calendar import, the app reads your device's calendars – only when you ask it to, and only to copy events into tasks that stay on the phone.

---

## 1. Who is responsible

This app is published by an individual developer ("we", "us"). For any privacy question you can reach us at [undelalune-dev@outlook.com](mailto:undelalune-dev@outlook.com).

---

## 2. What data the app handles and where it is stored

Everything you create in Everydo is stored **only in the app's storage on your device**:

| Data | Stored |
|---|---|
| Tasks, subtasks, and descriptions | Device only |
| Recurrence schedules and completion windows | Device only |
| Completion history | Device only |
| Reminder settings | Device only |
| App settings (theme, week start, widget options) | Device only |

We do not have a copy of any of this. It does not leave your device unless **you** explicitly export or back it up (see [section 4](#4-backups)).

Your tasks are never sent to the advertising or crash-reporting services described below. Those services receive only what is listed in the table there.

---

## 3. When the app connects to the internet, and third parties

Everydo uses the network only for the features below. In each case the request carries none of your tasks or their contents, but the third party will – like any web server – see your IP address and the specifics of the request. Their own privacy policies apply.

| Feature | Third party | What is sent | Policy |
|---|---|---|---|
| Advertising (free version) | [Google AdMob](https://admob.google.com) | Advertising ID (only if you consent), IP address, device info, general location derived from IP | [Google Privacy Policy](https://policies.google.com/privacy) · [Ads Policy](https://policies.google.com/technologies/ads) |
| Crash reporting | [Firebase Crashlytics / Google](https://firebase.google.com/products/crashlytics) | Stack trace, device model, Android version, app version, crash time – **not** your tasks, notes, or calendar data | [Google Privacy Policy](https://policies.google.com/privacy) |
| In-app purchase ("Remove ads") | [Google Play Billing / Google](https://play.google.com) | Handled by Google Play – the purchase is tied to your Google account. The app only reads whether the item is owned; **we** never see your name, payment details, or billing address | [Google Privacy Policy](https://policies.google.com/privacy) |
| Ad-free period settings | [Firebase Remote Config / Google](https://firebase.google.com/products/remote-config) | Firebase installation ID (a random identifier for this install), app version, Android version, device language and country – **not** your tasks, notes, or calendar data | [Google Privacy Policy](https://policies.google.com/privacy) |

> **Advertising note:** On first launch in the European Economic Area and the UK, the app shows a consent dialog. If you consent, ads are personalised and your advertising ID is used. If you decline, the advertising ID is not used and nothing is stored on or read from your device for advertising; you may still see ads, selected without any profile of you (Google calls these limited ads). You can review or change that choice at any time via **Settings → Help & info → Ad privacy settings**. The **"Remove ads"** in-app purchase removes advertising permanently, and with it the advertising requests described above.

> **Ad-free period:** Everydo can run for a period without showing ads. On a new installation the period starts when you install the app; on an app that is already on your device it starts with the update that introduced the period. Its length, and whether it is offered at all, is set by us and fetched through Firebase Remote Config; it may change or be withdrawn at any time and is not part of any agreement with you. While the period runs, no advertising requests are made and no consent dialog appears. The dates the app keeps in order to track the period are stored in its settings on your device and are included in your device backup along with them. When the period ends, the app says so once, in a dialog.

---

## 4. Backups

Two ways your data can leave the app, both under your control:

- **Manual export.** *Settings → Export backup* writes all tasks and history to a JSON file at a location you pick (a folder, a cloud drive, etc.). The file goes only where you send it. *Import backup* reads such a file back in.
- **Device backup.** Android may include Everydo's data (tasks, history, settings) in your device's own Google backup or in a device-to-device transfer when you migrate phones. This is a system feature controlled by your device's backup settings, not by us; it is covered by [Google's privacy policy](https://policies.google.com/privacy).

---

## 5. Calendar import

Everydo can copy events from the calendars on your device into tasks. This is optional: it happens only when you open *Settings → Data → Import from calendar* and pick the events yourself.

- The app asks for the Android **calendar read permission** at that moment, not at install and not at first launch. Decline it and the rest of the app works as before.
- Access is **read-only**. Everydo never creates, edits, or deletes anything in your calendar.
- Reading happens **only while that screen is open**. There is no background sync, no watching for changes, and no repeat reads afterwards.
- What you import (title, description, dates, repeat rule, reminders) is copied into Everydo's own storage on your device, exactly like a task you typed yourself. It stays there: calendar data is never sent to us or to the services in [section 3](#3-when-the-app-connects-to-the-internet-and-third-parties).
- Deleting an imported task in Everydo does not touch the original event.

---

## 6. Notifications and reminders

Reminders are scheduled and shown entirely on your device using Android's alarm and notification systems. No reminder content is sent anywhere.

---

## 7. What we do NOT do

- We do **not** use analytics or user-tracking SDKs beyond what is described in [section 3](#3-when-the-app-connects-to-the-internet-and-third-parties).
- We do **not** require an account or sign-in.
- We do **not** sync your tasks to any cloud or to us.
- We do **not** sell your data – we never have it.

---

## 8. Permissions and why they are used

| Permission | Purpose |
|---|---|
| Notifications (`POST_NOTIFICATIONS`) | To show task reminders |
| Exact alarms (`SCHEDULE_EXACT_ALARM`) | To fire reminders at the exact time you set |
| Boot completed (`RECEIVE_BOOT_COMPLETED`) | To restore scheduled reminders after your device restarts |
| Read calendar (`READ_CALENDAR`) | To list your calendars and their events during the optional import, and only while that screen is open (see [section 5](#5-calendar-import)) |
| Internet / network state (`INTERNET`, `ACCESS_NETWORK_STATE`) | To display advertising, send crash reports, fetch the ad-free period settings, and check the "Remove ads" purchase (see [section 3](#3-when-the-app-connects-to-the-internet-and-third-parties)) |

---

## 9. Data retention and deletion

Because your tasks live on your device, you are in full control:

- Delete an individual task (or its whole series) from within the app.
- Completion history is kept for two years. Once a day the app removes windows that closed more than two years earlier, so its storage does not grow without limit. Open and overdue windows are never removed this way, whatever their age. A backup you exported before that point still contains the older history.
- Uninstalling Everydo removes all of its data from your device. Backup files you exported yourself, and any copies in your device's Google backup, remain until you delete them.

We hold no copies of your tasks, so there is nothing for us to delete on your behalf. Crash reports and advertising data held by Google are covered by Google's own policy and retention rules, linked in [section 3](#3-when-the-app-connects-to-the-internet-and-third-parties).

---

## 10. Children

Everydo is not directed at children. We do not knowingly collect personal data from anyone, and we collect none ourselves at all.

---

## 11. Changes to this policy

We may update this policy as the app evolves. The current version is always available at this page, and the "Effective date" above reflects the latest revision.

---

## 12. Contact

Questions about this policy: [undelalune-dev@outlook.com](mailto:undelalune-dev@outlook.com)
