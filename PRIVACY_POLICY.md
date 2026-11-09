# HabitForge Privacy Policy

**Effective Date:** May 17, 2026
_Last updated: November 9, 2026_
**Version:** 1.2.0

HabitForge ("we," "our," or "us") is an Android app. HabitForge is a habit tracker for Android that stores habits, completions, notes, photos, and preferences locally on your device. This Privacy Policy explains what information the app collects, how it is used, and the choices you have. By installing or using HabitForge you agree to the practices described below.

## Information We Collect

### Location Data
- HabitForge does not collect location data.

### Account Information
- **No account, no sign-in, and no account data of any kind.** HabitForge has never had accounts.
- **There are no in-app purchases and no premium tier.** Earlier versions of this policy described Google Play Billing; the app no longer contains it.

### Device Information
- Habit names, completion history, notes, photos you attach, reminders and preferences are stored on your device and nowhere else.

## How We Use Your Information

### Location Sharing
- HabitForge does not use your location.

### What the App Does With Your Data
- Tracks habits and completions, on your device.
- Shows reminders and keeps your preferences, on your device.

### Service Improvement
- **The app contains no analytics and no crash reporting.** We receive nothing about how you use it. Earlier versions of this policy named Firebase; the app has never shipped it — the Firebase lines in its build file are commented out.
- We do not sell, rent, or monetize your habit data. We never receive it in the first place.

## Storage and Retention

### Data Storage
- Habits, notes, photos, completions, and preferences are stored on your device, in a Room database and DataStore inside the app's private storage.
- **There is no cloud copy.** No Sudarshan Tech Labs server exists for this app, and the app does not sign in to anything.

### Data Retention
- Local habit data remains until you delete it, clear app data, or uninstall the app.
- A CSV export you create is a file you own. It stays wherever you saved or sent it until you delete it.

### Data Security
- Your habit data sits in the app's private storage, protected by Android's application sandbox. The app does not add encryption of its own on top of that.
- **The app does not request the `INTERNET` permission, so it cannot send your data anywhere.** This is the strongest statement in this policy and it is the one worth checking: the permission list on the Play Store shows notifications only.
- You should protect your device with a screen lock, since that is what stands between someone holding your phone and your habit notes.

## Data Sharing

### Sharing With Other People
- **HabitForge has no sharing, pairing or collaboration features.** There is nobody to share with, and no way to.

### Third Parties
- **There are none.** The app sends data to no company, including us. It has no analytics, no crash reporting, no advertising SDK, no in-app purchases and no backend.
- The only things that leave the app are ones you start by hand: a CSV export you save or send yourself, and tapping a link to this policy, the project's GitHub page or the Play Store listing, each of which opens in your browser or in the Play Store app rather than inside HabitForge.

We do **not** share your data with:
- Data brokers
- Unrelated advertising networks, unless advertising is explicitly listed above for this app
- Third parties unrelated to the app features described in this policy

## Permissions Used

### Required Permissions

* **POST_NOTIFICATIONS**: Used for habit reminders. **This is the only permission HabitForge itself declares.**

The app does **not** declare `INTERNET`. Without it Android will not let the app open a network connection at all, which is why this policy can state flatly that your habit data cannot leave your device.

### Permissions added by Android libraries

The app declares the one above. The finished build carries four more, declared by WorkManager — the Android library that runs your reminders on schedule — rather than by HabitForge's own code. They appear in the permission list you see on the Play Store, so they are listed here for completeness:

* **WAKE_LOCK** and **RECEIVE_BOOT_COMPLETED**: how Android runs a reminder while the phone is idle, and re-registers your reminders after you restart the phone.
* **FOREGROUND_SERVICE**: how WorkManager runs scheduled work.
* **ACCESS_NETWORK_STATE**: lets a library *check* whether a network exists. **It does not grant the ability to use one** — that would need `INTERNET`, which this app does not declare. WorkManager declares this permission in every app that uses it, whether or not the app does anything with a network.

Verified against the merged manifest of the release build rather than the app's own manifest file. The merged release manifest contains exactly these five permissions and no others.

### Optional Permissions

* Attaching a photo to a habit completion and turning reminders on or off are optional features you control. Photos you attach stay in the app's private storage.

## Your Rights and Controls

### Location Sharing Control
- No location sharing exists in HabitForge.

### Account Management
- There is no account to manage, and no purchases.

### Data Access
- You can view, edit, export, or delete local habit data in the app.

### GDPR Rights (EU Users)
If you are in the European Union, you have additional rights:
- **Right to Access**: Request a copy of your personal data
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of your data
- **Right to Restrict Processing**: Limit how we use your data
- **Right to Data Portability**: Receive your data in a portable format
- **Right to Object**: Object to certain types of processing

To exercise these rights, contact us using the methods in the Contact Us section.

### Permissions
- You can revoke the notification permission in Android Settings -> Apps -> HabitForge -> Notifications. Reminders stop; nothing else changes.

