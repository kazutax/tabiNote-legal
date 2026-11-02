---
layout: page
lang: en
title: TabiNote Privacy Policy
permalink: /privacy-policy-en.html
---

# TabiNote Privacy Policy

[Japanese](https://kazutax.github.io/tabiNote-legal/privacy-policy.html)

**Last updated**: November 2, 2026

TabiNote (the "App") respects your privacy and tries to protect personal information. This Privacy Policy explains the information the App collects, uses, and stores.

The App is developed and operated by an individual. The operator handles collected information with care. Because the App is run by an individual, the operator does not guarantee security on the scale of a large service.

---

## 1. Information we collect

The App collects and stores the following information.

### 1.1 Account information
- **Email address**: Used to create and authenticate an account. If you use Sign in with Apple, Apple's settings let you hide your email address (Apple's private relay address). In that case, the App receives a forwarding address issued by Apple.
- **Password**: Used to authenticate an account you registered with an email address. It is stored as a hash. The developer cannot read it in plain text. If you use only Sign in with Apple, the App does not keep a password.
- **Username**: An ID that is unique to each user, made of lowercase letters, numbers, and underscores.
- **Display name**: The name shown on your profile (at least 2 characters). The first time you use Sign in with Apple, the App may use the name Apple provides, if you choose to share it, as your initial display name.
- **Profile image**: An icon image you upload.

You can create an account either by registering an email address and a password, or with Sign in with Apple. With Sign in with Apple, Apple shares with the App a user-specific identifier, your name (first time only, and optional), and an email address or a hidden private relay address. When you sign in, you choose what information Apple shares with the App.

### 1.2 Trip information
- **Trip title and description**: The trip record you create.
- **Companions on a trip**: Information about people you add to a trip.
- **Dates**: The start and end dates of a trip, and the visit date of each place.
- **Photos**: Image files you upload as memories of a trip. The current version accepts photos only. For each trip, you can set who can see it: Public, Friends only, Companions only, or Only me. In the App, it is shown only to the people you selected. Photos are delivered at a unique URL that is hard for others to guess. Someone who knows that URL may be able to view the photo even if it sits outside that audience (see section 6).
- **Location**:
  - GPS information in a photo (EXIF data)
  - A place you enter by hand
  - Your device's location, if you allow location access. It is used to show your current location on the map and to set location on a photo automatically.
- **Tags**: Place tags, custom tags, and similar tags.

### 1.3 Other information
- **Friends**: Information about friend requests, approvals, and your friends list.
- **Likes**: How the like feature is used on a trip.
- **Notifications**: Information shown in the in-app notification list, including friend requests, invitations to a trip, likes, and updates to a trip.
- **Notification settings**: Whether each of those notification types is on or off.
- **The device's notification permission**: If you allow notifications on your device, the App uses that permission for badges and similar display. You can still use the in-app notification list if you do not allow them.

### 1.4 Optional profile details (if you enter them in Settings)
- **Date of birth**, **gender**, **place of residence (country and city)**, and **travel style** (for example, traveling alone or a family trip): You may enter these in account settings. You can leave them blank and still use the App's main features.
- **Purpose of use**: They may be used to improve the quality of the Service, and, in the future, to personalize what is shown or suggested.
- **Who can see them**: By design, they are not shown on a public profile that other users see. If a later version of the App changes who can see them, the App will say so in this Policy or with an in-app notice.

### 1.5 Usage and device information (logs of how you use the App)

To improve the quality of the Service and to understand defects, the App collects and stores the following information about how you use the App. This information is recorded together with the account you are using (your user ID).

- **Usage logs (events)**: Starting the App (the start of a session), screens you opened, the type of major actions such as posting a trip, and the date and time they happened.
- **Device and app information**: Platform (iOS / Android), the App's version and build number, and the OS version.

The operator handles these logs so that they do not directly include your name, email address, password, or similar information. The operator uses this information for statistics and analysis, to improve the App and to understand how it is used. The operator does not use it for advertising, and does not sell it to third parties.

---

## 2. How we use information

The App uses collected information for the following purposes.

### 2.1 Providing the Service
- Account authentication and session management
- Saving and showing trip records
- Friends, and companions on a trip
- Likes, and achievements (prefectures and countries you have visited, and similar records)
- Showing a trip on a map, and filtering trips by user search and @mentions
- Delivering in-app notifications, and applying your notification settings

### 2.2 Improving the Service
- Checking how the App behaves, and fixing defects
- Improving performance
- Developing new features
- Analyzing and compiling statistics on how the App is used, including which features and screens are used. This includes the usage logs and device information in section 1.5.

### 2.3 User support
- Answering inquiries
- Managing accounts

### 2.4 Why we handle information

