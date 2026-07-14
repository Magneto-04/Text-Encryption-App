# Text Encryption App (Android)

An Android app that encrypts and decrypts text messages entered by the user — built to demonstrate practical application of cryptography in a mobile context, letting users protect sensitive text before sharing or storing it.

## What it does
- Takes plain text input from the user
- Encrypts it using cryptographic algorithm with a user-provided key/password
- Displays the encrypted (ciphertext) output, which can be copied/shared
- Decrypts ciphertext back to the original message when given the correct key/password

## Tech stack
- **Platform:** Android
- **Language:** Java (Android SDK)
- **Core concept:** Cryptography (symmetric/asymmetric encryption)

## How it works
1. User enters plain text into the input field
2. User enters/sets an encryption key or password
3. App encrypts the text using [algorithm] and displays the ciphertext
4. To decrypt, the user pastes ciphertext and enters the correct key — app returns the original message

## How to run
```bash
# Clone the repo
git clone https://github.com/Magneto-04/Text-Encryption-App.git

# Open in Android Studio
# File > Open > select the project folder

# Build and run
# Connect an Android device or start an emulator, then click Run
```
