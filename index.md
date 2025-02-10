# Privacy Policy

*Effective Date: 25th January 2025*

## Introduction

Welcome to Tangoo ("we," "us," or "our"). Tangoo is a Japanese dictionary mobile application designed to help users learn Japanese through an offline-first dictionary, word lists, customizable tests, short stories and more.

To enhance your learning experience and improve our services, Tangoo integrates certain features that process data, including Firebase Analytics and Crashlytics. These tools help us understand how the app is used, identify issues, and improve functionality.

Additionally, Tangoo offers optional features like User Accounts, Subscriptions, and Cloud Backups, which require processing additional user data. This Privacy Policy explains what data we collect, how it is used and stored, and your rights regarding your personal information.

## Information Collection and Use

Tangoo is designed to provide an offline-first learning experience. However, to enhance your experience and improve the app, certain features require the collection and storage of data. Below, we explain what data is collected, how it is used, and where it is stored.

### Data Collected Locally

The following data is stored only on your device and is not transmitted to our servers or third-party services unless you create a user account:

- **Dictionary**: The entire Japanese dictionary data is saved locally in a Database on your device.
- **Word Lists**: You can create custom word lists and assign words to them. This data is saved locally on your device.
- **Grammar Favorites**: You have the option to mark grammar items as favorites. These preferences are stored on your device.
- **Test Data**: Any test settings, progress or performance data from spaced repetition tests is stored locally to enhance your learning experience.

### Data Collected Online

Certain features require data to be stored online using Firebase services:

- **User Accounts**: If you create an account, we collect your email address to enable authentication via Firebase Auth. This is required for optional features like Subscriptions and Cloud Backups.
- **Subscription Data**: If you subscribe to Tangoo Premium, we store purchase verification details (such as purchaseDate, purchaseToken, and platform) in Firestore to verify your subscription status. This data is securely processed and used solely for subscription verification and access management. We do not share it with third parties outside of Firebase and Google Play.
- **User Feedback**: Tangoo allows users to submit feedback to help improve the app. Feedback is collected anonymously and does not include any personally identifiable information.
Submitted feedback is stored securely in our database and may be reviewed to enhance Tangoo’s features. By submitting feedback, you agree that we may analyze and use it to improve our services.

### Analytics Data
To improve Tangoo, we use Firebase Analytics to collect non-personal usage data. This includes:

- Feature usage (e.g., which pages are accessed).
- Device information (e.g., operating system, device model, and app version).
- Session data (e.g., session duration and frequency of use).

This data is aggregated and anonymized and is used to understand how users interact with the app and prioritize improvements. Firebase Analytics runs automatically for all users and is not tied to any personally identifiable information unless you create an account.

### Crash Reporting
Firebase Crashlytics is used to identify and fix bugs or technical issues in Tangoo. When a crash occurs, Crashlytics collects technical data, including:

- Device information (e.g., operating system, app version).
- Crash logs and stack traces.
- Information about the actions leading to the crash.

This data helps us improve the app’s stability and functionality. Crashlytics does not collect personally identifiable information unless it is manually tied to a user account (e.g., for premium users reporting issues).

### Subscription Data
If you purchase a Premium Subscription, we store certain data in Firestore to verify and manage your subscription. This includes:

- order id – A unique id from Google Play used to identify the order
- product id - An identifier of the product that was purchased
- purchase token – A unique token from Google Play used for subscription verification.
- platform – The operating system (Android or iOS) where the purchase was made.
- expiry date – The expiry date of the currently active subscription.
- purchase date – The date the subscription was purchased or renewed.
  
This data is used to confirm active subscriptions, grant premium access, and prevent fraud. Tangoo does not store or process payment information—all payments are handled by Google Play.

### Why We Collect This Data
The data collected is used to:

- Provide and improve the app’s features.
- Enhance stability and fix issues.
- Enable optional features like User Accounts, Subscriptions, and Cloud Backups.


## User Accounts and Subscriptions

Creating a user account in Tangoo is optional, but it is required to access certain features, such as Premium Subscriptions and Cloud Backups. Below, we explain what data is collected, how it is used, and your responsibilities as a user.

### Purpose of User Accounts
User accounts enable access to the following features:

- Premium Subscriptions: Allows users to unlock premium features, such as advanced tests and the Short Stories library.
- Cloud Backups: Provides the ability to securely back up your local data (e.g., Word Lists and Spaced Repetition scores) to the cloud, so it can be restored on other devices.

### Data Collected During Account Creation
When you create an account, the following data is collected and processed through Firebase Authentication:

- Email Address: Used for account identification and authentication.
- Authentication Method: Whether you sign in using an email/password or via Google Login.

We do not collect any other personal information beyond what is required for authentication.

### Data Usage
The data collected during account creation is used solely to:

- Authenticate and secure your account.
- Provide access to optional features tied to your account, such as Premium Subscriptions and Cloud Backups.
- Verify and maintain an active subscription status through Google Play.

If you cancel your subscription, you will retain access to premium features until the end of your billing cycle, after which your subscription data will no longer grant premium access.
  
### Password Recovery
If you forget your password for an email-based account, you can contact us at daniel.tangooapp@gmail.com to request a manual password reset. Note that we do not have access to your password but can assist with resetting it.

