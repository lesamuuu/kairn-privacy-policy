# Kairn Privacy Policy

> Draft requiring review before publication, particularly regarding health data, children, legal bases, and providers' contracts and international data transfers.

**Last updated:** November 9, 2026

**Data controller:** Samuel Petrucci

**Location:** Santa Cruz de Tenerife, Spain

**Privacy contact:** samuelpayback@gmail.com

This policy explains how Kairn processes information when you use the app and the choices you have to control it.

## 1. The essentials

Kairn is an app for logging strength training. You can use its core features without creating an account and without an Internet connection.

Your workout history is stored on your device. Kairn does not provide its own cloud workout synchronization service, and its controller cannot remotely access the history stored on your phone.

You can choose separately whether to share error reports and feature usage data to help improve the app. Both options are off by default.

If you submit feedback through the app, the message you write is transmitted together with limited technical information. This submission is independent of your analytics and diagnostics preferences.

Kairn may also connect to update services to check for and download new versions of its code and assets.

## 2. Information stored on your device

Kairn stores the information needed to provide its features locally:

- **Workouts:** sessions, dates, times, duration, exercises, sets, weights, repetitions, effort indicators, and results calculated from your records.
- **Organization:** routines, exercise order, equipment, and tags.
- **Content you add:** notes, comments, exercise images, and events in Kairn's internal calendar.
- **Preferences:** language, units, appearance, an optional display name, and other app settings.

This information enables workout logging, history browsing, charts and estimates, customization, and the files you ask the app to generate. Physical activity records, images, and notes may reveal personal or health-related information, depending on their contents.

Kairn calendar events are entered within the app; this feature does not involve access to your system calendar. The current version does not integrate with Apple Health, HealthKit, or Health Connect.

Avoid entering information about other people without a lawful basis for doing so.

## 3. Optional error reports

If you enable **“Share error reports,”** Kairn may send technical information to help identify and fix problems.

Reports may include the error type, technical codes, references to functions and code locations, app version, operating system and its version, date and time, and pseudonymous installation or session identifiers.

Kairn filters reports to exclude original error messages that may contain private information, SQL queries, variables, and full local paths. It does not automatically attach your workout history, exercise names, weights, repetitions, notes, images, or file contents.

The current PostHog implementation does not collect native crashes or make screen or session recordings.

## 4. Optional usage data

If you enable **“Share feature usage,”** Kairn may send events about the features you use. For example: opening a section, using a chart, saving a routine, logging a set, or completing a session.

Events may include action and setting categories, date and time, app version, operating system information, and pseudonymous identifiers.

They do not automatically include your exercise or routine names, weights, repetitions, notes, photos, file contents, or historical workout dates. However, event timing and frequency may reveal when you use particular training features.

### Provider and controls

Kairn uses **PostHog Cloud EU** to process authorized error reports and usage events.

The identifiers are not your name or an account, but they allow events from the same installation to be linked. These data are therefore pseudonymous, not completely anonymous.

PostHog receives the IP address used to make the connection. Kairn disables geographical enrichment for events; this does not mean the provider does not receive the IP address.

Kairn's configuration does not use this information for advertising, session recordings, or cross-app tracking.

You can enable or disable diagnostics and analytics independently in Settings. Declining them does not prevent you from logging workouts or viewing your history.

When these preferences change, Kairn discards pending events from the previous configuration. Disabling an option prevents new submissions of that type, but does not automatically delete data already transmitted. Network requests started before the change may still complete.

