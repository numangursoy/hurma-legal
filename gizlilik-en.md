# Hurma — Privacy Policy

**Last updated:** 30 August 2026

Hurma is a mobile app that teaches you to read the Qur'an. This policy explains what data is processed when you use the app.

---

## In short

- We do not sell your data to anyone, and we do not share it for marketing.
- The app contains **no advertising**; no ad or analytics tool is used.
- We use no usage analytics or behavioural tracking tools.
- Even when we access your contacts, **your contact data never leaves your device**.
- You can permanently delete your account and all your data from inside the app.

---

## 1. Data we collect

### Account information
When you create an account:

- **Your email address** — required so you can sign in.
- **Your password** — stored by our infrastructure provider (Supabase) in an irreversibly hashed form. We cannot see your password in plain text. If you sign in with Google or Apple, no password is ever created.

If you choose to sign in with Apple or Google, we receive only your email address and (if you chose to share it) your name from those providers.

### Profile information
After registration you are asked to complete your profile:

- **Your first and last name**
- **Your age**
- **Your gender**

This information is saved to your account. Age is asked so the app can enforce its 13-year age limit.

### Your learning progress
So you can pick up where you left off, the following is saved to your account:

- Your total and weekly XP
- Your daily streak and your streak freezes
- Your heart count and the time they last refilled
- The sections you completed and how many times you played them
- The list of words you struggled with (used for review exercises)
- Your notification preference and your device notification token
- The date you were last active

### Data that stays on your device
So the app works without an internet connection, it keeps a copy of the above on your device. If you delete the app, that copy is deleted too.

---

## 2. Contacts access

If you want to invite friends, the app **asks permission** to access your contacts. If you decline, the app keeps working exactly as before.

If you grant permission:

- Your contacts are read and listed **on your device only**.
- Contact data is **never uploaded** to our servers, never stored, and never shared with anyone.
- When you pick a person, your phone's own share sheet opens and **you** send the invitation.

---

## 3. Leaderboard

The app has a weekly and an all-time leaderboard. Other signed-in users can see **your display name and your XP** there. Your email address, surname, age and gender are **not shown** on the leaderboard.

If you do not want your name shown, you can change it from the profile screen.

---

## 4. Subscription

**This version contains no in-app purchases.**

If a **hurma+Premium** subscription is enabled in future, payment will be processed through the Apple App Store and the **RevenueCat** service will be used to track subscription status. Your card details never reach us; payment happens entirely on Apple's side.

---

## 5. Data we do not collect

We **do not access or collect** any of the following:

- Your photos or files
- Your microphone or camera
- Usage analytics, behavioural tracking, cookie-based tracking
- Your advertising identifier (IDFA)

The app contains **no advertising SDK, no analytics tool and no behavioural tracking SDK**. There is no third-party tracking of any kind. The app does not track you across other apps or websites, and for that reason no App Tracking Transparency prompt is shown on iOS.

Your location is accessed only to calculate prayer times, and only if you grant permission. Your location is **not sent to our servers**; it is passed to the prayer-time service that performs the calculation (see section 7). Granting it is optional — you can type your city in instead.

---

## 6. Why we process your data

| Purpose | Data |
|---|---|
| So you can sign in to your account | Email, password |
| So your progress is not lost and returns when you change device | XP, streak, completed sections |
| To offer you suitable review exercises | Words you struggled with |
| To send you a daily reminder notification | Notification preference, device notification token |
| To display the leaderboard | Display name, XP |
| To enforce the 13-year age limit | Age |
| To calculate prayer times | The city you select (or your location, if you allowed it) |

The legal basis for this processing is the performance of the service agreement between us, and your explicit consent (for notifications, contacts access and location).

---

## 7. Where data is stored and how it is shared

Your account and progress data are stored on **Supabase** infrastructure. Supabase only hosts data on our behalf; it does not use your data for its own purposes. The database is protected by row-level security (RLS): each user can access only their own record. For the leaderboard, only the display name and score fields are exposed to other users.

Email delivery (password reset, address verification) is handled through **Brevo**; only your email address is passed to that service.

### Audio files
The app streams letter and verse audio at playback time from these two sources. The audio is never downloaded, copied or redistributed:

- `kuran.diyanet.gov.tr` — publicly available alphabet (letter and vowel-mark) recordings of the Presidency of Religious Affairs of Türkiye (Diyanet)
- `audio.qurancdn.com` — Quran Foundation; verse recitation and word-by-word pronunciation. Hurma is a registered developer with Quran Foundation and operates under its developer terms.

When an audio file is played, those servers see your device's IP address, as with any internet request. No information about your account is sent to those servers.

### Prayer times and weather
Prayer times are calculated through `api.aladhan.com` (Aladhan). If you granted location permission your coordinates are sent to that service; if you did not, only the name of the city you selected is sent.

For the temperature and weather effect on the personalisation screen we use `api.open-meteo.com`, and for city search `geocoding-api.open-meteo.com` (Open-Meteo); those receive only coordinates or the city name you are searching for.

Neither service requires an account. The requests we send them carry no name, e-mail, account or anything else that identifies you — as with any internet request, they see your device's IP address.

Apart from this, we **share your data with no third party**. Sharing may occur only where legally required (a court order, for example).

---

## 8. Notifications

Daily reminders are scheduled **locally on your device**. If you have an account, your device notification token is stored against that account — it is used solely to send you notifications, is processed for no other purpose, and is shared with no one. You can turn notifications off from the app's settings or from your phone's settings.

---

## 9. Deleting your account

You can delete your account from inside the app at any time:

**Profile → Delete my account**

Once you confirm, your account, your progress and all your records are permanently deleted. This cannot be undone.

You may also request deletion by writing to the email address below.

---

## 10. How long data is kept

Your data is kept for as long as your account remains open. When you delete your account, the data is deleted immediately; clearing it from backups may take up to 30 days.

---

## 11. Children's privacy

The app is intended for users **aged 13 and over**. Age is asked during registration. Users under 13 should use the app under parental supervision; we do not knowingly collect data from anyone under 13. If we become aware of such a record, we delete the data.

---

## 12. Your rights

You have the right to access, correct and delete your data, and to object to its processing. To exercise these rights, please contact us at the address below.

---

## 13. Changes

If this policy changes, we will update this page and change the "last updated" date. For significant changes, we will also inform you inside the app.

---

## 14. Contact

For questions:

**Email:** numangrsy@gmail.com

---

*Hurma is an independent app. It has no official affiliation with the Presidency of Religious Affairs (Diyanet); the audio recordings are taken from the Presidency's publicly available alphabet materials.*
