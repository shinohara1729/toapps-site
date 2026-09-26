---
title: Privacy Policy
locale: en
documentId: privacy
revision: 1
versionDate: 2026-09-19
effectiveDate: 2026-09-19
nextReviewDate: 2026-12-19
status: published
checksumSha256: ''
---

<!-- markdownlint-disable-next-line MD025 -->
# Privacy Policy

TO Apps (the “Operator”) explains below how information is handled for the Shuffleep app (the “Service”).

> The Japanese version prevails in the event of a discrepancy with the English version, without limiting mandatory consumer or language rights under applicable law.

## Article 1 Information Collected and Used

### 1.1 Information on the Device

| Information                                                                          | Purpose                                    |
| ------------------------------------------------------------------------------------ | ------------------------------------------ |
| Onboarding status and settings such as theme, volume and session composition         | Restoring settings and displaying screens  |
| Consent time, document revision, language, app version and OS type                   | Recording consent and presenting revisions |
| Custom Word Set names and selected words                                             | Saving sets created by the User            |
| Downloaded audio and management information such as target, size and completion time | Offline playback and download management   |

The app does not upload these items to the Operator’s servers. However, depending on OS settings, settings, consent records and Custom Word Sets may be included in the OS provider’s cloud backups or device transfers. Audio files are configured for backup exclusion, but this does not guarantee the behavior of every device or OS.

Custom Word Set names allow free text. Please avoid unnecessary personal information or third-party secrets. Playback state is held in memory; the app does not measure sleep or save a session history.

### 1.2 External Transmissions and Purposes

The following transmissions accompany use of the app and related pages. HTTPS connections also disclose connection information such as an IP address to the recipient. Please also review each provider’s privacy information.

