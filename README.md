#  Luminash

Luminash is a modern React Native mobile application built to deliver a seamless, fast, and intuitive user experience. It’s designed, developed, and deployed using **React Native**, **Gradle**, and **Android SDK** with full support for release builds.  


Luminash is AI application like Google gemini

---

## ⚙️ Tech Stack
- ⚛️ React Native 0.75+
- 🧱 Android Gradle Plugin 9+
- 🧰 Java / Kotlin (Native Modules)
- 🎨 Custom UI with React Native Components
- 🔐 Signed Build using Keystore
- 🚀 Deployed via ADB / Play Console

---

## 🏗️ Setup & Installation

2️⃣ Install dependencies

npm install


3️⃣ Start Metro Bundler

npm start

4️⃣ Run the app on Android

npm run android

If you face permission issues:

cd android && gradlew clean && cd ..

📱 Building for Release

Generate a signed APK:

cd android
gradlew assembleRelease

Find your APK here:

android/app/build/outputs/apk/release/app-release.apk

Install manually:

adb install android/app/build/outputs/apk/release/app-release.apk


🏪 Play Store Deployment
Generate a Play Store–ready bundle:

cd android
gradlew bundleRelease

💡 Features

Clean, minimal design

Fast startup & smooth performance

Optimized release configuration

Offline-ready

