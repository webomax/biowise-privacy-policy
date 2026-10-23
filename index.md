
**Effective Date:** October 24, 2026

## 1. Introduction

Welcome to **BioWise**, a mobile application developed and published by **Webomax Bilişim Teknolojileri Limited Şirketi** ("we," "us," or "our"). We are committed to protecting your privacy. This Privacy Policy explains how we collect, use, process, and safeguard your information when you use the BioWise mobile application (the "App").

Because BioWise is a health and habit-tracking application, we have designed our architecture with a "Local First" privacy approach. **We do not store your personal health data on our servers.**

## 2. Information We Collect and How We Store It

To provide you with the BioWise experience, data is processed in the following ways:

- **Local Device Data (Health & Profile Information):** Information such as your age, gender, height, weight, daily habit logs (food, sleep, mood, movement), and custom settings are stored **locally on your device**. We do not store this personal health data on our servers. It only leaves your device when you use an AI feature, as described in Section 3.A.
- **Device & Usage Data:** We may collect anonymous, non-identifying information about your device (e.g., operating system version, device model) and app usage (e.g., screen visits, crash reports) to improve app stability and performance.

## 3. Third-Party Services and Data Sharing

While your core data remains on your device, BioWise utilizes specific third-party services to power core features and manage subscriptions. These services only receive the data strictly necessary to perform their functions:

**A. AI Features (BioWise AI Service, Google Gemini and OpenRouter)**

To provide AI Photo Logging and personalized daily insights, BioWise uses third-party AI models. **We ask for your permission in the App before any data is sent for AI analysis**, and you can turn AI features off at any time in Profile.

- **What is shared:** When you scan a meal, the photo you choose (resized, without photo metadata such as location) is sent. When you request a Premium daily insight, a summary of your logs is sent: calorie and step targets, target weight, recent averages, today's calories, nutrients, activity, steps, sleep, mood, and the mood note you wrote. Your name is not sent.
- **How it is sent:** Data first goes to the BioWise AI service, which runs on Cloudflare and is operated by us. It forwards the request to **Google Gemini** (Google's AI API). If Gemini is unavailable, it is forwarded instead to **OpenRouter**, which passes it to the provider of the AI model we have selected. We ask OpenRouter to use only providers that do not store or train on the data. Requests to AI providers do not include your App User ID or other identifiers.
- **How it is used:** The data is used solely to return the nutritional analysis or insight to your device. The BioWise AI service does not store your photos or logs, and we do not use your images or data to train AI models. The AI providers process it under their own terms and privacy policies.

**B. BioWise AI Service (Cloudflare)**

To enforce usage limits and check your Premium status, the BioWise AI service receives your anonymous RevenueCat App User ID with each AI request and keeps:

- daily usage counts (for example, how many AI scans you used today) and a record that your one free AI scan was used;
- a short-lived copy of your Premium status (checked with RevenueCat and, for promotional access, with InfluTo);
- daily counters keyed by a one-way hash of your IP address, which changes every day, to prevent abuse;
- technical logs (time, feature used, App User ID, success or error), without your photos or logs.

**C. RevenueCat (Subscription Management)**

We use RevenueCat to manage in-app purchases and premium subscriptions.

- **What is shared:** RevenueCat collects anonymous App User IDs, device information, and purchase history (e.g., when a subscription starts or expires).
- **How it is used:** This ensures you are correctly granted access to BioWise Premium across your devices. RevenueCat **does not** have access to your weight, dietary logs, or any personal health data.

**D. InfluTo (Referral and Promo Codes)**

We use InfluTo to attribute app installs and subscriptions to creator referral links and promo codes, and to grant promotional Premium access.

- **What is shared:** Your anonymous App User ID, a referral or promo code if you used one, basic device information (platform, operating system version, screen size, time zone, and language) used to match an install to a referral link, and subscription events such as viewing the paywall or completing a purchase.
- **How it is used:** To credit the creator who referred you and to check whether you have promotional Premium access. InfluTo does not receive your health data, photos, or logs.

**E. Apple HealthKit & Google Fit (Optional)**

You may choose to grant BioWise permission to read data (such as step counts or sleep data) from Apple HealthKit or Google Fit. This data is only read locally on your device to update your daily progress rings and is never transmitted to our servers.

## 4. Data Security

Because your profile and health data are stored locally on your device, the security of this data relies heavily on your device's built-in security features. We strongly recommend enabling a passcode, FaceID, or biometric lock on your mobile device to protect your health information. Data transmitted to our AI service and to third parties (like Google Gemini, OpenRouter, RevenueCat, and InfluTo) is sent over secure, encrypted connections (HTTPS).

## 5. Data Retention and Deletion

- **Local Data:** You have complete control over your health data. You can delete all your personal information, food logs, and progress history at any time simply by deleting the BioWise app from your device.
- **AI Service Data:** Daily usage counts and IP-based counters are deleted after 35 days, Premium status copies after 1 day, and technical logs after 7 days. The record that your free AI scan was used is kept so the free scan cannot be repeated. To have this data deleted, contact us at the address below.
- **Subscription Data:** Financial and subscription records managed by Apple, Google, and RevenueCat are retained in accordance with their respective privacy policies and legal tax requirements.

## 6. Children's Privacy

BioWise is not intended for use by individuals under the age of 13 (or 16 in certain European jurisdictions). We do not knowingly collect personal information from children. If you are a parent or guardian and believe your child has provided us with personal information, please contact us so we can guide you on how to delete the local app data.

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices or technologies. We will notify you of any material changes by updating the "Effective Date" at the top of this policy and, where required, presenting you with a notice within the App.

## 8. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Webomax Bilişim Teknolojileri Limited Şirketi**

Email: info@webomax.net
