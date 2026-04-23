# Privacy Policy for CAPSA

**Effective date:** April 23, 2026
**Last updated:** April 23, 2026

This Privacy Policy describes how the CAPSA app ("CAPSA", "the app", "we", "us") handles information when you use it on your iPhone or iPad. This document is written to comply with Apple's App Store Privacy disclosure requirements as published at <https://developer.apple.com/app-store/app-privacy-details/>.

---

## 1. Summary

CAPSA does not collect any personal data.

All information you create inside the app — the photos you scan, the names you assign, the descriptions you write and the collections you organize — is stored exclusively on your device and, if you have iCloud enabled, in your own personal iCloud account. The developer of CAPSA has no access to this information at any time.

CAPSA does not contain analytics, advertising, tracking technologies, or third-party SDKs.

---

## 2. Information the App Handles on Your Device

The following information is created by you and stored locally on your device using Apple's SwiftData framework. It never leaves the device except to sync to your own iCloud account (see Section 3).

- **Photos of collectible items** you capture with the in-app document scanner (Apple VisionKit). Images are stored as JPEG data inside the app's local database.
- **Text** you type inside the app: collection names, item names, and item descriptions.
- **Visual layout preferences** of each item (its shape and dateAdded).
- **First-launch flags** stored in `UserDefaults` / `@AppStorage` (for example, whether you have seen the onboarding). These are local boolean flags and contain no personal information.

This information is not transmitted to the developer or to any third party.

---

## 3. iCloud Synchronization (CloudKit Private Database)

CAPSA uses **CloudKit** with Apple's `.automatic` configuration to sync your collections across your own Apple devices.

- Your data is stored in the **Private Database** of your personal iCloud account.
- Synchronization is handled entirely by Apple's infrastructure under your Apple ID.
- The developer of CAPSA **cannot access, read, modify, or export this data**.
- If you disable iCloud for CAPSA in iOS Settings, no data leaves your device.
- If you delete the app or sign out of iCloud, the data in your iCloud account is managed by Apple according to Apple's iCloud Terms and Privacy Policy (<https://www.apple.com/legal/privacy/>).

Because this data remains under your sole control within your iCloud account, it is not considered "collected" by the developer under Apple's definition of collection (i.e., transmitting data off the device in a way that allows the developer access for a period longer than necessary to service the request in real time).

---

## 4. Security

CAPSA relies entirely on Apple's built-in security infrastructure:

- Data stored on your device is protected by iOS Data Protection and file-system encryption, which are tied to your device passcode.
- Data synchronized to iCloud via CloudKit is encrypted by Apple both **in transit** (TLS) and **at rest** on Apple's servers, under your Apple ID.
- The developer does not operate any server, database, or backend service, and therefore cannot read, expose, leak, or be breached with respect to your CAPSA data.
- Any security guarantees beyond the device itself are provided by Apple and governed by Apple's Privacy Policy and iCloud Terms.

---

## 5. Camera Access

CAPSA uses the camera through Apple's VisionKit document scanner only when you explicitly tap the scan button to add a new collectible.

- You will be asked for camera permission the first time this feature is used, through the standard iOS system prompt.
- The captured image is processed by Apple's VisionKit on your device and returned to the app as an image.
- The image is then stored locally (and in your own iCloud if enabled), following the rules in Sections 2 and 3.
- The app does not stream, upload, or share camera images with the developer or any third party.
- You may revoke camera access at any time in iOS Settings → Privacy & Security → Camera.

CAPSA does not access the Photo Library, microphone, location, contacts, health data, or any other sensitive permission.

---

## 6. Permissions and User Consent

CAPSA does not implement any custom consent flow because no personal data is collected by the developer. All consent interactions are handled by iOS itself:

- **Camera**: managed by the iOS system permission prompt (see Section 5).
- **iCloud sync**: controlled by your device-wide iCloud settings for CAPSA.
- **Notifications, Location, Contacts, Photos, Microphone, Health**: not requested, because the app does not use them.

You can change any of these choices at any time in the iOS Settings app, and CAPSA will continue to function for features that do not depend on the revoked permission.

---

