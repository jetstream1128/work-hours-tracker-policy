# Privacy Policy

Effective date: April 6, 2026

This Privacy Policy applies to **Ultimate Work Hours Tracker** (the "App") and explains how **DanTechStudio** ("we", "us", or "our") handles information when you use the App.

## Contact

If you have questions about this Privacy Policy or privacy-related requests, contact:

- Developer: Bohdan Alieksieiev
- Email: dantechstudio.sup@gmail.com

## Summary

The App is a work-hours tracking tool. It is designed to store shift data primarily on your device, while using selected third-party services for analytics, remote configuration, and in-app purchase/subscription management.

At the time of writing, the App:

- stores work-hour records and settings locally on your device;
- stores a limited number of automatic local database backups on your device;
- can create local XLSX/PDF exports when you request them;
- can share exported files through your device operating system when you choose to share;
- uses local notifications and Android widget/exact alarm functionality when enabled;
- uses Firebase Analytics and Firebase Remote Config;
- uses RevenueCat for subscription and purchase status handling;
- does not require account creation for core features;
- does not include third-party advertising SDKs.

## Information We Process

### A. Data processed locally on your device

- Work shift records (for example date, start/end times, shift source).
- App settings (for example reminders, language, currency, overtime settings, widget settings).
- Local backup files of the app database.
- Export files you generate (for example XLSX/PDF).

### B. Data processed by third-party services used by the App

#### Firebase Analytics

Used for product analytics events and selected app-level properties, such as:

- app interaction events (for example punch in/out, export action);
- selected preferences sent as analytics properties (for example preferred theme/language/currency and certain feature usage flags).

Firebase/Google may also process SDK/device/app identifiers and usage metadata required for analytics operation.

#### Firebase Remote Config

Used to fetch app configuration values (for example feature flags, update thresholds, and policy URLs).

Remote Config may process technical metadata used for parameter targeting and service operation (for example app/platform/version and related configuration context).

#### RevenueCat and App Store Providers

Used to support subscriptions and one-time in-app purchases.

Depending on platform flow, this can include:

- product identifiers and purchase status;
- transaction/receipt-related data required for validation;
- RevenueCat App User ID (anonymous by default if you do not sign in);
- store-side billing/subscription metadata handled by Google Play / Apple.

We do not use your shift history as purchase identity data.

## How We Use Information

We use data to:

- run core shift tracking and payroll-estimate functionality;
- save settings and keep app behavior consistent across sessions;
- schedule reminders and support Android widget behavior;
- generate/share exports when you request them;
- monitor product usage and improve app quality/features;
- validate and restore purchases/subscriptions.

## Sharing of Data

We do not sell your personal data.

Data may be shared with service providers that process data on our behalf to provide app functionality:

- Google Firebase (Analytics, Remote Config);
- RevenueCat (subscription/purchase infrastructure);
- Platform stores/payment infrastructure (Google Play, Apple).

When you export/share files, data is also shared with destinations you choose via your device OS.

## Where Data Is Stored

- Core shift data and settings: on your device (local storage/database).
- Analytics/config/purchase infrastructure data: processed by the respective service providers described above.

## Data Retention

- Local app data remains on your device until you edit/delete it, clear app storage, or uninstall the app.
- Local automatic backups are retained in a limited rolling set on-device (currently up to five backups).
- Exported files remain where you save/share them until deleted.
- Third-party service retention is managed by those providers under their own policies and controls.

## Data Deletion and User Choices

You can:

- delete/edit shift records inside the app;
- clear app storage in device settings;
- uninstall the app;
- delete exported files where saved.

For third-party service data requests, contact us at the email above. We may need enough technical details to identify records (for example app variant/platform and relevant purchase/support identifiers).

Deletion request page:

- https://jetstream1128.github.io/work-hours-tracker/data-deletion/

## Notifications, Widgets, and Device Permissions

If enabled by your settings/use, the App may request or use notification-related capabilities and Android features such as exact alarms, boot handling, and home screen widget synchronization.

## Security

We apply reasonable safeguards in the app design (for example app-local storage patterns and Android backup restrictions in configuration).

No storage/transmission method is completely secure, and you remain responsible for securing your device and exported files.

## Children's Privacy

The App is not directed to children under 13, and we do not knowingly design it as a child-directed service.

## International Data Processing

Because we rely on third-party infrastructure providers, data processed by those providers may be handled in countries other than your own, subject to their legal and technical safeguards.

## Third-party Policies

- Google Play User Data policy: https://support.google.com/googleplay/android-developer/answer/10144311?hl=en
- Apple App Review Guidelines: https://developer.apple.com/app-store/review/guidelines/
- Firebase privacy and data collection references:
  - https://firebase.google.com/docs/ios/app-store-data-collection
  - https://firebase.google.com/docs/analytics/configure-data-collection
- RevenueCat documentation:
  - https://www.revenuecat.com/docs/customers/identifying-customers

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the effective date and may provide additional notice where appropriate.