- **Contract to provide the Service**: Creating and authenticating an account, saving trip records, showing a trip to the audience you selected, friends, likes, and in-app notifications are handled under the contract to provide the Service.
- **Usage logs**: Handled to understand defects and to improve the App. They are not used for advertising. If you want the App to stop handling usage logs, email support@kazutak.com.
- **Permission on your device**: The photo library and your device's location are used when you allow them on the device. If you refuse them, you can still enter a place by hand.
- **What you choose to enter**: Date of birth, gender, place of residence, and travel style are handled only when you enter them. You can leave them blank and still use the App's main features.

---

## 3. Third-party services and processors

The App uses the following third-party services. Data is stored with Supabase and with Cloudflare R2, as follows.

### 3.1 Supabase
- **Used for**: Authentication, and storage of the database (account information, trip records, usage logs, notifications, and similar records)
- **Image files**: Files for trip photos and profile images are stored in Cloudflare R2, in section 3.2
- **Provider**: Supabase Inc.
- **Privacy policy**: https://supabase.com/privacy

### 3.2 Cloudflare R2
- **Used for**: Storage of trip photos and profile images. The current version accepts photos only for a trip.
- **Provider**: Cloudflare, Inc.
- **Privacy policy**: https://www.cloudflare.com/privacypolicy/

### 3.3 Sign in with Apple
- **Use**: Authentication when you choose Sign in with Apple to sign in or create an account
- **Provider**: Apple Inc.
- **Information shared**: A user-specific identifier, your name (first time only, and optional), and an email address or Apple's private relay address
- **Privacy policy**: https://www.apple.com/legal/privacy/
- **Note**: If you hide your email address, the App receives a hidden forwarding address issued by Apple. Your real email address is not shared with the App. To check or disconnect the Apple Account link, use Settings → [your name] → Sign-In & Security → Sign in with Apple on your device.

---

## 4. Storage and security

### 4.1 How long data is kept, and how much can be stored
- **How long**: While your account is active, data is generally stored in the cloud.
- **Storage limit**: When operation requires it, including keeping the Service running, security, and managing infrastructure cost, the operator may set a storage limit for each user, or delete data for an account that has not been used for a long time. Those conditions are shown in the [Terms of Use](https://kazutax.github.io/tabiNote-legal/terms-of-service-en.html) and in the App.
- **Showing how much you use**: My Page and similar screens in the App may show an approximate amount of cloud storage in use. The figure is based on the total of the sizes recorded at upload. It may not exactly match the space used in cloud storage.
- **When you delete your account**: Related data is deleted as well.
- **Deleting media**: Photos, profile images, and similar media are placed on a deletion queue when you delete your account or delete them yourself, and may be deleted on the server in batches at intervals. Deletion may not finish immediately. The App does not guarantee immediate deletion.

### 4.2 Security
- Passwords are stored as hashes.
- Data in transit is encrypted with HTTPS.
- Authentication uses access tokens.

---

## 5. Your rights

You have the following rights.

### 5.1 Access to data, and correction
- From Settings in the App, you can view and correct your profile information.

### 5.2 Deletion of data
- From Settings in the App, you can delete your account.
- Deleting your account deletes all personal information and trip records.

### 5.3 Managing location
- GPS information in a photo may be read automatically from the photo's EXIF data.
- Your device's location is managed by the operating system's settings and by the permission dialog when you use the App.
- If you do not want to share location, consider removing location information before you upload a photo.
- If you refuse access to the photo library or to your device's location, you can still enter a place by hand.

### 5.4 Managing notifications
- From Settings in the App, you can turn each notification type on or off.
- Device notifications, such as badges, are managed from the Settings app on your device.

### 5.5 Requests by email

You can ask for the following by email to support@kazutak.com.

- Disclosure of your personal information
- Correction of something you cannot fix on a screen in the App
- An objection to how usage logs are handled
- A copy of your data

We aim to reply within about one month.

---

## 6. Sharing data

The App does not share your personal information with third parties, except in these cases:

- Disclosure is required by law
- You have given explicit consent
- The information is provided to a third-party service named in this Privacy Policy
- Other users of the Service view a trip you posted, within the audience you selected

The audience setting controls who can see a trip and its media in the App. Photos are delivered at a unique URL that is hard for others to guess. Someone who knows that URL may be able to view the media even if it sits outside the audience you selected. Take care with sharing sensitive content, and with how you handle the URL.

---

## 7. Use by minors

The App is not aimed mainly at a particular age group. If a minor uses the App, a parent or guardian should give permission first. The App does not intentionally collect personal information from minors.

---

## 8. Changes to this Privacy Policy

This Privacy Policy may change without notice. If there is an important change, the App will notify you in the App. If you keep using the App after a change, you are deemed to have agreed to the changed Privacy Policy.

---

## 9. Contact

For questions or comments about this Privacy Policy, email:

- **support@kazutak.com**

---

## 10. Scope

This Privacy Policy applies to use of this App (TabiNote). For services and websites other than this App, each one's privacy policy applies.
