# FitQuick Privacy Policy

**Effective Date:** May 17, 2026
_Last updated: November 8, 2026_
**Version:** 1.3.0

FitQuick ("we," "our," or "us") is an Android app. FitQuick is a fitness companion for Android with workout logging, progress tracking, reminders, camera progress photos, ads, and premium features. This Privacy Policy explains what information the app collects, how it is used, and the choices you have. By installing or using FitQuick you agree to the practices described below.

## Information We Collect

### Location Data
- FitQuick does not collect location data.

### Account Information
- No FitQuick account is required for core use.
- Google Play Billing may process purchase status for premium features.

### Device Information
- Workout goals, exercise logs, progress, reminders, camera progress photos, app preferences, analytics events, crash reports, and advertising identifiers may be processed as described below.

## How We Use Your Information

### Location Sharing
- FitQuick does not use your location.

### Account Management
- Generate workout plans and track local progress.
- Manage premium entitlement status through Google Play Billing.
- Show ads in the free tier through Google AdMob.

### Service Improvement
- Use Firebase Analytics and Crashlytics to improve reliability and understand broad usage patterns.
- Keep your workout data on your device; the app does not send it to a Sudarshan Tech Labs server.
- We do not sell your fitness data.

## Storage and Retention

### Data Storage
- Workout plans, logs, preferences, and reminders are stored locally using on-device storage such as Room/DataStore.
- Progress photos you take stay in the app's private storage on your device and are not uploaded to Sudarshan Tech Labs servers.
- Firebase may receive analytics and crash information; AdMob may process advertising identifiers for ads.

### Data Retention
- Local workout data remains until you delete it, clear app data, or uninstall the app.
- Firebase and AdMob retain diagnostic, analytics, and ad data according to their policies.

### Data Security
- On your device, your workout data and progress photos sit in the App's private storage, protected by Android's application sandbox.
- In transit to the three Google services named in this policy — Firebase Analytics, Firebase Crashlytics and AdMob — data is protected by those services' own transport security, and their handling of it is governed by Google's privacy policy rather than ours.
- No Sudarshan Tech Labs server exists, so there is no third location holding your data.
- Your workout data stays on your device. Only the analytics events, crash reports and advertising data named in this policy leave it.
- Network communication uses HTTPS/TLS.
- You should protect your device and your Google account with strong authentication, since your Play purchases and the Google services above are tied to it.

## Data Sharing

### Sharing with other people
- FitQuick has no pairing, sharing, family-group or collaboration feature. Your workout data is not shared with any other person through the App.

### Third Parties
- Firebase Analytics and Crashlytics for app quality.
- Google AdMob for ads in the free tier.
- Google Play Billing for purchases.

We do **not** share your data with:
- Data brokers
- Unrelated advertising networks, unless advertising is explicitly listed above for this app
- Third parties unrelated to the app features described in this policy

## Permissions Used

### Required Permissions

* **INTERNET and ACCESS_NETWORK_STATE**: Used for Firebase, AdMob, and billing.
* **CAMERA**: Used only to take progress photos when you choose to.
* **POST_NOTIFICATIONS, RECEIVE_BOOT_COMPLETED, WAKE_LOCK, and VIBRATE**: Used for workout reminders.
* **AD_ID**: Used by Google AdMob where available for advertising.
* **ACCESS_ADSERVICES_AD_ID, ACCESS_ADSERVICES_ATTRIBUTION, ACCESS_ADSERVICES_TOPICS**: Declared by the AdMob library for Android's Privacy Sandbox advertising APIs. These cover the advertising identifier, ad attribution, and the Topics API used for interest-based ads. They arrive with AdMob rather than being requested by FitQuick's own code.
* **FOREGROUND_SERVICE and BIND_JOB_SERVICE**: Declared by WorkManager, which schedules the workout reminders.
* **DUMP**: Declared by a build-time library. Android grants it only to system apps, so it has no effect here.

The App's own manifest declares seven permissions; the finished build carries thirteen, the rest arriving with the Google libraries above. The list you see on the Play Store is the full merged set, which is why all of them appear here.

### Optional Permissions

* Progress photos, notifications, and premium purchases are optional user-controlled features.

## Your Rights and Controls

### Location Sharing Control
- No location sharing exists in FitQuick.

### Account Management
- No FitQuick account is required; Google Play purchases are managed through your Google account.

### Data Access
- You can view, edit, or delete workout history and preferences inside the app.

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
- You can revoke Android permissions in Android Settings -> Apps -> FitQuick -> Permissions.
- Revoking the camera permission stops progress photos; the rest of the app continues to work.
- You can reset or delete your advertising ID in Android Settings -> Privacy -> Ads, which limits ad personalisation.

## Children's Privacy