## 7. Tracking and App Tracking Transparency (ATT)

CAPSA does **not** track users as defined by Apple:

- No data is linked with third-party data for advertising or advertising measurement.
- No data is shared with data brokers.
- No third-party analytics, advertising or attribution SDKs are integrated.
- No advertising identifier (IDFA) is read or used.

Because CAPSA does not perform any tracking, the app **does not present the App Tracking Transparency (ATT) prompt**, in line with Apple's requirement that the prompt only be shown by apps that actually track.

---

## 8. Third-Party Services

CAPSA does not integrate any third-party SDK, analytics library, advertising network, crash-reporting service, or external API. The app communicates only with Apple's own on-device frameworks and, when iCloud is enabled, Apple's CloudKit service under your Apple ID.

---

## 9. Apple's App Privacy Nutrition Label

In line with Apple's App Store Privacy Details requirements, CAPSA declares the following:

| Section | Declaration |
|---|---|
| Data Used to Track You | **None.** CAPSA does not track users as defined by Apple (no linking to third-party data for advertising/measurement; no data brokers). |
| Data Linked to You | **None.** The developer does not receive any data. |
| Data Not Linked to You | **None.** The developer does not receive any data. |

The corresponding selection in App Store Connect is **"Data Not Collected"**.

---

## 10. Children's Privacy

CAPSA does not knowingly collect personal information from anyone, including children under the age of 13 (or the equivalent minimum age under applicable local law, such as 16 under GDPR). The app does not require an account, does not ask for personal details, and does not present advertising or external links.

---

## 11. Data Retention and Deletion

Because the developer does not collect any data, there is no developer-side retention period. Your data is retained only on your own device and in your own iCloud account, for as long as you choose to keep the app installed and iCloud sync enabled.

You can remove your data at any time:

- **Delete an item or a collection** using the delete buttons inside CAPSA.
- **Delete all local data** by deleting the CAPSA app from your device.
- **Delete the iCloud copy** at iOS Settings → [your name] → iCloud → Manage Account Storage → CAPSA → Delete Data.
- **Stop future iCloud sync** at iOS Settings → [your name] → iCloud → Apps Using iCloud → disable CAPSA.
- **Revoke camera permission** at iOS Settings → Privacy & Security → Camera → disable CAPSA.

Deleting the app does not send any deletion request to the developer, because no developer-side data exists to delete.

---

## 12. International Use and Legal Compliance (GDPR, CCPA/CPRA, LGPD)

Because the developer does not collect, store, process, sell, share, or transfer any personal data, CAPSA complies by design with the core obligations of major data-protection frameworks, including (but not limited to):

- The **EU General Data Protection Regulation (GDPR)** and the **UK GDPR**.
- The **California Consumer Privacy Act / California Privacy Rights Act (CCPA/CPRA)**.
- The **Brazilian Lei Geral de Proteção de Dados (LGPD)**.

Specifically:

- The developer is not a "data controller" or "data processor" of your CAPSA content, because CAPSA content stays on your device or in your personal iCloud account.
- No personal data is sold or shared for cross-context behavioural advertising under CCPA/CPRA.
- There is no international transfer of personal data performed by the developer. Any processing performed by Apple through iCloud is governed by Apple's own privacy documentation and regional terms.

If you are a user in the EU/EEA, UK, California, Brazil, or another jurisdiction granting data-subject rights (access, rectification, erasure, portability, objection, restriction), you may exercise those rights against Apple for iCloud-side processing, and you may contact the developer using the details in Section 14 for any question regarding CAPSA itself.

---

## 13. Changes to This Policy

If the app ever begins to handle data differently (for example, if a future version introduces analytics or a new permission), this policy will be updated before the new version ships, and the "Last updated" date at the top of this document will change. Material changes will also be reflected in the App Store Privacy Details before the updated version becomes available.

---

## 14. Contact

For any question related to privacy or this document, please contact:

**Paula Mora Romero**
Email: moraromeropaula@gmail.com

---

_This document applies exclusively to the CAPSA iOS/iPadOS application. It does not cover Apple iCloud, the App Store, or any Apple service, which are governed by Apple's own privacy policies._
