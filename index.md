# Privacy Policy for FoundryWear

**Last updated: February 26, 2026**

FoundryWear ("the App") is a Wear OS application developed by Arcascope for
research-grade accelerometer data collection. This policy explains what data
the App collects, how it is used, and your rights regarding that data.

---

## 1. Data We Collect

### Sensor Data
The App records **accelerometer data** (movement on X, Y, Z axes) from your
smartwatch at a user-configurable rate (default: 50 Hz). This data is stored
locally on your device and, when you choose to upload, sent to secure cloud
storage.

### Battery Data
The App periodically records your device's battery percentage alongside sensor
sessions to help interpret recording quality.

### Device Information
The App collects the following device-level information:
- A randomly generated **device UUID** (created on first launch, not linked to
  your identity, phone number, or any account)
- Device model and manufacturer (e.g., "Samsung Galaxy Watch")
- Android OS version
- Accelerometer sensor name, vendor, and hardware specifications

### What We Do Not Collect
- Location data
- Personal identity (name, email, phone number)
- Contacts, messages, or call logs
- Camera or microphone data
- IMEI, Android ID, or any hardware-level device identifiers

---

## 2. How Data Is Used

Collected sensor data is used solely for **research purposes** by Arcascope.
Specifically:
- To study movement patterns and develop circadian rhythm analysis tools
- Data is associated with your device UUID only, not with any personal identity

---

## 3. Data Storage and Transfer

### Local Storage
Data is written to your device's external app storage directory:
`/sdcard/Android/data/com.arcascope.foundrywear/files/`

### Cloud Upload
When you initiate an upload (or enable automatic upload on charging), your
session files are uploaded over **WiFi only** to **Google Firebase Storage**,
organized under your device UUID. 

Firebase Storage is governed by Google's security and privacy standards.
See [Google's Privacy Policy](https://policies.google.com/privacy).

### Anonymous Authentication
The App uses **Firebase Anonymous Authentication** to securely access cloud
storage. This creates no user account and is not linked to any identity.

---

## 4. Data Sharing

We do **not** sell, trade, or share your data with third parties. Data may
only be accessed by Arcascope research staff.

---

## 5. Data Retention

Session data is retained in cloud storage for as long as needed for the
research study you are participating in. You may request deletion at any
time (see Section 7).

---

## 6. Analytics and Crash Reporting

The App does **not** use analytics services, third-party crash reporting, or
advertising SDKs.

---

## 7. Your Rights

You may request:
- A copy of all data associated with your device UUID
- Deletion of all data associated with your device UUID

To make a request, contact us at **[franco@arcascope.com]** with the
subject line "FoundryWear Data Request" and include your device UUID (visible
in the App's settings screen).

---

## 8. Children's Privacy

The App is not intended for use by children under 18. We do not knowingly
collect data from children.

---

## 9. Changes to This Policy

We may update this policy as the App evolves. The "Last updated" date at the
top of this page will reflect any changes. Continued use of the App after
changes constitutes acceptance of the updated policy.

---

## 10. Contact

For privacy questions or data requests:

**Arcascope**
Email: [franco@arcascope.com]
Website: [https://arcascope.com](https://arcascope.com)
