# Privacy Policy 🛡️

**Effective Date: February 15, 2026**  
**Version: 1.0.0**

---

### 🟢 The "Privacy-First" Summary (TL;DR)

- **No Accounts:** You don’t need to sign up. We don’t know who you are.
- **On-Device Storage:** Your financial data (subscriptions, prices, notes) never leaves your phone. It is stored in a private local database, not on our servers.
- **Minimal Telemetry:** We use anonymous analytics to improve our brand library and fix bugs. Your financial data (amounts, notes) remains 100% private and stays on your device.

---

## 1. Our Privacy Philosophy

Lupi (the "App") was built on the principle of **Zero Knowledge**. We believe your financial life is your business. Our architecture ensures that your sensitive data remains under your physical control at all times.

## 2. Information We Handle

### A. Data Stored Locally (By You)

All records of your expenses, custom categories, and notes are saved directly to your device's internal storage using a secure SQLite database.

- **Access:** Only you can see this data.
- **Backup:** Your data is included in your standard device backups (e.g., iCloud or Google Backup), managed by your OS.

### B. Technical Interactions (The Internet)

To make the App useful, we perform specific, limited network requests. These requests do not contain your personal financial records:

- **Currency Conversion:** We fetch the latest rates from **Frankfurter API**.
- **Brand Identity:** We fetch logos and brand colors from **Brandfetch API** based on the domains you search for.
- **Notifications:** If enabled, we use **Expo/Apple/Google** system tokens to trigger local reminders.
- **Usage Insights:** We collect anonymous data about which brands are being searched (e.g., "netflix.com") to improve our built-in logo library (Lupi Assets) and monitor app stability using Firebase.

### C. [TODO] Future Premium Features

_Currently, the App is 100% free._ When we introduce Premium features, payment processing will be handled entirely by the **Apple App Store** or **Google Play Store**. We will never have access to your credit card or billing details.

## 3. Trusted Partners

We only connect to services that are essential for the App’s functionality.

| Service             | Why we use it                    | Privacy Info                                          |
| :------------------ | :------------------------------- | :---------------------------------------------------- |
| **Frankfurter API** | Real-time currency exchange      | [Public Domain / Open Source]                         |
| **Brandfetch API**  | Visualizing your subscriptions   | [Privacy Policy](https://brandfetch.com/privacy)      |
| **Apple / Google**  | App distribution & Notifications | [Apple Privacy](https://www.apple.com/legal/privacy/) |
| **Firebase (Google)**  | Crash reporting & anonymous brand usage | [Privacy Policy](https://firebase.google.com/support/privacy) |

## 4. Total Control: Data Deletion

You are the owner of your data.

1.  **Manual Reset:** You can wipe all data instantly using the **"Reset App"** feature in Settings.
2.  **App Uninstallation:** Deleting the App from your device automatically destroys the local database.

## 5. Global Compliance (GDPR & CCPA)

Although we do not "collect" data in the traditional sense, we comply with global standards:

- **GDPR (Europe):** The legal basis for processing is the performance of the contract (providing the app's features).
- **CCPA (California):** We do not "sell" or "share" your personal information.

## 6. Contact & Support

If you have questions about our "Local-First" approach, please reach out to the developer:

**Wojciech Grygo**  
Email: **grygo.wojtek@gmail.com**
