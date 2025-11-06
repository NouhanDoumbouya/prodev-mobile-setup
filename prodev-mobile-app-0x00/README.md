# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

# First Mobile App — Expo Router Setup

## 🎯 Objective

Set up and test the first mobile application using the **Expo Router template**, understand project scaffolding, and learn the file structure of a React Native app.

---

## 🧰 Steps Followed

1. **Navigated to Project Directory**

```bash
cd prodev-mobile-setup
```

2. **Created Expo Project**

```bash
npx create-expo-app@latest prodev-mobile-app-0x00/app-example
```

* Used default Expo Router (TypeScript) template.
* Project scaffolded into `app-example`.

3. **Modified Home Screen**

* Opened `app-example/app/(tabs)/index.tsx`.
* Replaced:

```tsx
<ThemedText type="title">Welcome!</ThemedText>
```

with:

```tsx
<ThemedText type="title">** First App Created**</ThemedText>
```

4. **Ran and Tested the App**

```bash
cd app-example
npx expo start
```

* Scanned QR code with Expo Go.
* Confirmed updated text appeared on device.

5. **Reset Project**

```bash
npm run reset-project
```

**Observations:**

* Cleared `.expo`, `.cache`, and other build artifacts.
* Source code remained intact.
* App rebuilt cleanly; faster subsequent builds.

---

## 🚀 Outcome

* Successfully created first Expo Router mobile app.
* Verified running on physical device.
* Learned file structure and reset workflow.

---

## 📁 Directory Structure

```
prodev-mobile-app-0x00/
 ├── README.md
 └── app-example/
      ├── app/
      │    ├── (tabs)/index.tsx
      │    └── _layout.tsx
      ├── constants/Colors.tsx
      ├── assets/
      ├── components/
      ├── hooks/
      ├── package.json
      ├── package-lock.json
      └── ...
```

## 👤 Author

**Nouhan Doumbouya**
Freelance Software Engineer | ALX Student | React Native Developer
[GitHub: nouhan-doumbouya](https://github.com/NouhanDoumbouya)
