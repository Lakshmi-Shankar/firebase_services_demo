## Firebase Services Demo (Flutter + Firestore)

### Overview

This project demonstrates basic Firebase integration in a Flutter application.
It connects to **Cloud Firestore** and allows basic data operations (e.g., adding and displaying tasks).

---

## Tech Stack

* Flutter
* Firebase Core
* Cloud Firestore
* FlutterFire CLI

---

## Prerequisites

* Flutter (stable channel)
* Node.js
* FlutterFire CLI
* Firebase project created in Firebase Console
* Brave or Chrome browser (for web testing)

---

## Setup Instructions

### 1. Install Dependencies

```bash
flutter pub get
```

### 2. Configure Firebase

```bash
flutterfire configure
```

Select:

* android
* ios
* macos
* web
* windows

(Note: Linux is not supported by Firebase plugins.)

---

### 3. Run the App (Web Recommended)

If using Brave:

```bash
export CHROME_EXECUTABLE=/usr/bin/brave-browser
flutter run -d chrome
```

The app will launch in Brave.

---

## Important Notes

* Firebase does **not** support native Linux desktop.
* Use **Web (Chrome/Brave)** or **Android emulator** for testing.
* If `flutter doctor` shows Android SDK missing, install Android Studio.

---

## Common Commands

Clean project:

```bash
flutter clean
```

Check issues:

```bash
flutter doctor
```

Run on web:

```bash
flutter run -d chrome
```

---

## Project Goal

Understood:

* Firebase initialization in Flutter
* Firestore integration
* Platform configuration using FlutterFire CLI
* Running Flutter web apps 

---
