# RestroManager 🍽️

A Flutter-based Restaurant Management System with waiter ordering, kitchen display system, billing, Firebase authentication, realtime Firestore integration, and multi-device waiter management.

---

# Features 🚀

## Manager Panel
- Manager Login & Registration
- Restaurant Profile Management
- Add/Edit/Delete Menu Items
- Add/Remove Tables
- Manage Waiters
- View Billing History
- Kitchen Display Monitoring

## Waiter Panel
- Waiter Login
- Device-based Authentication
- Take Customer Orders
- Add Kitchen Notes
- Checkout System
- Realtime Order Updates

## Kitchen Display System (KDS)
- Live Incoming Orders
- Order Status Tracking
- Queued → Preparing → Ready → Done

## Billing System
- Table-wise Billing
- Order History
- Realtime Bill Calculation

## Firebase Integration
- Firebase Authentication
- Cloud Firestore
- Offline Persistence
- Firebase Cloud Messaging (FCM)

---

# Tech Stack 🛠️

- Flutter
- Dart
- Firebase Auth
- Cloud Firestore
- Firebase Messaging
- Riverpod
- Google Fonts

---

# Project Structure 📂

```text
lib/
├── models/
├── screens/
├── services/
├── widgets/
├── firebase_options.dart
└── main.dart
```

---

# APK Download 📱

[⬇ Download RestroManager APK](https://drive.google.com/file/d/1qJo7oLJ86iS36D3dBD9ABCtBkMowYxkR/view?usp=drive_link)

---

# Installation ⚙️

## Clone Repository

```bash
git clone https://github.com/rohanmashere2/restaurant-management-system.git
```

## Install Dependencies

```bash
flutter pub get
```

## Run Project

```bash
flutter run
```

---

# Build APK 📦

```bash
flutter build apk --release
```

APK location:

```text
build/app/outputs/flutter-apk/app-release.apk
```

---

# Firebase Setup 🔥

1. Create Firebase Project
2. Add Android App
3. Download `google-services.json`
4. Place inside:

```text
android/app/
```

5. Run:

```bash
flutterfire configure
```

---

# Future Improvements 💡

- PDF Invoice Generation
- Thermal Printer Support
- QR Table Ordering
- Inventory Management
- Analytics Dashboard
- Online Payments

---

# Developer 👨‍💻

Rohan Mashere

GitHub:
https://github.com/rohanmashere2

---

# License 📄

This project is licensed under the MIT License.

MIT License