- Our app is **not intended for children under 13**.
- We do not knowingly collect data from children under 13.
- If you are a parent or guardian and believe your child has provided personal information, please contact us to request deletion.
- Parents and guardians should supervise children's use of apps that store personal content.

## Security

- Local data is protected by Android's application sandbox.
- Network communication uses HTTPS/TLS.
- The Google services named in this policy provide their own security controls and privacy policies.
- You are responsible for protecting your device and your Google account credentials.
- We do not sell your personal data.

## Changes to This Policy

We may update this Privacy Policy to reflect new features, legal requirements, or changes in our practices. Significant changes will be:
- Noted in the app release notes or repository when applicable
- Reflected with a new "Last updated" date
- Communicated in the app or project page if the change is significant

The "Last updated" date at the top of this policy indicates when revisions occurred. Continued use of the app after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, wish to request data deletion, or have privacy concerns:

* **GitHub Repository:** https://github.com/SUDARSHANCHAUDHARI/fitquick-privacy-policy
* **Email:** sunny.sudarshan@gmail.com
* **Main App Repository:** https://github.com/SUDARSHANCHAUDHARI/FitQuick

We will respond as quickly as possible, typically within 48 hours.

## Data Deletion

### How to Delete Your Account:
This app does not require an account. You can delete local app data using the options below:

#### Option 1: In-App Deletion
1. Open FitQuick
2. Delete individual entries, reminders, history, or settings where the app provides controls
3. Or clear app data from Android Settings -> Apps -> FitQuick -> Storage
4. Uninstalling the app also removes local app-private data

#### Option 2: Email Deletion Request
Send an email to: **support@sudarshantechlabs.com** or **sunny.sudarshan@gmail.com**
- Subject: "Data Deletion Request - FitQuick"
- Include: The email/account identifier used in the app, if any
- We will process deletion requests as quickly as possible, typically within 48 hours for acknowledgement

### What Gets Deleted:
- Local app data stored by the app, including your workout history and progress photos
- Local preferences and reminder records
- Cached data controlled by the app
- Exported or shared files only if you delete them from where you saved them

### Data Retention After Deletion:
- **Immediate:** clearing app data removes local app-private data from your device
- **Uninstall:** removes app-private local data
- **Already sent to Google:** analytics events, crash reports and advertising data already transmitted are held by Google under their own retention policies, not ours. Clearing app data does not recall them
- **Exports/shared files:** remain wherever you saved or sent them until you delete them

To request deletion of your data:

1. Open FitQuick, if installed
2. Delete local content or clear app/site data where applicable
3. Contact support via email: sunny.sudarshan@gmail.com
4. Request account/data deletion and include enough detail for us to identify the app and any account, if one exists
5. We will confirm what data can be deleted and complete the request according to the retention terms above

## Firebase and Google Services

This app may use the following services depending on the features you enable and the installed version:

- Firebase Analytics
- Firebase Crashlytics
- Google AdMob
- Google Play Billing

Please review relevant third-party privacy policies:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Firebase Privacy Policy](https://firebase.google.com/support/privacy)
- [Google Play Terms](https://play.google.com/about/play-terms/)
- [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)

## About FitQuick

FitQuick is built with privacy in mind. The app is built with:
- Kotlin and Jetpack Compose
- Room/DataStore for local fitness data
- Firebase, AdMob, and Google Play Billing integrations

The app collects only the data needed for the features described in this policy, and local-first features keep data on your device whenever possible.

---

**Last Updated:** November 2, 2026

---

## Recent Updates (Version 1.3.0 - November 8, 2026)

- **Replaced a boilerplate security sentence** that claimed data was protected by "Android, the browser, Firebase, Google, GitHub, or other services". FitQuick uses no browser and no GitHub service. The section now describes where data actually sits: app-private storage on your device, and in transit to the three named Google services.
- **Listed the permissions that arrive with the Google libraries.** The App's own manifest declares seven; the finished build carries thirteen. The additions are the Privacy Sandbox advertising permissions (`ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS`), `FOREGROUND_SERVICE` and `BIND_JOB_SERVICE` from WorkManager, and `DUMP`. The Play Store shows the merged set, so all of them belong here.
- **Replaced the hedged "Family Groups" wording** with a plain statement: FitQuick has no pairing, sharing or family-group feature.

## Recent Updates (Version 1.2.0 - November 2, 2026)

- **Removed the Google Gemini AI workout generation and camera form-check sections.** Those features were taken out of the app, so the policy no longer describes them.
- **Clarified that the camera is used only for progress photos, which stay on your device.**

## Recent Updates (Version 1.1.0 - May 17, 2026)

- **Aligned policy with the shared privacy-policy structure.**
- **Clarified fitness data, camera form checks, Firebase diagnostics, AdMob ads, billing, and Gemini AI.**
