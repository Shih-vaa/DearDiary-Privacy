## Privacy Policy
> **Note:** This policy was drafted by auditing the app's actual code paths (what data it touches, where it sends it, and what third-party SDKs are wired in), not written from a template. It's a solid starting point, but isn't legal advice — have it reviewed before publishing, especially the Google Sign-In section, since Google's API Services User Data Policy has its own specific disclosure requirements.
>
> This file is the source copy. The version Play Console and end users should link to is the published one: **https://shih-vaa.github.io/deardiary-legal/privacy.html** (this repo is private, so this file itself isn't publicly reachable — that URL is served from the separate public  repo, which should be kept in sync with this file by hand when either changes).

## Summary

DearDiary is a journaling app. Your diary entries, doodles, and images are stored **only on your device** unless you explicitly turn on Google Drive backup. Creating an account (email or Google Sign-In) stores your login and basic profile info (name, and whatever else you choose to add) with our backend provider, Supabase. Crash reports go to Sentry. Nothing is sold or shared with advertisers.

## Information We Collect

**Account information.** If you sign up with email, we store that email and an encrypted password (handled by Supabase Auth). If you use Sign in with Google, we receive your Google account's basic identity (email, name) via OAuth, along with a token scoped for Google Drive's app-private storage (see Backup, below).

**Profile information.** Anything you enter on the Profile screen — display name, bio, age, profile photo — is stored in our database (Supabase). All of these except your name are optional.

**Diary content.** Everything you write, draw, or paste into a diary — text, doodles, embedded images, page titles — is stored **locally on your device** in a private, sandboxed database. We do not receive or have access to this content unless you turn on backup.

**Backup (optional, off by default).** If you enable Google Drive backup, your entire diary — every book, page, doodle, and embedded image — is uploaded to a hidden, app-private folder in *your own* Google Drive (Google's ), which only this app, authenticated as you, can read. It does not appear in your regular Drive file list. This upload is protected by your Google account's access controls but is **not separately encrypted** by the app before it's sent — please don't rely on it as an encrypted backup in the cryptographic sense.

**Crash and diagnostic data.** We use Sentry to catch crashes and errors. This can include your device type, OS version, IP address, and — for a sample of sessions (10% of normal sessions, 100% of sessions that hit an error) — a masked screen recording (text and images are masked by default) to help us understand what led to a bug.

**Device permissions.**
- *Photo library:* used to pick a profile photo or embed images in a diary page. Selected photos stay on your device (and are included in backup uploads only if you enable backup).
- *Biometrics / PIN:* if you set an app lock, your PIN and the fact that biometric unlock is enabled are stored locally on your device only (never transmitted anywhere).
- *Notifications:* used only for the optional journaling reminders you configure, scheduled entirely on-device.

## How We Use Information

- To create and secure your account.
- To sync your profile across devices you sign into.
- To back up your diary to your own Google Drive, only when you ask us to.
- To diagnose crashes and fix bugs.
- To send the reminder notifications you set up.

We do not use your diary content for analytics, advertising, or any purpose beyond storing and displaying it back to you.

## Third-Party Services

- **Supabase** (authentication, profile storage) — [supabase.com/privacy](https://supabase.com/privacy)
- **Google** (Sign-In, Drive backup storage) — [policies.google.com/privacy](https://policies.google.com/privacy). Our use of Google user data via Sign-In complies with the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.
- **Sentry** (crash reporting, session replay) — [sentry.io/privacy](https://sentry.io/privacy/)

## Data Retention and Deletion

Diary content lives on your device until you delete it there, or delete a backup copy from your Google Drive's app data directly. Account and profile data (email, name, bio, etc.) is retained until you ask us to delete it.

**To delete your account and associated data:**
- **In the app:** open **Profile** and tap *- **In the app:** open **Profile** and tap *- **In the app:** open **Profile** and tap *- **In the app:** open **Profilisit- **In the app:** open pa- **In the app:** open **Profile** and tap *- **In the app:** open **Profile** and tap *- **In the app:me - **In the app:** open **Profile** and tap *- **In the app:** open **Profile** and tap *- **In the app:** open **Profile** and tap *- **In the app:** open **Profilisit- **In the app:** open pa- **In the app:** open **Profile** and tap *- **In the app:** open **Profile** and tap *- **In the app:me - **In the app:** openDr- **In the app:** open **Profile** and tap *- **In the app:** open **Profile** and tap *- **InearDiary is not directed at children under 13, and we do not knowingly collect information from them.

## Your Choices

- Backup is opt-in — leave it off and your diary never leaves your device.
- You can edit or remove most profile fields at any time from the Profile screen.
- You can disable notifications from your device's system settings.

## Changes to This Policy

If this policy changes in a way that matters, we'll update the date at the top and, for significant changes, note it in the app.

## Contact

Questions about this policy or your data: **shiva.zen.dev@gmail.com**
