# Privacy Policy for GPS Logger Pro

**Effective Date:** November 7, 2026  
**Last Updated:** November 7, 2026  
**Developer:** PinangTech  
**Application:** GPS Logger Pro (`com.aistudio.gpslogger.pkxvmt`)  
**Contact:** boonpin1975@gmail.com  

---

## 1. Overview
PinangTech ("we", "us", or "our") built **GPS Logger Pro** as an ad-supported application. This SERVICE is provided by PinangTech and is intended for use as is. This page informs users regarding our policies with the collection, use, and disclosure of Personal Information if anyone decides to use our Service.

By using GPS Logger Pro, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information Collection and Use

### A. Location Data (Foreground & Background)
- **What is collected:** Precise geographic location (GPS latitude, longitude, altitude, speed, bearing, and GNSS satellite telemetry).
- **Purpose:** Location data is collected solely to record travel routes, calculate movement statistics (speed, elevation, distance), display live maps, and alert you of overspeed conditions.
- **Background Location:** When you start tracking, the app utilizes a Foreground Service with background location permission (`ACCESS_BACKGROUND_LOCATION`) to maintain continuous recording while the app is in the background or when your screen is locked.
- **Storage:** All recorded GPS coordinates and waypoints remain **100% stored on your local device** in an encrypted/local SQLite database. We do **not** transmit, sell, or sync your routes to our own servers.

### B. Audio / Microphone (Voice Commands)
- **What is used:** The microphone permission (`RECORD_AUDIO`) is used exclusively for on-device, offline local voice recognition commands (e.g., "start tracking", "stop tracking", "exit").
- **Storage:** Audio data is processed in real time and is **never recorded, stored, or sent to external cloud servers**.

### C. Bluetooth & Power Automation
- **What is used:** Bluetooth connection status is accessed locally to detect when your device connects to or disconnects from your vehicle or headset to automatically start or stop tracking.
- **Storage:** Bluetooth identifiers are stored strictly on your local device preferences.

### D. User-Initiated Data Export & Cloud Backup
- Exported files (GPX, KML, KMZ, GeoJSON, CSV, NMEA) are generated locally on your device.
- Google Drive cloud backup is strictly optional and only triggered when you authenticate with your Google account to back up route files to your personal Google Drive folder.

---

## 3. Third-Party Services & Advertising

This application integrates third-party services that may collect information used to identify you or your device:

### Google Mobile Ads (AdMob)
- We display advertisements provided by Google AdMob.
- Google AdMob may collect and process device identifiers (such as Google Advertising ID), IP address, and app usage data to serve relevant or non-personalized advertisements and perform analytics.
- For more information, please review Google's Privacy Policy:
  - [Google Privacy & Terms](https://policies.google.com/privacy)
  - [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

---

## 4. Data Retention and Security
- Your recorded trip data is stored locally on your device. You can permanently delete any track, clear tile caches, or wipe app data at any time from within the app settings.
- We implement commercially acceptable administrative and technical measures to protect the security of your information. However, no method of transmission over the internet or electronic storage is 100% secure.

---

## 5. Children's Privacy
GPS Logger Pro does not address anyone under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If you are a parent or guardian and become aware that your child has provided us with personal information, please contact us so that we can take necessary actions.

---

## 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. You are advised to review this page periodically for any changes. Any updates are effective immediately upon posting on this page.

---

## 7. Contact Us
If you have any questions, suggestions, or concerns regarding this Privacy Policy, please contact us at:

- **Developer:** PinangTech
- **Email:** boonpin1975@gmail.com
- **Repository:** https://github.com/boonpin1975/policy
