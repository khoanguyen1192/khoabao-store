# Privacy Policy for QR Inventory & Barcode Scanner

**Effective Date:** August 19, 2026<br>
**Last Updated:** August 19, 2026<br>
**Developer:** Khoa Bảo Store (Legal Owner: NGUYEN DINH BAO KHOA)

---

## 1. Introduction

This Privacy Policy explains how the iOS application **QR Inventory & Barcode Scanner** (also displayed in the app as **QR Scanner**) (the “App”) handles information when you scan or create codes, organize a code library, manage inventory projects, use product lookup, or purchase a subscription.

The App is developed and maintained by **Khoa Bảo Store** (“we,” “us,” or “our”). By using the App, you acknowledge the practices described in this Privacy Policy. If you do not agree with this policy, please do not use the App.

The App does not require you to create an account.

---

## 2. Privacy Summary

- Scanned and generated code content, saved history, projects, inventory records, imported CSV data, and preferences are stored locally on your device.
- Camera frames and images selected for code or text recognition are processed on your device and are not uploaded by us.
- When you request product information for a numeric barcode, the barcode is sent to the Open Food Facts API.
- Firebase may process app configuration, installation, technical, and app-usage information when those services are enabled.
- RevenueCat and Apple process subscription and purchase information needed to provide and restore premium access.
- We do not sell your personal data.
- We do not use your scanned content, inventory records, contacts, calendar data, or photos for advertising.
- The App does not currently request the Identifier for Advertisers (IDFA) or track you across apps and websites owned by other companies.

---

## 3. Information You Create and Store Locally

### 3.1 Code and Inventory Data

Depending on the features you use, the App may store the following data locally on your device:

- QR code and barcode values that you scan, enter, or create
- Names, labels, formats, favorites, and scan dates
- Information you choose to encode in a QR code, such as text, website URLs, Wi-Fi details, contact details, calendar details, phone numbers, email content, or locations
- Project names, project settings, inventory items, quantities, prices, shelves, SKUs, tags, notes, minimum stock levels, expiration dates, and transaction history
- CSV catalogs you import and reports you generate
- App preferences, onboarding status, theme and language choices, free-scan counters, and cached subscription status

This content remains on your device unless you intentionally share or export it, request an online product lookup, or use an operating-system action that sends the content to another app or service.

### 3.2 CSV Import and Export

CSV files selected for import are read by the App to create or update local inventory records. Exported CSV files are created locally in temporary app storage. They leave the App only when you choose a destination through the iOS share sheet or another system action.

Files that you export to another app, cloud provider, email service, or storage location are governed by that recipient’s privacy practices.

### 3.3 Clipboard

The App can copy code content or a Wi-Fi password to the system clipboard only when you select a copy action. Other apps may be able to read clipboard content according to your device settings and Apple’s platform behavior.

---

## 4. Device Permissions

The App requests permissions only when needed for a feature you choose.

### 4.1 Camera

Camera access is used to scan QR codes and barcodes and to perform visual text recognition. Camera frames are processed on the device and are not uploaded by us.

### 4.2 Photos

The App accesses only images you select for scanning or visual recognition. Add-only Photo Library permission may be requested when you choose to save a generated code image. Selected images and recognized text are processed on the device and are not uploaded by us.

### 4.3 Contacts

When you scan a supported contact code and explicitly choose **Add Contact**, the App requests Contacts permission to save that contact on your device. The App does not upload your address book or use your contacts for analytics or advertising.

### 4.4 Calendar

When you scan a supported calendar code and explicitly choose **Add to Calendar**, the App requests Calendar permission to save that event on your device. The App does not upload your calendar database or use calendar content for analytics or advertising.

### 4.5 Location Content

The App can scan, create, and locally save QR codes containing coordinates or place information that you provide. The App does not request access to iOS Location Services to determine your device’s precise GPS location.

You can manage permissions at any time in **iOS Settings → Privacy & Security**.

---

## 5. Information Processed by Online Services

### 5.1 Firebase Remote Config and Analytics

The App integrates Firebase services provided by Google LLC.

**Firebase Remote Config** is used to deliver operational configuration such as feature availability, free-scan limits, paywall behavior, and update settings. Firebase documents that Remote Config may process information such as country code, language, time zone, operating-system version, app version, bundle identifier, Firebase app identifier, and a Firebase installation identifier.

When **Firebase Analytics** collection is enabled in the production configuration, it may process:

- App interactions and feature events
- Screen names and onboarding progress
- Paywall and purchase-flow events
- Subscription transaction events and status
- App version and general device or operating-system information
- Installation or vendor identifiers made available to Firebase under the final SDK configuration

We use this information to operate the App, understand aggregate feature usage, improve reliability and usability, measure purchase-flow performance, and configure features. We do not intentionally include scanned code payloads, selected photos, contact or calendar content, imported CSV content, or inventory record details in Firebase analytics events.

If Firebase Analytics collection is disabled in a release configuration, developer-defined analytics events are not sent to Firebase Analytics. Firebase Remote Config may still process the technical and installation information required to provide remote configuration.

Learn more:

