# 🌾 Gluten Free App

A Flutter mobile application designed to help **Celiac disease** patients identify gluten-free products by scanning barcodes — and explore trusted stores, doctors, and recipes dedicated to gluten-free living.

---

## 📱 Overview

**Gluten Free App** makes living gluten-free safer and easier.  
Users can scan product barcodes, browse gluten-free recipes, and discover doctors and stores that specialize in gluten-free products.

---

## 🚀 Main Features

| Feature | Description |
|----------|--------------|
| 🔍 **Barcode Scanner** | Scan product barcodes and check gluten-free status via API. |
| 🧾 **History Page** | Keeps a list of all previously scanned products. |
| 🏪 **Stores Page** | Shows verified gluten-free stores and user-suggested ones. |
| 🧑‍⚕️ **Doctors Page** | Lists verified specialists with community suggestions. |
| 🍽️ **Recipes Page** | Explore and suggest gluten-free recipes. |
| 🌓 **Dark / Light Mode** | Supports theme switching with persistence. |
| 🌍 **Multi-language Support** | Arabic 🇩🇿 and English 🇬🇧 — auto-detected from system. |
| 🧠 **Admin Validation Flow** | All user submissions are reviewed before publication. |
| 💰 **AdMob Integration** | Banner + Interstitial + Rewarded ads for monetization. |

---

## 🧩 Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | Flutter (Dart) |
| **State Management** | Riverpod |
| **Backend** | Firebase Firestore + Storage + Node.js |
| **Auth** | Firebase Authentication |
| **API** | Custom Barcode API |
| **Routing** | GoRouter |
| **Localization** | flutter_translate (en/ar JSON) |
| **Theming** | Riverpod + SharedPreferences |
| **Analytics** | Firebase Analytics |

---

## 🧱 App Architecture


lib/
├─ main.dart
├─ router.dart
├─ providers.dart
├─ models/
├─ pages/
├─ services/
├─ widgets/
└─ assets/i18n/
├─ en.json
└─ ar.json

---

## 🔐 Admin Approval Flow

1. User adds a new store / recipe / doctor.  
2. Data saved in `pending_submissions/` with `approved: false`.  
3. Admin reviews and approves.  
4. Once approved → moved to main collection and visible to all users.

---

## 🎨 Design & Experience

- Clean, minimal UI  
- Arabic RTL support  
- Adaptive light/dark colors  
- Simple navigation with GoRouter  

📷 **Screenshots (example):

![1st](https://github.com/user-attachments/assets/0951ca84-6dfc-4957-807a-3027eae1b135)
![2nd](https://github.com/user-attachments/assets/579eb786-fa87-4933-928c-c42003d9be9b)
![3rd](https://github.com/user-attachments/assets/43b69ce9-08a4-45a2-884f-a1831fc21c4a)
![4th](https://github.com/user-attachments/assets/608e84dd-a122-404b-89be-1826474badfe)
![5th](https://github.com/user-attachments/assets/a6b0e061-9dfa-46b4-9c45-226a1512c70f)
![6th](https://github.com/user-attachments/assets/cc4a8b9b-005b-49bc-83cc-1be1271d6b9e)


🧠 Author
👩‍💻 Chaima Belkhattab
📍 Algiers, Algeria
💬 Flutter Mobile Developer | Android & iOS
📧 chaimabelkhattabe@gmail.com