More information: [PostHog Privacy Policy](https://posthog.com/privacy).

## 5. Feedback you voluntarily submit

If you use **“Send feedback,”** the following are transmitted to PostHog:

- The text you write and your selected category: bug or improvement.
- The language, platform, and app version and build.
- An identifier generated for that submission, separate from the analytics identifier.

The provider also receives the connection's IP address.

The form does not automatically attach your workouts, images, or files, and does not request a reply address. The message itself may contain personal data if you choose to include them. Do not include passwords, medical information, sensitive data, or unnecessary information about other people.

You can submit feedback even if diagnostics and analytics are disabled. Pressing the send button requests only that feedback submission and does not enable the other options.

The draft is temporarily held in the screen's memory. It is not saved as a pending message for automatic delivery later. You can retry after a submission error; a failure to confirm delivery could result in a duplicate submission if you try again.

## 6. App updates

Kairn uses **Expo / EAS Update**, provided by **650 Industries, Inc.**, to check for and download code and asset updates.

These connections may transmit technical information needed to deliver a compatible update, such as the platform, app version or configuration, technical update identifiers, and connection data, including the IP address.

This process is independent of the diagnostics and analytics options. It is not designed to transmit your workout history, notes, or photos.

More information: [Expo Privacy Policy](https://expo.dev/privacy).

## 7. Device permissions

Kairn may request permissions when you use particular features:

- **Camera and photos:** to take a photo or choose an image to associate with an exercise. Images are processed and stored locally; they are not automatically sent to PostHog.
- **Notifications:** for local workout-related alerts, such as timers and session reminders. These features do not use a push notification service to send your history to a server.
- **Files and destination apps:** importing or exporting information involves the system's file pickers and sharing options.

You can manage permissions in your device settings. If you decline one, the feature that needs it may be unavailable, but you can continue using Kairn's other features.

## 8. Backups, reports, and shared files

You can generate full backups, exchange files, and PDF reports.

A full backup may contain your history, notes, routines, images, and preferences. Exchange files contain the information you select. Reports contain the data relevant to the report generated. Your configured display name may also appear in filenames or reports.

Files are generated on your device. If you choose to share or save them using another app or provider, that app or provider receives their contents and processes them under its own terms.

Exported files do not include password protection or encryption provided by Kairn. Store and share them carefully.

Kairn's full backups do not include its telemetry consent preferences or telemetry identifiers.

Your operating system may also back up or transfer device data according to its settings. These operations are separate from the backups you explicitly create within Kairn.

## 9. Purposes and legal bases

Where the General Data Protection Regulation —GDPR— applies, legal bases depend on the processing involved:

- **Requested features:** performance of the service, to the extent processing is necessary to log, view, import, or export information.
- **Optional diagnostics and analytics:** your consent, which you can withdraw in Settings.
- **Voluntary feedback:** your consent to submit and process the message.
- **Legal obligations and rights requests:** compliance with applicable legal obligations.

Installing or using Kairn is not treated as consent to enable optional diagnostics or analytics.

**Review required before publication:** confirm the legal basis for update connections and technical security. If processing involves special categories of data, such as health data, also determine the applicable condition under Article 9 of the GDPR and the measures needed to comply with it. Performance of the service alone does not replace that requirement.

## 10. Recipients and international transfers

Transmitted data may be processed by PostHog and Expo and the providers they use to deliver their services, in accordance with their contracts and roles.

Information may also be received by the apps and people you choose to send files to, and by authorities where a valid legal obligation applies.

Kairn does not sell your personal data or use them for behavioral advertising.

The PostHog integration targets its European region. European hosting alone does not establish that no access or processing takes place from other countries. Expo may process information outside the European Economic Area.

**Review required before publication:** confirm the contracting entities, relevant countries, and applicable transfer safeguards under both providers' contracts, and explain how to request information about or a copy of those safeguards.

## 11. Data retention and deletion

Workout data remain on your device until you delete them using the available options or erase the app's data.

Removing a routine or withdrawing an exercise from the catalog does not necessarily delete its historical records: Kairn preserves history during various operations.

To remove all local data, use your system's options to erase the app's data or delete the app. On iOS, offloading the app while retaining its documents is not the same as deleting the app and its data.

Voluntarily submitted information, diagnostics, and usage data are retained for as long as necessary for the purposes described in this policy, taking into account issue resolution, app improvement, and applicable legal obligations. Technical information used by update services is retained in accordance with their operational purposes and applicable obligations.

You can request deletion of personal data we have received by emailing **samuelpayback@gmail.com**. Disabling telemetry stops new submissions but does not automatically delete previous ones.

Exported files, shared files, and backups stored outside Kairn must be deleted separately. Restoring your device may recover data from an earlier backup.

Uninstalling Kairn does not automatically delete information already transmitted to providers or files stored outside the app.

## 12. Security

Kairn uses the private app storage provided by the operating system and HTTPS connections for transmissions to the services described.

Automatic reports are filtered to limit their contents and exclude the workout records and other private data identified in this policy.

These measures do not constitute a guarantee of absolute security or end-to-end encryption. Protection of local data also depends on the security of your device and its backups.

Use your device's screen lock and protect exported files, especially if they contain sensitive notes or images.

## 13. Your rights

Depending on applicable law, you may request access, rectification, erasure, restriction, portability, or object to the processing of your data. You may also withdraw consent without affecting the lawfulness of earlier processing.

To exercise these rights, email **samuelpayback@gmail.com**.

Because Kairn has no accounts and events are not linked to your name or email address, we may be unable to locate particular data using your email address alone. We will explain what additional, proportionate, and necessary information may help identify the relevant records. You do not need to send us your entire workout history to make a request.

We cannot remotely modify or recover information that remains exclusively on your phone.

Where the GDPR applies, we will normally respond within one month, subject to the extensions and conditions provided by law.

You may lodge a complaint with the competent data protection authority. In Spain, this is the [Spanish Data Protection Agency](https://www.aepd.es/).

## 14. Children

Where the law requires authorization from a child's legal representative for particular data processing, that authorization must be obtained before processing takes place.

If you believe a child has submitted personal information without the necessary authorization, contact **samuelpayback@gmail.com** so we can assess appropriate measures.

**Review required before publication:** specify the intended audience and applicable age or authorization requirements, consistently with app store declarations and the countries where the app is distributed.

## 15. Changes and contact

We may update this policy when features, providers, or applicable obligations change.

We will publish the updated version with its date. Where a change requires new information or consent, we will provide that information and request consent before starting the relevant processing. Publishing an updated policy does not replace that consent.

For privacy questions:

**Samuel Petrucci**

Santa Cruz de Tenerife, Spain

[samuelpayback@gmail.com](mailto:samuelpayback@gmail.com)
