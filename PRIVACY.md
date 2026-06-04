# Privacy Policy for TrackMoola

**Effective date:** June 4, 2026
**Last updated:** June 4, 2026

This Privacy Policy explains how the **TrackMoola** mobile app ("TrackMoola", the "App", "we", "us", or "our") handles your information. TrackMoola is published by **Amogh Tech Ltd**.

TrackMoola is an **offline-first personal-finance companion**. It helps you track your financial profile — income, savings, debts, expenses, properties, and related calculations — directly on your device.

If you have any questions about this policy or your data, contact us at **support@amoghsa.com**.

---

## The short version

- **Your financial data stays on your device.** Everything you enter (income, savings, debts, expenses, properties, dependents, and calculation results) is stored locally on your phone.
- **We do not operate a server that stores or reads your financial data.** We have no backend that can see your money. We literally cannot access what you enter.
- **We do not connect to your bank.** There is no account aggregation (no Plaid, Flinks, or similar). All data is entered manually by you — by design, for privacy.
- **Optional cloud sync goes to *your own* account.** If you turn on sync, your data is stored in **your own iCloud** (iOS) or **your own Google Drive** (Android) — not ours.
- **Ads appear only on the free tier**, served by Google AdMob, and require your consent. A one-time purchase removes them permanently.
- **No financial figures are ever sent to analytics or advertising services.**

---

## 1. Who we are

TrackMoola is developed and published by **Amogh Tech Ltd**. You can reach us at:

- **Email:** support@amoghsa.com

This policy applies to the TrackMoola apps for **iOS** and **Android**.

---

## 2. Information stored on your device

TrackMoola is designed so that the information you enter stays on your device. The App stores the following **locally** (using SwiftData on iOS and an encrypted-at-rest SQLite/Room database on Android):

- **Financial profile:** age, birth year, province/region, filing status, risk tolerance, retirement age, marginal tax rate, and housing status.
- **Income streams:** name, type, amount, frequency, and whether the income is taxable.
- **Savings accounts:** account type (e.g., RRSP, TFSA, FHSA, RESP, RDSP, non-registered, chequing, savings), balances, contributions, and expected returns.
- **Debts:** type, balance, interest rate, payment, and credit limit.
- **Rental / property details:** value, mortgage, rental income, and expenses.
- **Expenses:** category, amount, frequency, and whether the expense is essential.
- **Dependents:** a nickname, birth year, and education-savings goals.
- **Contribution room** and related figures.
- **For the Couples tier:** how each item is owned (personal, joint, or split) between you and a partner.

**We do not collect, transmit, or have access to any of this financial information.** It is processed on your device to power the App's calculations and views.

---

## 3. Optional cloud sync (your own account)

Cloud sync is **optional** and **off by default**. TrackMoola is fully usable offline without ever enabling it.

If you choose to enable sync (a feature of the paid Pro tier):

- **On iOS**, your data is synced to **your own private iCloud** account using Apple's CloudKit. It is stored in your iCloud, governed by Apple's terms, not ours.
- **On Android**, your data is synced to a **hidden, app-private folder in your own Google Drive** (the Drive "app data" folder). It is stored in your Google account, governed by Google's terms, not ours.
- **Couples / partner sync** (a separate paid feature) lets you share your household data with a partner through your platform's native sharing (Apple's CloudKit sharing or a Google Drive file you grant access to). Data stays within the two users' own cloud accounts.

In all cases:

- Data in transit is protected using HTTPS/TLS.
- **We operate no server in this flow.** Your data moves between your device and your own cloud account.
- You can turn sync off, and you can delete the synced data directly from your own iCloud or Google Drive account.

---

## 4. Advertising (free tier only)

The **free tier** of TrackMoola shows ads served by **Google AdMob**. Paid tiers (Pro and Couples) are **ad-free**, and ads are removed permanently once you make a qualifying purchase.

- **Ad formats:** a small banner, occasional full-screen ads on natural transitions, and an optional "rewarded" ad (e.g., to unlock an additional export). Ads never block your access to the App's core calculations.
- **Advertising identifier:** to show ads, AdMob may use your device's advertising identifier and related data.
- **Your consent:**
  - On **iOS**, we use Apple's **App Tracking Transparency (ATT)** framework. If you decline tracking, you will still see ads, but **non-personalized** ones.
  - On **Android**, we use Google's **User Messaging Platform (UMP)** consent form (including for users in the EEA/UK) to obtain the appropriate consent before serving personalized ads.
