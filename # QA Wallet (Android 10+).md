# QA Wallet (Android 10+)

Dark-mode wallet for **QA test cards** with PIN/fingerprint lock and **NFC sandbox emulation**.

## Features

- Dark mode UI
- PIN & fingerprint app lock
- Preloaded dummy cards (TEST ONLY) + add your own
- Mask/unmask details
- NFC HCE sandbox (sends card number bytes as demo)
- Offline local storage

## Preloaded Cards (TEST ONLY)

- Visa 4111111111111111
- Mastercard 5555555555554444
- Amex 378282246310005
- Google Pay Sandbox 4242424242424242
- Alipay 6200000000000005

## Build via GitHub Actions

Add repo **Secrets**: SIGNING_KEY (base64 keystore), KEY_ALIAS, KEY_STORE_PASSWORD, KEY_PASSWORD.
Run **Actions Build QA Wallet APK** and download artifact.
