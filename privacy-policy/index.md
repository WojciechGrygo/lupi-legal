# Privacy Policy 🛡️
**Effective Date:** February 25, 2026  
**Version:** 1.0.0

## 🟢 The “Privacy-First” Summary (TL;DR)
- **No Accounts:** You don’t need to sign up. We don’t know who you are.
- **On-Device Storage:** Your financial data (subscriptions, prices, notes) never leaves your phone. It is stored in a private local database, not on our servers.
- **Minimal Telemetry:** We use anonymous analytics to improve our app and fix bugs. Your financial data (amounts, notes) remains 100% private and stays on your device.

## 1. Our Privacy Philosophy
Lupi (the “App”) was built on the principle of Zero Knowledge. We believe your financial life is your business. Our architecture ensures that your sensitive data remains under your physical control at all times.

## 2. Information We Handle

### A. Data Stored Locally (By You)
All records of your expenses, custom categories, and notes are saved directly to your device’s internal storage using a secure SQLite database.
- **Access:** Only you can see this data.
- **Backup:** Your data is included in your standard device backups (e.g., iCloud or Google Backup), managed by your OS.

### B. Technical Interactions (The Internet)
To make the App useful, we perform specific, limited network requests. These requests do not contain your personal financial records:
- **Currency Conversion:** We fetch the latest rates from Frankfurter API.
- **Brand Identity:** When you search for a subscription (e.g., "Netflix"), we send the query to Brandfetch API to retrieve the official logo and colors. This is a visual feature only; we do not track or store what you search for.
- **Notifications:** Notifications (reminders) are scheduled and processed strictly locally on your device. We do not transmit or store push notification tokens on any external servers.
- **Usage & Stability Insights:** We use Firebase Crashlytics & Analytics to monitor app performance, collect anonymous usage data, and fix technical bugs. This data contains technical logs, device models, and stack traces only. It does not include your financial records, subscription names, or any personal identifiers.

### C. Premium Subscriptions & Purchases
Lupi offers Premium features via in-app purchases. 
- **Payment Processing**: All transactions are handled entirely and securely by the **Apple App Store** or **Google Play Store**.
- **Financial Privacy**: We never have access to, nor do we store, your credit card numbers, bank account details, or billing addresses.
- **Anonymized Validation**: We use **RevenueCat** to verify your PRO status anonymously. This process does not link your financial identity to your personal identity.
- **Platform Terms**: All purchases are subject to the respective store's terms and privacy policies (Apple Media Services or Google Play Terms of Service).

### D. User Support & Feedback
If you choose to use our in-app feedback form, your message, along with any provided contact information (e.g., email address) and basic app information (specifically: your platform, e.g., iOS or Android, and the App version), is sent directly to the developer via EmailJS. This information is used solely to provide support, troubleshoot issues, and improve the App.

## 3. Trusted Partners
We only connect to services that are essential for the App’s functionality.

| Service | Why we use it | Privacy Info |
| :--- | :--- | :--- |
| **Frankfurter API** | Real-time currency exchange | [Public Domain / Open Source](https://github.com/hakanensari/frankfurter) |
| **Brandfetch API** | Visualizing your subscriptions | [Privacy Policy](https://brandfetch.com/privacy-policy) |
| **Apple / Google** | App distribution & Payment Processing | [Apple Privacy](https://www.apple.com/legal/privacy/) / [Google Privacy](https://policies.google.com/privacy) |
| **Firebase (Google)** | Crash reporting & anonymous app analytics | [Privacy Policy](https://firebase.google.com/support/privacy) |
| **RevenueCat** | Validating PRO subscriptions & purchases | [Privacy Policy](https://www.revenuecat.com/privacy/) |
| **EmailJS** | Processing user feedback (if you use the contact form) | [Privacy Policy](https://www.emailjs.com/legal/privacy-policy/) |

## 4. Total Control: Data Deletion
You are the owner of your data.
- **Manual Reset:** You can wipe all data instantly using the “Clear Data” feature in Settings.
- **App Uninstallation:** Deleting the App from your device automatically destroys the local database.

## 5. Global Compliance (GDPR & CCPA)
Although we do not “collect” personal data in the traditional sense, we comply with global standards:
- **GDPR (Europe):** The legal basis for processing is the performance of the contract (providing the app’s features).
- **CCPA (California):** We do not “sell” or “share” your personal information.
- **Opt-out / Opt-in:** You can enable or disable anonymous analytics and crash reporting at any time via the Settings menu within the App. By default, these features are OFF until you decide to help us improve Lupi (Opt-in approach).

## 6. Children’s Privacy (COPPA)
This App is not directed to individuals under the age of 13 (or the legal age in your jurisdiction). We do not knowingly collect personal information from children. If you become aware that a child has provided us with personal information, please contact us so we can take steps to delete such information.

## 7. Changes to this Policy
We may update this Privacy Policy from time to time. If we make material changes, we will update the "Effective Date" at the top of this document. We encourage you to review this policy periodically.

## 8. Contact & Support
If you have questions about our “Local-First” approach, please reach out to the developer:
- **Wojciech Grygo**
- **Email:** grygo.wojtek@gmail.com