- **Measurement:** on iOS, Apple's **SKAdNetwork** may be used for privacy-preserving ad attribution.
- **No financial data in ads:** the information you enter into TrackMoola is **never** shared with AdMob or used for ad targeting.

Google's handling of advertising data is governed by Google's Privacy Policy and AdMob policies (see Section 8). You can manage or reset your advertising identifier in your device settings.

---

## 5. Analytics

If analytics are used, they are **limited and non-financial**. We may use privacy-respecting analytics (such as Google Firebase Analytics) and remote configuration (Firebase Remote Config) to understand general, anonymous usage patterns (for example, which features are opened) and to manage feature flags and pricing experiments.

- **No money values, balances, or any financial figures you enter are ever included in analytics or sent off your device.**
- Remote configuration fetches settings (such as feature flags) to the App; it does not upload your financial data.

---

## 6. Purchases

TrackMoola offers **one-time purchases** (there are **no subscriptions**) to unlock paid tiers and remove ads:

- On **iOS**, purchases are processed by **Apple** through the App Store (StoreKit).
- On **Android**, purchases are processed by **Google** through Google Play Billing.

Payments and billing details are handled entirely by Apple or Google. **We do not receive or store your payment card details.** We receive only the entitlement information needed to unlock features you have purchased and to restore previous purchases.

---

## 7. Device permissions and notifications

TrackMoola requests only the minimum permissions it needs:

- **Internet access** — used for optional cloud sync (to your own account), ads on the free tier, and fetching remote configuration. There is no TrackMoola backend.
- **Advertising ID** (Android) — used for ads on the free tier, as described above.
- **Notifications** (Android 13+ and iOS) — used for **local** notifications, such as letting you know a sync finished or an export is ready. These are device notifications; we do not send marketing push notifications.

TrackMoola does **not** request access to your location, contacts, camera, microphone, photos, or device storage for browsing files.

---

## 8. Third-party services

When you use certain features, data is handled by the following third parties under **their own** privacy policies:

- **Apple** (iCloud sync, App Store purchases) — https://www.apple.com/legal/privacy/
- **Google** (Google Drive sync, AdMob advertising, Firebase analytics/remote config, Google Play purchases) — https://policies.google.com/privacy

We encourage you to review these policies. We do not control how Apple or Google process data within their services.

---

## 9. International data transfers

If you enable cloud sync or see ads, the relevant data may be processed by Apple or Google on servers located in countries other than your own. Those transfers are governed by Apple's and Google's respective privacy frameworks and safeguards.

---

## 10. Data retention and deletion

- **On-device data:** kept on your device until you delete it. You can delete your data from within the App, or by uninstalling the App.
- **Cloud-synced data:** stored in your own iCloud or Google Drive account and remains under your control. You can delete it directly from that account at any time, or by turning off sync within the App.
- **We hold no copy of your financial data**, so there is nothing for us to retain or delete on a server.

If you have purchased a paid tier, your purchase record is held by Apple or Google as the payment processor, subject to their policies.

---

## 11. Your privacy rights

Depending on where you live, you may have rights under laws such as Canada's **PIPEDA**, the EU/UK **GDPR**, or the **California Consumer Privacy Act (CCPA/CPRA)**, including the right to access, correct, or delete personal data, and to withdraw consent.

Because TrackMoola stores your financial data **on your own device and in your own cloud account**, you can exercise most of these rights directly — by viewing, editing, or deleting your data in the App or in your iCloud/Google account, and by managing ad consent and your advertising identifier in your device settings.

For any privacy request or question, contact us at **support@amoghsa.com** and we will respond within a reasonable timeframe.

---

## 12. Children's privacy

TrackMoola is intended for **adults** (general personal-finance audience) and is **not directed to children**. We do not knowingly collect personal information from children. If you believe a child has provided personal information through the App, please contact us so we can address it.

---

## 13. Security

Your data is stored using your platform's standard protections, including encryption at rest where supported by the device and operating system, and is transmitted over encrypted connections (HTTPS/TLS) during optional cloud sync. No method of electronic storage or transmission is 100% secure, but because we do not operate a server that holds your financial data, the primary safeguards are your device's and your cloud provider's protections.

---

## 14. Changes to this policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Last updated" date above and post the new version at this location. Significant changes may also be communicated within the App. Your continued use of TrackMoola after an update means you accept the revised policy.

---

## 15. Contact us

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

**Amogh Tech Ltd**
Email: **support@amoghsa.com**
