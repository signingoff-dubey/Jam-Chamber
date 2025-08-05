# 🎧 Jam Chamber

Jam Chamber is a Flutter-powered companion app for Spotify Premium users that lets you share and join live Jam sessions from around the world. The app helps you create a collaborative listening experience by letting you easily generate, share, and explore Spotify Jam links.

---

## 📱 What is Jam Chamber?

**Jam Chamber** connects music lovers by providing a centralized space to:

- Detect when you're playing music on Spotify.
- Prompt you to create a Spotify Jam session.
- Allow manual sharing of Jam links or QR codes with the community.
- View and join active Jams from other users around the world.
- Remove Jams when users end them manually.

> ⚠️ Due to Spotify API limitations, automatic Jam creation and end-detection are **not possible**. Users must manually share or remove links.

---

## 🌟 Key Features

- 🔐 Login via Spotify Premium (OAuth2)
- 🎧 Prompt to start a Jam when a song is detected
- 📤 Manually share Jam links or QR codes to a global feed
- 🌍 Browse and join active Jam sessions
- ❌ Manually end and remove your own Jam links
- 🛠 Settings to manage notifications and preferences

---

## 🛠 Tech Stack

- **Flutter** – Cross-platform frontend
- **Spotify Web API** – Authentication + music playback detection
- **Firebase Firestore** – Real-time feed of shared Jam links
- **Firebase Auth** – Anonymous or Google login (optional)
- **Firebase Cloud Functions (optional)** – Cleanup and moderation
- **Firebase Cloud Messaging (optional)** – Notifications for trending Jams

---

## 🚧 Project Status

Jam Chamber is under active development. All UI screens are currently being prototyped, with basic Spotify integration and Firestore feed operational in development builds.

---

## 📸 Planned Screens

- 🔐 **Login Screen** – Authenticate using Spotify Premium
- 🏠 **Feed Screen** – Global list of shared Jam links (with join buttons)
- ➕ **Jam Share Screen** – Manually paste Jam URL or scan QR
- ⚙️ **Settings** – Notification preferences, manual/auto prompts

---

## 🔒 Limitations

- Spotify’s Web API does **not** allow:
  - Automatic Jam creation
  - Automatic Jam link extraction
  - Automatic detection of Jam end
- All Jam sharing and removal must be done manually by users
- Spotify Premium is **required** for most playback control features

---

## 📦 How to Use

1. Install the app on your Android device.
2. Log in using your Spotify Premium account.
3. When a track is playing, get a prompt to start a Jam.
4. Tap to open Spotify, create a Jam session.
5. Copy and paste the link (or scan a QR code) into Jam Chamber.
6. Explore other active Jam links and join any you like.