## Children's Privacy

- Our app is **not intended for children under 13**.
- We do not knowingly collect data from children under 13.
- If you are a parent or guardian and believe your child has provided personal information, please contact us to request deletion.
- Parents and guardians should supervise children's use of apps that store personal content.

## Security

- Local data is protected by Android's application sandbox. HabitForge is an Android app only; there is no web or browser version of it.
- The app makes no network connections, so there is no network traffic to secure.
- There are no third-party services in this app.
- You are responsible for protecting your device, which for this app means a screen lock.
- We do not sell your personal data. We never receive it.

## Changes to This Policy

We may update this Privacy Policy to reflect new features, legal requirements, or changes in our practices. Significant changes will be:
- Noted in the app release notes or repository when applicable
- Reflected with a new "Last updated" date
- Communicated in the app or project page if the change is significant

The "Last updated" date at the top of this policy indicates when revisions occurred. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, wish to request data deletion, or have privacy concerns:

* **GitHub Repository:** https://github.com/SUDARSHANCHAUDHARI/habitforge-privacy-policy
* **Email:** sunny.sudarshan@gmail.com
* **Main App Repository:** https://github.com/SUDARSHANCHAUDHARI/HabitForge

We will respond as quickly as possible, typically within 48 hours.

## Data Deletion

### How to Delete Your Account:
This app does not require an account. You can delete local app data using the options below:

#### Option 1: In-App Deletion
1. Open HabitForge
2. Delete individual entries, reminders, history, or settings where the app provides controls
3. Or clear the app's data from Android Settings
4. Uninstalling the app also removes local app-private data

#### Option 2: Email Deletion Request
Send an email to: **support@sudarshantechlabs.com** or **sunny.sudarshan@gmail.com**
- Subject: "Data Deletion Request - HabitForge"
- Include: The email/account identifier used in the app, if any
- We will process deletion requests as quickly as possible, typically within 48 hours for acknowledgement

#### Option 3: Web Deletion
1. Visit the privacy policy website for contact and support information
2. Uninstalling the app removes its local data
3. For Android apps, clear storage from Android Settings if you want a full local reset

### What Gets Deleted:
- Local app data stored by the app
- Local preferences and reminder/history records
- Cached data controlled by the app
- Exported/shared files only if you delete them from where you saved them

### Data Retention After Deletion:
- **Immediate:** clearing app data removes local app-private data from your device
- **Uninstall:** removes app-private local data from Android apps
- **Exports/shared files:** remain wherever you saved or sent them until you delete them

To request deletion of your data:

1. Open HabitForge, if installed
2. Delete local content or clear app/site data where applicable
3. Contact support via email: sunny.sudarshan@gmail.com
4. Request account/data deletion and include enough detail for us to identify the app and any account, if one exists
5. We will confirm what data can be deleted and complete the request according to the retention terms above

## Third-Party Services

**HabitForge uses none.** No Firebase, no Google Play Billing, no analytics, no advertising, no backend of ours.

The only third-party policy with any bearing on the app is Google Play's, because that is where you installed it from:

- [Google Play Terms](https://play.google.com/about/play-terms/)

## About HabitForge

HabitForge is built with privacy in mind. The app is built with:
- Kotlin and Jetpack Compose
- Room/DataStore for local storage
- WorkManager for reminders

That is the whole list. There is no networking library in it, because the app makes no network calls: your data stays on your device, not "whenever possible" but always.

---

**Last Updated:** November 9, 2026

---

## Recent Updates (Version 1.2.0 - November 9, 2026)

- **Removed Google Play Billing and the premium tier.** The app has no in-app purchases. This policy described billing in seven places, including a permission entry saying `INTERNET` was "used for Google Play Billing".
- **Removed Firebase.** The policy named it as a security control; the app has never shipped it. The Firebase lines in its build file are commented out, on every branch.
- **Stated that the app declares no `INTERNET` permission.** Without it Android will not let the app open a network connection, which is why this policy can now say flatly that habit data cannot leave the device rather than hedging with "network communication uses HTTPS/TLS where applicable".
- **Listed the four permissions WorkManager merges in** — `WAKE_LOCK`, `RECEIVE_BOOT_COMPLETED`, `FOREGROUND_SERVICE` and `ACCESS_NETWORK_STATE` — and explained that the last of those lets a library *check* for a network but not use one. The app declares one permission; the finished build carries five.
- **Removed the scaffold text** that this policy shared with our other apps: a "Family Groups" heading for an app with no sharing features, and references to a browser, a browser profile and GitHub accounts. HabitForge is an Android app with no web version.
- **Said there are no third parties at all**, in place of a services list that named Google Play Billing and linked the Firebase and GitHub privacy policies.

## Recent Updates (Version 1.1.0 - May 17, 2026)

- **Aligned policy with the shared privacy-policy structure.**
- **Clarified local habit data, photos, notifications, and billing.**
