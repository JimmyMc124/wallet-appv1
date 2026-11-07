# Wallet

A private wallet app for the cards you carry: credit, debit, ID, licence, insurance and membership cards. Everything stays on your device. There is no account and no server.

![Wallet banner](wallet-banner-1024x500.png)

## Features

- **Card pile:** cards stack like a real wallet. Tap one to bring it forward, hold and drag to reorder.
- **Four card types plus Other:** credit, debit, identity, licence and a flexible type for insurance, membership and more.
- **Smart entry:** card numbers are checked and the network (Visa, Mastercard, Amex and others) is detected. Dates format themselves.
- **App lock:** opens with your phone's fingerprint, face or screen lock.
- **Private by design:** only the last four digits of a number are stored, the security code is never asked for, and saved cards are encrypted.
- **Built-in guidance:** every field explains what to enter.

## Status

This is a prototype. Please do not use it with real card details yet.

- The app cannot make payments. The tap-to-pay screen detects NFC only; real contactless payments need a native app approved by banks and card networks.
- Camera text scanning works only in some browsers and is not available inside the app yet.

## Run it

Open `www/index.html` in a browser, or build the mobile app with Capacitor:

```
npm install
npx cap add android
npm run icons
npx cap sync android
npx cap open android
```

A GitHub Actions workflow in `.github/workflows` also builds an Android APK for you.

## Licence

Copyright (c) 2026 <your name>. All rights reserved.

The source is public for viewing only. You may not use, copy, modify, distribute or sell this code without written permission.
