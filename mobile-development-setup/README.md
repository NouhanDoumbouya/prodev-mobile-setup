# Mobile Development Setup — Expo Go Environment

## 🎯 Objective

This task is part of the **ProDev Mobile Development** module.
The goal is to **set up and test the mobile development environment** using **Expo Go**, ensuring smooth React Native app development and testing on physical devices.

---

## 🧰 Tools and Requirements

| Tool                 | Description                                  | Status       |
| -------------------- | -------------------------------------------- | ------------ |
| **Node.js (LTS)**    | JavaScript runtime environment               | ✅ Installed  |
| **npm**              | Node package manager (comes with Node.js)    | ✅ Installed  |
| **VS Code**          | Recommended IDE for React Native development | ✅ Installed  |
| **Operating System** | Ubuntu 22.04 (Linux)                         | ✅ Compatible |
| **Expo Go App**      | Runs React Native apps on a physical device  | ✅ Installed  |

---

## 📲 Setting Up Expo Go on Mobile

### Steps Followed

1. Visited the official [Expo Go page](https://expo.dev/go).
2. Installed **Expo Go** on my physical device:

   * **Android:** Downloaded via **Google Play Store**.
3. Opened the app and **signed in** using my Expo account.
4. Confirmed the app was ready to scan QR codes for projects.

---

## ⚙️ Setting Up Expo on My Computer

Expo recently introduced a new CLI that doesn’t require global installation.
Instead of using the legacy `expo-cli`, the new setup uses `npx`.

### Installation and Testing Steps

1. Verified Node.js and npm installation:

   ```bash
   node -v
   npm -v
   ```
2. Created a new Expo project:

   ```bash
   npx create-expo-app test-app
   ```
3. Navigated into the project:

   ```bash
   cd test-app
   ```
4. Started the local development server:

   ```bash
   npx expo start
   ```
5. A QR code appeared in the terminal and web dashboard.
6. Scanned the QR code using **Expo Go** on my Android device.
7. The default React Native welcome screen successfully loaded 🎉.

---

## 🧩 Challenges Faced & Solutions

| Challenge        | Description                                 | Solution                                                 |
| ---------------- | ------------------------------------------- | -------------------------------------------------------- |
| ⚠️ CLI Warning   | “Legacy expo-cli does not support Node +17” | Used the new `npx` workflow with `create-expo-app`       |
| 📶 Network Issue | Expo Go couldn’t connect initially          | Ensured both PC and mobile device were on the same Wi-Fi |
| 🕒 Slow Build    | First build took several minutes            | Cached dependencies improved speed later                 |

---

## 🚀 Outcome

* Successfully configured the **Expo Go** environment.
* Verified app builds and runs on a physical Android device.
* Environment is ready for future React Native and mobile development projects.

---

## 📁 Repository Structure

```
prodev-mobile-setup/
└── mobile-development-setup/
    └── README.md
```

---

## 👤 Author

**Nouhan Doumbouya**
Freelance Software Engineer | ALX Student | React Native Developer
[GitHub: nouhan-doumbouya](https://github.com/NouhanDoumbouya)
