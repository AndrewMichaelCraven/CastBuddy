# CastBuddy Privacy Policy

_Effective date: May 5, 2026_
_Contact: CastBuddy@icloud.com_

---

## What Information We Collect

**CastBuddy does not collect personal information.**

CastBuddy has no user accounts, no sign-up flow, and no mechanism to transmit personal information to us. We do not collect your name, email address, location, IP address, viewing history, or any other personally identifying information.

## What Is Stored and Where

All app data — your icon library, screens, moods, PIN, settings, and pairing history — is stored **locally on your device** using Apple's SwiftData framework. This data never leaves your device except as described below.

### iCloud Sync

If you have iCloud enabled on your iPad, Apple may sync your app data to your personal iCloud account via CloudKit. This sync occurs between **your own devices** under **your own Apple ID**. We have no access to this data.

## Catalog Fetching

To provide curated content suggestions in the Add Icon flow, CastBuddy periodically fetches a JSON file from a public GitHub repository:

`https://raw.githubusercontent.com/AndrewMichaelCraven/CastBuddy/main/catalog.json`

This request is made by your device directly to GitHub's servers. No personal information is included in the request. GitHub may log standard server-side access information (such as IP address and request timestamp) according to GitHub's Privacy Statement. CastBuddy does not receive or process any of this information.

## Anonymous Diagnostics (Optional)

CastBuddy includes optional anonymous diagnostic reporting powered by TelemetryDeck. This feature is **enabled by default** and can be disabled at any time in **Settings → Privacy → Share Anonymous Diagnostics**.

When enabled, CastBuddy sends anonymized signals such as "app launched," "pairing completed," and "cast succeeded" to TelemetryDeck's servers. These signals help us understand how the app is being used and identify failures.

**What TelemetryDeck receives:**
- Anonymous event names (e.g., "castSucceeded")
- App version and platform (iPadOS)
- A double-hashed, non-reversible identifier derived from your device — TelemetryDeck cannot use this to identify you or your device

**What TelemetryDeck does not receive:**
- Your name, Apple ID, or any account information
- Content you watch, icon names, or URLs you have entered
- Your IP address (TelemetryDeck strips and hashes it server-side)

When diagnostics are disabled, **no data of any kind** is sent to TelemetryDeck and the SDK is not initialized.

## Children's Privacy (COPPA)

CastBuddy is designed to be configured by a parent or guardian and used by children under parental supervision.

We do not knowingly collect personal information from any user, including children under the age of 13, in compliance with the U.S. Children's Online Privacy Protection Act (COPPA). We do not knowingly collect personal information from children under the age of 16 in compliance with the EU General Data Protection Regulation (GDPR), or from minors under the age of 18 in compliance with the California Consumer Privacy Act (CCPA).

The app is structurally designed to make such collection impossible: there is no account system, no input field where a child could enter personal data, no upload mechanism, and no transmission of identifying information to any server we control.

If you are a parent or guardian and believe your child has somehow provided personal information through CastBuddy, please contact us at CastBuddy@icloud.com and we will respond promptly.

## Data Security

Because CastBuddy stores all data locally on your device, your data is protected by iOS's built-in device encryption and the security of your Apple ID and iCloud account. We do not operate servers that store your personal data.

## Your Rights

Because we do not collect personal information, there is no personal data for us to delete, correct, or export on your behalf. If you have questions about data associated with your iCloud account, those requests should be directed to Apple.

For any questions about this Privacy Policy, contact us at **CastBuddy@icloud.com**.

## Changes to This Policy

We may update this Privacy Policy from time to time. When we make material changes, we will update the effective date above. Continued use of CastBuddy after any update constitutes acceptance of the revised policy.

---

*CastBuddy is an independent product developed by Andrew Craven. CastBuddy is not affiliated with, endorsed by, or sponsored by Apple, Disney, YouTube, Google, or any other third party.*
