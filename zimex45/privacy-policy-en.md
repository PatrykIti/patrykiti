# Privacy Policy - Zimex 45

**Effective Date: June 28, 2025**
**Last Updated: March 30, 2026**

## 1. Introduction

This Privacy Policy describes how the **Zimex 45** application ("App", "we", "us", "our") processes data when you use the App.

Zimex 45 is an unofficial fan-made retro phone simulator inspired by classic mobile phone experiences, including the Siemens SL45i era.

## 2. Data Controller

Personal data controller:
- Name: PATRYKITI Patryk Ciechanski
- Contact email: zimex45@patrykiti.pl
- Address: 05-532 Szymanow, Poland

## 3. What Data We Process

### 3.1 Data Processed by Integrated Third-Party Services

Depending on your device, region, consent choices, and app behavior, the App may process the following categories of data through integrated SDKs and services:

- **Crash and diagnostic data** via Firebase Crashlytics, such as:
  - crash reports
  - error messages and stack traces
  - technical context attached to logs, for example module names, operation names, timestamps, screen names, and non-sensitive runtime state
  - device and app metadata collected by the provider as part of crash diagnostics

- **Advertising and consent-related data** via Google Mobile Ads / AdMob and Google's User Messaging Platform (UMP), such as:
  - advertising-related identifiers and ad request data handled by Google
  - consent status and consent signals required to determine whether ads may be requested
  - technical device/network metadata processed by Google for ad delivery, fraud prevention, and compliance

### 3.2 Data Stored Locally on Your Device

The App stores certain data locally on your device, primarily through app storage and SharedPreferences, including:

- **Game data**:
  - high scores
  - game progress
  - in-game state needed for gameplay features

- **App preferences and settings**:
  - audio-related settings
  - UI and simulator preferences
  - selected in-app states required to restore screens and behavior

- **Organiser data**:
  - sample or simulated SIM contacts created inside the App
  - calendar state
  - appointments and other organiser entries created inside the App

- **Consent-related data**:
  - locally stored ad-consent status, such as `user_ad_consent`
  - consent strings or related values written by Google SDKs where applicable

### 3.3 Data the App Does Not Directly Request from You

The App does not require you to create an account or directly submit personal profile data in order to use its core features.

The App does not directly request access to:
- real phone contacts
- real call history or SMS history
- precise GPS location
- camera or microphone data
- photos, videos, or media libraries

## 4. Why We Process Data

We process data for the following purposes:

- **App functionality**: to run the simulator, organiser features, and games
- **Saving progress and preferences**: to preserve local game state and settings
- **Reliability and debugging**: to diagnose crashes, errors, and technical problems
- **Advertising and consent management**: to request, limit, or disable ads based on consent status
- **Security and compliance**: to help prevent abuse and comply with legal obligations

## 5. Third-Party Services

### 5.1 Firebase Crashlytics

We use **Firebase Crashlytics** to collect crash reports and technical diagnostics that help us identify and fix bugs.

Relevant provider information:
- [Firebase Privacy and Security](https://firebase.google.com/support/privacy)

### 5.2 Google Mobile Ads / AdMob

We use **Google Mobile Ads / AdMob** to display ads in the App.

Relevant provider information:
- [Google Privacy Policy](https://policies.google.com/privacy)

### 5.3 Google UMP (User Messaging Platform)

We use Google's consent tools included with the ads SDK to collect and store ad-consent choices where required.

Relevant provider information:
- [Google Privacy Policy](https://policies.google.com/privacy)

### 5.4 Sharing Principles

We do not sell your data.

However, data may be processed by service providers used by the App, especially Google services listed above, and may also be disclosed when required by law or reasonably necessary to protect security, rights, or the operation of the App.

## 6. Data Security

We take reasonable steps to reduce privacy risk, including:

- storing local app data inside the app's storage space
- sanitizing logging context to reduce accidental inclusion of sensitive data
- limiting the App to non-sensitive permissions in the main Android manifest
- relying on established third-party providers for crash reporting, ads, and consent flows

No method of transmission or storage is completely risk-free, so absolute security cannot be guaranteed.

## 7. Data Retention

- **Local app data** is generally retained until you clear app data, overwrite it through normal use, or uninstall the App.
- **Crash, advertising, and consent-related data** processed by third-party providers may be retained according to those providers' own policies and retention schedules.
- We do not guarantee or control exact retention periods for data stored by Google services.

## 8. Your Rights and Choices

Depending on applicable law, you may have rights such as access, rectification, erasure, restriction, objection, or complaint to a supervisory authority.

In practical terms:
- you can remove locally stored data by clearing app data or uninstalling the App
- ad-consent choices are managed through Google's consent flow when presented in the App or otherwise required for your region
- you can contact us regarding data protection questions or requests

## 9. Children

This App is not intended for children under 13 years of age.

- The App is intended for users aged 13+
- We do not knowingly ask children to provide personal profile information to use the App
- If you believe a child provided personal data to us directly, please contact us at zimex45@patrykiti.pl

## 10. Changes to This Policy

We may update this Privacy Policy from time to time.

When we make material changes, we may update the date at the top of this document and, where appropriate, reflect the change in an app update or related documentation.

## 11. Contact

For questions regarding this Privacy Policy or data processing, contact:

- Email: zimex45@patrykiti.pl

## 12. Legal Basis

Where the GDPR applies, our legal bases may include:

- **Art. 6(1)(f) GDPR** - legitimate interest, for app security, diagnostics, and reliable operation
- **Art. 6(1)(a) GDPR** - consent, where required for ad-related processing or consent management

## 13. Additional Information

### 13.1 App Permissions

The main Android manifest currently declares:
- **INTERNET** - required for communication with integrated online services such as crash reporting and advertising

The App does not declare sensitive runtime permissions for contacts, location, microphone, camera, SMS, or call history in the main Android manifest.

### 13.2 External Links

This document contains links to third-party privacy notices. Those third parties apply their own policies and practices.

---

**Version**: 1.1
