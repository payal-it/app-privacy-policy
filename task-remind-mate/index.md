# Privacy Policy — Task Remind Mate

**Last updated: June 2025**

This Privacy Policy describes how Task Remind Mate ("the app", "we", "our") collects, uses, and protects your information when you use our Android application.

---

## 1. About the App

Task Remind Mate is a voice-first reminder application designed for Indian-language users. The app lets you create reminders by speaking naturally in Hindi, Tamil, Gujarati, Marathi, or English. Reminders are stored securely in the cloud and delivered as local notifications on your device.

---

## 2. Information We Collect

We collect only what is necessary to provide the service.

### 2.1 Reminder Data
- The title, description, date, time, and recurrence settings of reminders you create.
- Stored in Google Firebase Firestore, associated with your account.

### 2.2 Account Information
- If you sign in with Google: your name, email address, and profile photo (provided by Google).
- If you use the app without an account: an anonymous Firebase ID is created automatically — no personal information is collected.

### 2.3 Voice Input
- Voice transcripts are processed entirely **on your device** using the Android Speech Recognition API.
- Audio recordings are **never sent to our servers**.

### 2.4 SMS Messages (Optional — Off by Default)
- The app may request the **READ_SMS** permission if you enable the "Parse reminders from SMS" feature in Settings.
- When enabled, the app reads your inbox messages **locally on your device** to suggest reminders from appointment or bill messages.
- SMS messages are **never transmitted to any server**, stored in the cloud, or shared with any third party.
- This feature is **disabled by default**. You can turn it on or off at any time in Settings.

---

## 3. How We Use Your Information

Your data is used solely to:

- Display and manage your reminders within the app.
- Schedule local notifications at the times you specify.
- Sync your reminders across your devices when signed in with a Google account.
- Improve app functionality (aggregate, anonymised usage — no personal data).

We do **not** sell, share, rent, or use your data for advertising or marketing.

---

## 4. Data Storage and Security

- Your reminder data is stored in **Google Firebase Firestore** with strict security rules that ensure only your account can access your data.
- Data is transmitted over encrypted HTTPS connections.
- Anonymous users' data is stored temporarily and will be deleted when the app is uninstalled and the anonymous account is deleted.

---

## 5. Third-Party Services

The app uses the following Google services, each governed by [Google's Privacy Policy](https://policies.google.com/privacy):

| Service | Purpose |
|---|---|
| Firebase Authentication | Secure sign-in (anonymous or Google account) |
| Firebase Firestore | Cloud storage for your reminders |
| Google Sign-In | Optional Google account linking |

No other third-party analytics, advertising, or tracking SDKs are used.

---

## 6. Permissions Used

| Permission | Why it is needed |
|---|---|
| `POST_NOTIFICATIONS` | To deliver reminder notifications on time |
| `SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM` | To fire reminders at the exact time you set |
| `RECEIVE_BOOT_COMPLETED` | To reschedule alarms after device restart |
| `RECORD_AUDIO` | For voice input (microphone) — only active when you tap the mic button |
| `READ_SMS` | **Optional.** Only requested if you enable "Parse reminders from SMS" in Settings. Messages are processed locally and never uploaded. |
| `INTERNET` | To sync reminders with Firebase and sign in with Google |

---

## 7. Data Retention and Deletion

- Your reminders are retained as long as your account is active.
- You can delete individual reminders at any time from within the app.
- To delete **all your data**: sign out of the app and uninstall it. This removes the anonymous Firebase account and all associated reminders.
- For Google-signed-in accounts, you may request complete data deletion by contacting us (see Section 10).

---

## 8. Children's Privacy

Task Remind Mate is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us and we will delete it promptly.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top of this page. We encourage you to review this policy periodically. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 10. Contact Us

For privacy questions, data access requests, or data deletion requests:

**Email:** payal.dev.apps@gmail.com  
**App name:** Task Remind Mate  
**Package:** com.pdev.taskremindmate  

We will respond to all requests within 30 days.

---

*This privacy policy was last reviewed for compliance with Google Play Store requirements including READ_SMS permission usage, Firebase data handling, and user data deletion procedures.*
