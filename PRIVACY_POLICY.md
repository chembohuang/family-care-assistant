# Privacy Policy for Family Care Assistant

**Last updated: February 10, 2026**

Family Care Assistant ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how our mobile application (the "App") collects, uses, and discloses information, and what choices you have with respect to the information.

## 1. Information We Collect and Use

The App is designed to help children remotely assist their elderly parents with smartphone operations. To provide this functionality, the App requires certain sensitive permissions.

### 1.1 Accessibility Service API
**Usage:** The App uses the Accessibility Service API to allow a trusted remote user (the "Child" or "Helper") to perform gestures (such as taps, swipes, and back/home actions) on this device (the "Parent" or "Care Receiver" device).
**Data Collection:**
*   **We do NOT use the Accessibility Service to collect any personal or sensitive user data.**
*   The API is strictly used to receive control commands from the connected Child device and execute them locally.
*   We do not read, store, or transmit any text you type (such as passwords or credit card numbers) using this service.

### 1.2 Media Projection (Screen Recording)
**Usage:** The App uses the Media Projection API to capture the screen content of this device and stream it in real-time to the connected Child device.
**Data Collection:**
*   **Transient Transmission Only:** The screen content is transmitted in real-time to the connected Child device via our relay server.
*   **No Storage:** We do not record, save, or store any screen data on our servers or on the device. The data is transient and exists only for the duration of the active remote support session.
*   **Safety Restriction:** As per Android system security, sensitive screens (such as banking apps or password fields) protected by `FLAG_SECURE` will appear as black or blurred screens to the remote user. We do not and cannot bypass this restriction.

### 1.3 Device Information
We may collect minimal device information (such as device model and operating system version) solely for the purpose of establishing a stable connection and optimizing the video stream quality.

## 2. How Data is Transmitted

The App establishes a connection between the Parent device and the Child device using a relay server.
*   **Relay Only:** The server acts solely as a bridge to forward data packets (video stream and control commands) between the two devices.
*   **No Persistence:** The relay server does not store any video streams or control logs.

## 3. Data Sharing and Disclosure

We do not sell, trade, or otherwise transfer to outside parties your Personally Identifiable Information.
*   **Peer-to-Peer Nature:** The screen data is shared **only** with the specific Child device that enters the correct 6-digit connection code displayed on your screen. You have full control over who you share your screen with.
*   **Legal Requirements:** We may disclose information if required to do so by law or in the good faith belief that such action is necessary to comply with a legal obligation.

## 4. Security

We implement appropriate technical and organizational measures to protect the data transmitted through our App. However, please be aware that no method of transmission over the internet is 100% secure. We strive to use commercially acceptable means to protect your information but cannot guarantee its absolute security.

## 5. Children's Privacy

Although our App is a tool for family care, it is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13.

## 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page. You are advised to review this Privacy Policy periodically for any changes.

## 7. Contact Us

If you have any questions about this Privacy Policy, please contact us at:

**Developer:** Guoqin Huang
**Email:** chemboking@gmail.com
