# Privacy Policy

**Last updated: October 22, 2026**

viiti ("we", "us", or "our") explains here what information the viiti app stores and how it is used.

## Using viiti and signing in

You can use viiti without creating an account. If you choose Apple or Google sign-in, viiti sends the provider sign-in token to Supabase to authenticate your account and connect it to your backup. Supabase Auth can retain the account identifier and profile details returned by the provider, such as an email address, name, or profile image URL. viiti does not receive your provider password.

The Google Sign-In SDK included in viiti has a privacy manifest that declares linked data categories including name, email, phone number, coarse location, other data types, user ID, device ID, and other usage data. It lists App Functionality and Analytics purposes for some categories and declares that it does not track users. viiti's sign-in code uses Google authentication and the provider profile name; it does not request phone-number or location scopes. See [Google's versioned SDK privacy manifest](https://github.com/google/GoogleSignIn-iOS/blob/a7965d134c5d3567026c523e0a8a583f73b62b0d/GoogleSignIn/Sources/Resources/PrivacyInfo.xcprivacy) and [Google's Privacy Policy](https://policies.google.com/privacy) for the SDK and provider disclosures.

## Habit data and cloud backup

viiti stores habits and progress on your device. When you sign in, the app can also store an account-linked backup in Supabase. The backup includes information such as habit names and symbols, completion dates, focus session details and lengths, focused minutes, streak and freeze information, reflections, and quit notes. This information is associated with your Supabase account so it can be restored after reinstalling viiti or signing in on another device. The account profile and backup remain associated with your account until the account is deleted or otherwise removed; no automatic retention period was identified in the service configuration reviewed for this policy.

App preferences, reminder schedules, Screen Time selections, and Apple StoreKit purchase records are not included in the habit backup. If you are offline, local habit tracking remains available, while sign-in and cloud backup require an internet connection. If backup cannot be reached, viiti keeps your local progress and offers a retry in Settings. If local and cloud copies conflict, syncing pauses and both copies are preserved.

## Screen Time and reminders

viiti uses Apple's Screen Time frameworks to block selected apps and categories. The selection tokens are stored on your device and are not part of the Supabase habit backup. Reminder preferences are stored on your device, and iOS schedules reminders as local notifications.

## Subscriptions and payments

Apple handles subscription purchases and billing through the App Store. viiti uses StoreKit to check subscription products and entitlement status. Payment details and StoreKit purchase records are not included in the Supabase habit backup. For billing questions, contact Apple Support or manage your subscription in iPhone Settings → Apple ID → Subscriptions.

## Signing out, deleting, and uninstalling

Signing out disconnects the account session but keeps habit data stored on your device. Signing out does not delete the account or cloud backup. Uninstalling viiti also does not delete the cloud backup.

For a signed-in account, open **Settings → Delete account** while signed in to the account that owns the backup. The app requests deletion of that account and its cloud backup. The app clears the account's local habit data only after the server confirms deletion. If the server cannot confirm the request, the app shows an error and keeps local data; treat the request as incomplete and contact [getviiti@gmail.com](mailto:getviiti@gmail.com) for help. If local cleanup cannot finish after server confirmation, the app reports that and offers a retry. For a guest with no cloud backup, **Settings → Delete account** clears data stored on that device.

Deleting a viiti account does not cancel an App Store subscription. Manage or cancel subscriptions in iPhone Settings → Apple ID → Subscriptions.

## Contact

For privacy questions or account-deletion help, email [getviiti@gmail.com](mailto:getviiti@gmail.com).

---

[Back to Support](index.md)
