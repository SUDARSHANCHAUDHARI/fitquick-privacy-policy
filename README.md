# FitQuick — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

FitQuick is an AI-powered fitness companion for Android. It provides personalised workout plans via Google Gemini AI, progress tracking, workout reminders, and optional camera-based form checking. The App uses Firebase for analytics and crash reporting, and Google AdMob for advertisements.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Workout logs and exercise history | Progress tracking | Room database on your device |
| User fitness preferences (goals, level) | Personalisation and AI plan input | DataStore on your device |
| Camera photos (exercise form capture) | Optional form checking | App private storage on your device |
| App settings | Personalisation | DataStore on your device |

### Data Collected by Third-Party Services

**Firebase Analytics:**
- App usage events (e.g., workout started, plan generated, screen views)
- Device model, OS version, app version, language, and country
- Session duration and navigation paths
- No personally identifiable information (name, email) is included

**Firebase Crashlytics:**
- Device model, OS version, app version
- Crash stack traces and error logs
- No workout data or personal information is included in crash reports

**Google AdMob:**
- Android Advertising ID (AAID) for ad personalisation
- Device information for ad targeting
- For details: https://policies.google.com/technologies/ads

**Google Gemini API (user-initiated):**
When you request an AI workout plan, your fitness preferences (goals, fitness level, available equipment) are sent to the Gemini API. Sudarshan Tech Labs does not store this data on its servers.

**Google Play Billing:**
In-app purchase transactions are processed by Google Play. Sudarshan Tech Labs does not receive or store payment information.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Track and display workout history | Local workout logs |
| Generate AI workout plans | Fitness preferences sent to Gemini API |
| Display scheduled workout reminders | Local WorkManager tasks |
| Improve app quality | Firebase Analytics events |
| Fix app crashes | Firebase Crashlytics reports |
| Display advertisements | AdMob (Advertising ID) |

---

## Data Storage and Security

- **Local data:** Protected by Android's application sandboxing
- **Firebase:** Google's infrastructure with encryption in transit (HTTPS/TLS) and at rest
- **Camera photos:** Stored in the App's private directory, not accessible to other apps
- **API keys:** Stored securely, not exposed in the App

## Data Retention

| Data | Retention |
|---|---|
| Local workout data | Until you delete it or uninstall the App |
| Firebase Analytics | Aggregated data, 14 months (Firebase default) |
| Firebase Crashlytics | 90 days (Firebase default) |
| AdMob data | Managed by Google per their privacy policy |

---

## Data Sharing

We do not sell your data. Data is shared only with:

- **Google (Firebase Analytics, Crashlytics, AdMob, Gemini, Play Billing):** https://policies.google.com/privacy

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `INTERNET` | Required for Firebase, AdMob, and Gemini API |
| `ACCESS_NETWORK_STATE` | Check connectivity before network calls |
| `CAMERA` | Optional — capture exercise form photos |
| `READ_EXTERNAL_STORAGE` | Access files on Android 9 and below |
| `WRITE_EXTERNAL_STORAGE` (Android 9 and below) | Save files on Android 9 and below |
| `WAKE_LOCK` | Prevent screen sleep during an active workout |
| `VIBRATE` | Haptic feedback for workout alerts |
| `RECEIVE_BOOT_COMPLETED` | Reschedule workout reminders after device restart |
| `POST_NOTIFICATIONS` | Send workout reminder notifications |

---

## Your Rights and Controls

- **Delete local data:** Uninstall the App or go to Android Settings > Apps > FitQuick > Storage > Clear Data
- **Opt out of personalised ads:** Android Settings > Privacy > Ads > Opt out of Ads Personalisation
- **Reset Advertising ID:** Android Settings > Privacy > Ads > Reset advertising ID
- **Delete individual workout entries:** Use the delete option within the App

---

## Children's Privacy

FitQuick is not directed at children under 13. We do not knowingly collect personal information from children.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of FitQuick after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## GDPR Rights (EU Users)

If you are in the European Economic Area, you have the right to:

- **Access** — Request a copy of your personal data
- **Rectification** — Correct inaccurate data
- **Erasure** — Request deletion of your data
- **Restrict Processing** — Limit how we use your data
- **Data Portability** — Receive your data in a portable format
- **Object** — Object to certain types of processing

To exercise these rights, contact us at the details above.

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| App interactions | Yes (Firebase Analytics) | No | Analytics |
| Crash logs | Yes (Crashlytics) | No | App stability |
| Advertising ID | Yes (AdMob) | Google | Advertising |
| Fitness preferences | On request | Google (Gemini) | AI plan generation |
| Workout logs | Local only | No | — |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21
