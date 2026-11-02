---
title: Privacy Policy — VPN SharPei for Android
description: Privacy Policy for the VPN SharPei Android app (com.sharpei.vpn).
permalink: /privacy-android
---

# Privacy Policy — VPN SharPei for Android

**App:** VPN SharPei (package `com.sharpei.vpn`)
**Effective date:** November 3, 2026

This Privacy Policy explains what data the VPN SharPei Android app ("the App", "we", "us") collects, why, and with whom it is shared.

## Summary

- The App is a VPN client. **We do not log your browsing history, the sites you visit, DNS queries or the content of your traffic.**
- There are **no user accounts**. We do not ask for your name, email or phone number.
- The App uses **Google Firebase** (Analytics, Crashlytics, Cloud Messaging, Remote Config) and **Google Play** services (Billing, Play Integrity).
- Free users see ads served by **Yandex Mobile Ads**. Premium subscribers do not see ads.
- All data is transmitted over encrypted connections (HTTPS/TLS).

## Data we collect

### 1. Device identifier
To recognise your device on our VPN servers and keep your subscription, the App creates a pseudonymous device ID: a SHA-256 hash of the Android ID combined with the package name. The raw Android ID never leaves the device. It is sent to our server (tegadmin.org) together with your app version and Android version.

### 2. VPN connection
When you connect, the App downloads a server configuration from our server and routes your traffic through the selected VPN server. Our servers process your IP address and traffic only transiently to provide the connection. We do not store traffic content, visited domains or DNS queries. We may keep aggregated technical metrics (for example, server load) that do not identify you.

### 3. Purchases and subscriptions
Subscriptions are processed by **Google Play Billing**. We never receive your payment card details. The App sends the purchase token and product ID to our server, which verifies it with Google to activate Premium. We keep purchase status (product, expiry, renewal state) linked to your pseudonymous device ID.

### 4. Analytics, crash reports and notifications
- **Firebase Analytics** collects app interaction events (screens opened, connect/disconnect, purchase events), app instance ID, device model, OS version and coarse location derived from IP.
- **Firebase Crashlytics** collects crash reports and diagnostics (stack traces, device state at the time of the crash).
- **Firebase Cloud Messaging** uses a push token so we can send service notifications. The token is stored on our server with your device ID.
- **Firebase Remote Config** downloads app settings.
- **Play Integrity API** checks that the App is genuine. Google processes device integrity signals.

Google privacy policy: https://policies.google.com/privacy

### 5. Advertising (Yandex Mobile Ads)

Free users see ads from Yandex Mobile Ads (YANDEX LLC). To show and measure ads, the SDK may process your device's Advertising ID, IP address, coarse location derived from IP, device model, OS version and interactions with ads. You can reset or delete your Advertising ID or opt out of personalized ads in Android Settings → Privacy → Ads. Yandex privacy policy: https://yandex.com/legal/confidential/

### Public IP check
To show your current IP address, the App sends requests to public services (for example, ipify.org). These services see your IP address as part of a normal HTTP request.

## Summary table

| Data | Who receives it | Purpose | Shared with third parties |
|---|---|---|---|
| Pseudonymous device ID | Our server, Firebase | App functionality, anti-fraud, analytics | No (Google acts as a processor) |
| Purchase history | Google Play, our server | Activating subscriptions | No |
| App interactions | Firebase Analytics | Analytics | No |
| Crash logs, diagnostics | Firebase Crashlytics | Stability | No |
| Advertising ID, ad interactions | Yandex Mobile Ads | Showing and measuring ads | Yes (to Yandex) |

Advertising ID usage: Advertising (Yandex Mobile Ads) and analytics (Firebase).

## What we do not collect
Name, email, phone number, contacts, photos, files, precise location, SMS, call logs, browsing history, or the content of your VPN traffic.

## Permissions
- **VPN service** (`BIND_VPN_SERVICE`): to create the encrypted VPN tunnel. This is the core function of the App.
- **Notifications**: connection status and service notifications.
- **Internet / network state**: to connect and monitor connectivity.

## Retention and deletion
Subscription and device records are kept while you use the App and for up to 12 months after your last activity, then deleted. Firebase keeps analytics data for up to 14 months and crash reports for 90 days. To ask us to delete data linked to your device, email us at the address below. Uninstalling the App stops all data collection.

## Children
The App is not directed to children under 18 and we do not knowingly collect data from children.

## Your rights
Depending on your country (including GDPR in the EU and 152-FZ in Russia), you may have the right to access, correct or delete your data, or object to processing. Contact us to exercise these rights.

## Changes
We may update this policy. The effective date above shows the latest version.

## Contact
cinemaassist@gmail.com
