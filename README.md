# Privacy Policy — FitQuick

**Last updated:** 2026-03-21
**Effective date:** 2026-03-21

This Privacy Policy describes how **Sudarshan Tech Labs** ("we", "us", or "our") handles information in the **FitQuick** Android application ("the App").

---

## 1. About This App

FitQuick is a fitness application providing AI-generated workout plans, exercise guidance, progress tracking, and workout reminders. The App uses Firebase services for analytics and crash reporting, and Google AdMob for advertisements.

---

## 2. Data Collected

### 2.1 Data Stored Locally

| Data | Purpose | Storage |
|---|---|---|
| Workout logs and progress | Progress tracking | Room database (on-device) |
| Exercise preferences and settings | Personalisation | DataStore (on-device) |
| Camera photos (form check) | Exercise form capture | Device local storage |

### 2.2 Data Collected by Third-Party Services

**Firebase Analytics:**
- App usage events (e.g., workout started, plan generated)
- Device model, OS version, language
- Session duration and screen views
- No personally identifiable information is included in analytics events

**Firebase Crashlytics:**
- Crash reports including device model, OS version, and app version
- Stack traces at the time of a crash
- No personal fitness data is included in crash reports

**Google AdMob:**
- Advertising identifier (Android Advertising ID)
- Device information for ad targeting
- See Google's advertising privacy policy for details

**Google Gemini API:**
- When generating a workout plan, your fitness preferences (goals, fitness level) are sent to the Gemini API
- This data is used only to generate your plan and is not stored by Sudarshan Tech Labs

**Google Play Billing:**
- In-app purchase transactions are processed by Google Play
- We do not receive or store payment information

---

## 3. How Data Is Used

| Purpose | Legal Basis |
|---|---|
| Providing workout tracking functionality | App functionality |
| Generating AI workout plans (Gemini) | User-initiated request |
| Improving app quality (Firebase Analytics) | Legitimate interest |
| Fixing crashes (Firebase Crashlytics) | Legitimate interest |
| Displaying relevant advertisements (AdMob) | Legitimate interest / consent |

---

## 4. Data Sharing

We do not sell your personal data. Data is shared only with the following service providers for the purposes described above:

- **Google (Firebase Analytics, Crashlytics, AdMob, Gemini, Play Billing)** — see https://policies.google.com/privacy

No other third-party data sharing occurs.

---

## 5. Permissions Explained

| Permission | Reason |
|---|---|
| `INTERNET` | Required for Gemini AI, Firebase, and AdMob |
| `ACCESS_NETWORK_STATE` | Check connectivity before network calls |
| `CAMERA` | Optional — capture exercise form photos |
| `READ_EXTERNAL_STORAGE` (Android 9 and below) | Access files on legacy Android |
| `WRITE_EXTERNAL_STORAGE` (Android 9 and below) | Save files on legacy Android |
| `WAKE_LOCK` | Prevent screen sleep during active workout |
| `VIBRATE` | Haptic feedback for workout alerts |
| `RECEIVE_BOOT_COMPLETED` | Reschedule workout reminders after device restart |
| `POST_NOTIFICATIONS` | Send workout reminder notifications |

---

## 6. Data Retention

| Data | Retention |
|---|---|
| Local workout data | Until you delete it or uninstall the App |
| Firebase Analytics | Aggregated, retained per Firebase default (14 months) |
| Firebase Crashlytics | Retained per Firebase default (90 days) |
| AdMob data | Managed by Google per their privacy policy |

---

## 7. Your Rights

You may:
- Delete your local workout data via App Settings or by uninstalling the App
- Opt out of personalised ads via Android Settings > Privacy > Ads
- Reset your Advertising ID via Android Settings

---

## 8. Children's Privacy

FitQuick is not directed at children under 13. We do not knowingly collect personal information from children.

---

## 9. Data Security

- Local data is protected by Android's application sandbox
- All network communication uses HTTPS/TLS encryption
- Firebase services are secured per Google's infrastructure standards

---

## 10. Changes to This Policy

We will notify you of significant changes by updating the "Last updated" date. Continued use of the App constitutes acceptance.

---

## 11. Contact

**Sudarshan Tech Labs**
Official website: https://sudarshantechlabs.com
Company email: sudarshantechlabs@gmail.com
Developer contact: sunny.sudarshan@gmail.com

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| App interactions | Yes (Firebase Analytics) | No | Analytics |
| Crash logs | Yes (Crashlytics) | No | App stability |
| Advertising ID | Yes (AdMob) | Yes (Google) | Advertising |
| Fitness preferences | Yes (Gemini, user-initiated) | No | AI plan generation |
| Workout logs | No (stored locally only) | No | — |

---

*This policy applies to the FitQuick Android application published by Sudarshan Tech Labs.*