- [Firebase Privacy and Security](https://firebase.google.com/support/privacy)
- [Google Privacy Policy](https://policies.google.com/privacy)

### 5.2 RevenueCat

The App integrates RevenueCat to mirror, validate, synchronize, and analyze subscription transactions. RevenueCat may process:

- An anonymous App User ID
- App and device technical information
- Product identifiers
- Purchase and subscription history
- Transaction status, renewal status, and entitlement information
- Locale and currency information

The App does not provide RevenueCat with your name, email address, contact list, scanned code content, inventory data, or payment card details. RevenueCat does not process payment card information for this App; payments are handled by Apple.

Learn more:

- [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy)
- [RevenueCat App Privacy Guidance](https://www.revenuecat.com/docs/platform-resources/apple-platform-resources/apple-app-privacy)

### 5.3 Apple App Store and StoreKit

The App uses Apple StoreKit for auto-renewable subscriptions and purchase restoration. Apple processes your Apple ID, payment method, billing, tax, receipt, and transaction information under Apple’s policies. We do not receive or store your complete payment card or bank account details.

The App may receive transaction identifiers, product identifiers, purchase dates, expiration dates, revocation status, and entitlement status required to unlock and restore premium features.

Learn more:

- [Apple Privacy Policy](https://www.apple.com/legal/privacy/)
- [Apple StoreKit](https://developer.apple.com/documentation/storekit/)

### 5.4 Open Food Facts Product Lookup

When you scan or enter an eligible numeric product barcode, the App may request product information from the Open Food Facts API. The request includes:

- The numeric barcode
- Requested product-data fields
- An App-identifying User-Agent
- Standard network information such as your IP address that is necessarily visible to the service receiving the request

Open Food Facts may return a product name, brand, package size, category, and product image URL. The App does not upload your product photos, inventory records, name, email address, or account information to Open Food Facts. Product lookup results may be cached temporarily in memory for the current App session.

Open Food Facts data is community-provided and may be incomplete or inaccurate.

Learn more:

- [Open Food Facts API Documentation](https://openfoodfacts.github.io/documentation/docs/Product-Opener/api/)
- [Open Food Facts Terms of Use](https://world.openfoodfacts.org/terms-of-use)

### 5.5 External Links and System Actions

Scanned content may let you open a website, map, phone call, message, email composer, social profile, or another installed app. These actions occur only after you select them. Once you leave the App, the destination service’s privacy policy applies.

---

## 6. How We Use Information

We process information described in this policy to:

- Provide scanning, code creation, library, project, inventory, import, export, and subscription features
- Perform product lookups that you request
- Save your settings and locally created content
- Validate purchases and restore premium access
- Configure features and maintain compatibility
- Understand aggregate usage and improve the App when analytics is enabled
- Prevent fraud, abuse, and technical failures
- Comply with applicable law and enforce our rights

We do not sell or rent personal data. We do not use scanned payloads, photos, contacts, calendar data, CSV content, or inventory records for targeted advertising. We do not share personal data with data brokers.

---

## 7. Data Retention and Deletion

### 7.1 Local Data

Locally stored data remains on your device until you delete individual records, clear the relevant App data, or delete the App. Deleting the App normally removes its local container and locally stored records. Files you exported outside the App must be deleted separately from their destination.

### 7.2 Online Service Data

Firebase, RevenueCat, Apple, Open Food Facts, and any destination you choose for sharing or exporting retain information according to their own policies and legal obligations. Apple purchase records may remain associated with your Apple ID even after the App is deleted so that purchases can be restored and financial obligations can be met.

For a privacy request concerning data under our control, contact us using Section 11. We may ask for information reasonably necessary to locate a relevant anonymous installation or transaction record. We cannot delete information controlled solely by Apple or a third-party destination on your behalf.

---

## 8. Security and International Processing

We use reasonable technical and organizational safeguards appropriate to the nature of the information handled by the App. Local data benefits from protections provided by iOS, including device access controls and data protection. Communications with online services use HTTPS.

No method of storage or transmission is completely secure. You are responsible for protecting access to your device and reviewing the contents of a code before opening a link or performing another action.

Third-party providers may process information in countries other than your own. Their policies describe their processing locations, safeguards, and legal bases.

---

## 9. Your Privacy Choices and Rights

Depending on your location, you may have rights to access, correct, delete, restrict, object to, or obtain a copy of personal data, and to lodge a complaint with a data-protection authority.

You can also:

- Delete saved codes, projects, or inventory records in the App
- Decline or revoke Camera, Photos, Contacts, or Calendar permission in iOS Settings
- Choose not to request online product lookup
- Choose not to share or export local content
- Manage or cancel subscriptions in your Apple ID subscription settings
- Delete the App to remove its local data container

To exercise a right concerning data controlled by us, email [support@khoabao.store](mailto:support@khoabao.store). We will respond within the period required by applicable law.

---

## 10. Children’s Privacy

The App is a general-purpose utility and is not directed to children under 13, or the equivalent minimum age in the relevant jurisdiction. We do not knowingly collect personal information from children. If you believe a child has provided personal information through the App or a support request, please contact us so we can evaluate and address the request.

---

## 11. Contact Information

For privacy questions, requests, or concerns, contact:

**Khoa Bảo Store**<br>
**Legal Owner:** NGUYEN DINH BAO KHOA<br>
**Email:** [support@khoabao.store](mailto:support@khoabao.store)

For Apple payment or Apple ID questions, contact [Apple Support](https://support.apple.com/contact).

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy to reflect changes to the App, third-party services, law, or our privacy practices. We will publish the updated policy at the same public location and revise the **Last Updated** date. Material changes will be communicated in the App or through another appropriate method when required by law.

Your continued use of the App after an update means the updated policy applies to your subsequent use, subject to applicable law.

---

**Thank you for using QR Inventory & Barcode Scanner.**