| Recipient                                                                                                         | Information and trigger                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Operator’s purpose                                                 | Recipient’s purpose                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| [RevenueCat, Inc.](https://www.revenuecat.com/privacy/)                                                           | Billing functionality after acceptance of the Terms and this Policy, purchases and restores: customer ID, purchase/subscription information, store type and technical device/app information                                                                                                                                                                                                                                                                                 | Determining entitlements, restoring purchases and support matching | Providing subscription management, maintenance and security                                                                              |
| Operator’s delivery infrastructure (Cloudflare, Inc., `assets.toapps.dev`)                                        | Audio listings/downloads: RevenueCat customer ID, requested paths and connection information                                                                                                                                                                                                                                                                                                                                                                                 | Checking Premium entitlement and delivering audio                  | Delivery, caching, operations and security by [Cloudflare](https://www.cloudflare.com/privacypolicy/)                                    |
| Apple / Google stores                                                                                             | Purchases, restores and subscription management: store account-related purchase information and payment information                                                                                                                                                                                                                                                                                                                                                          | Processing purchases and checking entitlements                     | Payment, subscription management and fraud prevention under the stores’ own terms and privacy policies                                   |
| [Google Mobile Ads](https://policies.google.com/privacy) (Google LLC)                                             | After the Terms and this Policy are accepted, consent management (UMP) takes place, followed by SDK initialization if UMP permits it. Ad requests are made when UMP permits them and Free ad-display conditions are met. The SDK may process IP/connection information and approximate location inferred from it, available advertising/device identifiers, ads shown, app interactions, and diagnostic, performance and crash information. Ad requests are non-personalized | Serving and measuring non-personalized ads                         | Advertising, analytics, fraud prevention, maintenance and security by Google Mobile Ads. Google’s privacy policy and related terms apply |
| [Expo](https://expo.dev/privacy)                                                                                  | App startup/update checks, which may occur before consent: EAS Client ID, OS/app/runtime versions, update and connection information; fatal error information in circumstances such as update recovery                                                                                                                                                                                                                                                                       | Delivering updates and recovery from update failures               | Providing the update infrastructure, diagnostics, maintenance and security                                                               |
| [GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) (GitHub Pages) | Legal document/update metadata retrieval and public page access, including before consent: IP address, requested URL and browser/connection information                                                                                                                                                                                                                                                                                                                      | Providing legal information and public pages                       | Hosting, access processing, maintenance and security                                                                                     |

RevenueCat’s “anonymous ID” is generated without entering a name but can be linked to purchases; it does not mean legal anonymization. The delivery infrastructure caches entitlement results for approximately five minutes using a key containing this ID. Cache expiry does not delete the providers’ access or operational logs.

The Operator has no separate member-profile database. This does not mean that nothing is stored on servers: short-lived caches and external providers’ records exist.

### 1.3 Information Received in Inquiries

Emails to `contact@toapps.dev` include the sender’s address, any name voluntarily supplied, message/attachments and information needed to match purchases. Delivery and storage use Cloudflare Email Routing and the destination email service. This information is used to respond to inquiries and rights requests and retain necessary handling records. Do not send diagnoses, detailed health information, passwords, full payment-card numbers or unnecessary identity documents.

### 1.4 Other Information

The app has no features collecting GPS location, microphone recordings, camera images, contacts, photo libraries or biometric measurements such as HealthKit data. There is no profile registration for names, addresses, dates of birth or email addresses. Inquiries and voluntary text input are addressed above.

Advertising SDKs are used after the Terms and this Policy have been accepted to serve non-personalized ads. The advertising SDK processes information as described in Section 1.2. No separate analytics or crash-reporting SDKs, including Crashlytics, are used as of this Policy version, but the advertising SDK’s own measurement and diagnostics and Expo update and recovery communications still occur. Push tokens are not obtained for local notifications.

## Article 2 Purposes of Use

Information is handled to provide features, save settings, verify purchases/restores/delivery entitlements, deliver updates, maintain security, handle inquiries and rights requests, manage consent, serve and measure non-personalized advertising, and meet legal obligations. New purposes will be subject to required notice, consent and other procedures.

## Article 3 Third Parties and Business Succession

Personal data is not disclosed to third parties without consent except where permitted or required by law. Necessary service providers and overseas handling are addressed in Articles 4 and 5. A business succession involving information will be subject to required safeguards and the existing purposes of use.

## Article 4 External Providers

RevenueCat, Cloudflare, Expo, GitHub, Google LLC (Google Mobile Ads) and inquiry email delivery/storage providers are used for subscription management, delivery, updates, public pages, non-personalized advertising delivery and measurement, and email handling. Information and purposes are listed in Article 1. This does not mean that all processing, including Google’s advertising services, is performed on the Operator’s behalf; roles depend on each service’s terms, settings and applicable law. Entrusted handling is limited to what is needed and managed through review of contractual terms and handling practices.

Apple and Google independently handle store accounts, payment and their own purchase records. Not all store activities are performed on the Operator’s behalf. OS cloud backups likewise depend on the User’s OS account and settings.

## Article 5 Overseas Handling

External providers include businesses based in the United States. Delivery infrastructure and CDNs, such as Cloudflare’s, process data in multiple countries and regions, including Japan; destinations are not limited to the United States. Google’s advertising services may also process information in multiple countries and regions, including outside the User’s country of residence.

Where handling constitutes an international provision of personal data, applicable legal requirements include reviewing protections and relevant systems and providing information, obtaining consent or following other necessary procedures. Outsourcing alone does not remove international-transfer requirements. Questions about countries and safeguards may be sent to the contact in Article 14.

## Article 6 Security and Retention

1. App, delivery, update and legal-page communications use HTTPS. Device settings are stored in app storage; this does not mean AsyncStorage itself encrypts its contents. The Operator has no feature collecting or storing store passwords or full card numbers. Customer IDs, purchase status and consent records are stored or processed.
2. Device data remains until deleted by the User or otherwise removed. Entitlement caches expire after approximately five minutes but may be created again on subsequent use. Subscription, update, delivery and advertising records follow providers’ settings, contracts and legal obligations rather than the cache’s retention period.
3. Inquiry and rights-request records are kept as needed for handling and deleted when no longer required. Records may be retained to the extent needed for legal retention, disputes, fraud prevention or other legitimate requirements. Users may inquire about retention or deletion of specific records.

## Article 7 Access, Correction, Deletion and Other Requests

1. Requests for access, correction, deletion, cessation of use or other rights under applicable law may be sent to the email address in Article 14.
2. Describe the request and relevant OS and purchase store. Purchase-related requests may require a support ID and only the necessary parts of purchase evidence. An ID alone is not treated as proof of identity. Passwords and full card numbers are not requested. No identity verification is required to request the Operator’s name or telephone number.
3. The Operator aims to respond within 30 days of receipt. Applicable statutory deadlines and extension procedures take precedence. If more investigation is needed, the reason and expected response timing will be explained.
4. Resetting settings does not erase all information. Custom Word Sets and downloaded audio can be deleted from their respective management screens. Uninstalling does not also erase OS backups, store purchase history or records held by providers or email services. Instructions will be provided for the relevant data.
5. After matching the request, the Operator will process deletion or cessation of use for records under its control, including relevant RevenueCat records. Requests concerning a store’s own purchase records will be directed to that store. Google’s advertising records follow its settings, terms, applicable law and procedures; the Operator cannot directly delete all such records. Reusing the app or restoring purchases may recreate records. Data deletion does not cancel a subscription; cancellation must be completed with the purchasing store.

## Article 8 Cookies, Advertising and Analytics

The app uses an advertising SDK after the Terms and this Policy have been accepted to serve non-personalized ads. Non-personalized ads are not selected based on past behavior, but identifiers and connection information may still be processed for frequency capping, aggregate reporting and fraud prevention. The app does not use a separate analytics SDK. Subscription and update identifiers, and the information and purposes associated with the advertising SDK, are described in Articles 1, 2 and 4. External store or support pages follow their providers’ cookie policies.

## Article 9 Children and Minors

The Service is not directed to children under 13. If the Operator learns that a child under 13’s information has been collected, it will stop relevant processing, make necessary checks, delete information and take other steps required by applicable law. Parents may contact the address in Article 14. Minors must obtain legally required permission. Age-signal collection is not enabled in the current standard distribution configuration. Use alone is not treated as valid parental consent required by law.

## Article 10 Incidents

If leakage, loss, damage or another incident is discovered, the Operator will investigate, contain it and address recurrence. Required reports to supervisory authorities and notices to affected people will be made. Appropriate methods include public pages, notices accessible in the app and email to known contact addresses.

## Article 11 Revisions

Changes and their effective date will be announced at the public URL or through other appropriate channels. Legally required consent will be requested for material changes, such as changes in collected information or purposes. The app may also ask Users to accept revised documents.

## Article 12 Users in the United States and Canada

The Operator does not sell personal information for consideration. Information is sent to and processed by Google LLC for non-personalized advertising. The Operator does not share information to serve ads based on behavioral histories across different services. Non-personalized settings do not mean that no information is sent to Google or that all processing is outside legal definitions of sale or sharing. The advertising processing in Article 1 is also subject to applicable law and Google’s settings and terms. Requests concerning rights under the laws of the User’s residence are accepted through Article 7. The individual proprietor is responsible for personal information protection. Conditions for Canada will be prepared before offering the Service there.

## Article 13 Operator Information

| Item                 | Content                                                                                                                                                            |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Name (business name) | TO Apps (sole proprietor; the operator's name and telephone number will be provided without delay by email upon request sent to the contact address in Article 14) |
| Address              | Konotora Bldg 7F, 1-1-14 Shimomeguro, Meguro-ku, Tokyo 153-0064, Japan                                                                                             |
| Representative       | The same individual as the name above                                                                                                                              |

## Article 14 Contact Information

For inquiries regarding this Policy, please contact the following.

- Email: [contact@toapps.dev](mailto:contact@toapps.dev)