### User Responsibilities
You are responsible for maintaining the confidentiality of your login credentials. If you suspect unauthorized access to your account, please contact us immediately at daniel.tangooapp@gmail.com.

### Data Deletion
If you choose to delete your account, all associated online data (e.g., Cloud Backups) will also be permanently deleted. Offline data stored locally on your device will not be affected.

### Account Deletion
Users can request the deletion of their account and associated data by contacting us at daniel.tangooapp@gmail.com. Upon request:
- Your email address and associated account data will be permanently deleted.
- Certain data may be retained for up to 7 years if required for tax, legal, or compliance purposes. After this period, all retained data will be permanently deleted.

### Subscription Data Retention
If you cancel your subscription but do not delete your Tangoo account, we retain your subscription data for continued premium access until the end of your billing cycle.
If you delete your Tangoo account, all subscription data will be permanently deleted, and premium access will be revoked immediately.
For compliance and fraud prevention, certain subscription records may be retained for up to 6 months after expiration but will not be used for tracking or marketing.

## Third-Party Services

Tangoo uses the following third-party services to enhance functionality, improve the app, and ensure data security. Below is an overview of these services, the data they process, and why they are necessary.

### Firebase Authentication
- Purpose: Enables user account creation, login, and authentication using email/password or Google Login.
- Data Collected:
    - Email address.
    - Authentication method (e.g., email or Google Login).
- Why We Use It: To securely manage user accounts and provide access to features like Premium Subscriptions and Cloud Backups.

### Firebase Firestore (Database)
- Purpose: Stores user account information, subscription verification data, and Cloud Backup data.
- Data Collected:
    - User Account Data: Email and authentication method.
    - Subscription Data: purchaseDate, purchaseToken, platform, and subscriptionStatus (for verifying premium access).
- Why We Use It: To securely store and manage user accounts and subscriptions while ensuring premium feature access.
- For Users who don't create an account, we are not saving any data in Firestore.

### Firebase Cloud Functions (Backend Processing)
- Purpose: Processes backend logic such as verifying Google Play subscriptions and handling automated tasks.
- Data Processed:
    - Subscription Verification: Automatically checks whether a user has an active subscription using their purchaseToken.
- Why We Use It: To enable secure, automated verification of subscriptions without requiring users to manually validate their purchases.
  
### Firebase Analytics
- Purpose: Tracks app usage to help us understand user behavior and improve Tangoo’s features.
- Data Collected:
    - App usage data (e.g., screens accessed, session duration).
    - Device information (e.g., OS version, device model).
- Why We Use It: To analyze which features are most used and identify areas for improvement.
- Opt-Out Option: If you wish to opt out of Firebase Analytics, please contact us at daniel.tangooapp@gmail.com.

### Firebase Crashlytics
- Purpose: Monitors app performance and identifies technical issues or crashes.
- Data Collected:
    - Crash logs and stack traces.
    - Device information (e.g., OS version, app version).
- Why We Use It: To diagnose and resolve crashes, ensuring the app runs smoothly for all users.
- Opt-Out Option: If you wish to opt out of Crashlytics, please contact us at daniel.tangooapp@gmail.com.

### Google Play
- Purpose: Facilitates subscription payments and manages premium feature access.
- Data Collected: Google Play collects payment information and processes transactions. Tangoo does not store or process your financial information.
- Why We Use It: To securely handle payments for Premium Subscriptions and manage subscription statuses.
- Google Play Policies: You can learn more about Google’s privacy practices here:
    - [Google Privacy Policy](https://policies.google.com/privacy)

### Data Sharing with Third Parties
The data shared with Firebase and Google Play is necessary to provide the services outlined above. Both Firebase and Google Play comply with strict security and privacy standards.

### Firebase Privacy Policy and Terms
For more information on Firebase’s data handling practices, you can review their Privacy Policy and Terms of Use:
- [Firebase Privacy Policy](https://firebase.google.com/support/privacy)
- [Firebase Terms of Service](https://firebase.google.com/terms)

## Security

Tangoo takes data security seriously and implements measures to protect your personal information and user data. For features like User Accounts and Cloud Backups, data is stored and processed through Firebase, which complies with industry-standard security protocols, including encryption during data transmission and storage.

While Firebase provides secure infrastructure, we recommend users take the following precautions to enhance security:

- Use strong, unique passwords for your account.
- Keep your login credentials confidential.
- Secure your device with a password, biometric lock, or similar measures.
  
If you suspect unauthorized access to your account or data, please contact us immediately at daniel.tangooapp@gmail.com.

## Children's Privacy

Tangoo is suitable for users of all ages. However, we do not knowingly collect personal information from children under the age of 13 without parental consent. For optional features like User Accounts and Subscriptions, users must be at least 13 years old to comply with applicable privacy laws.

If you are a parent or guardian and believe your child has provided us with personal information without your consent, please contact us at daniel.tangooapp@gmail.com. Upon verification, we will promptly delete any such data from our systems.

## Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Since Tangoo is still in active development, future features might significantly impact what data we store and process. Any changes will be posted on this page with an updated effective date. We encourage you to review this Privacy Policy periodically for any changes.

## Contact Us

If you have any questions or suggestions about our Privacy Policy, please contact us:

- **Email**: daniel.tangooapp@gmail.com
