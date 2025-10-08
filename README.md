
 📘 README.md — *LearnSmart: E-Learning App*

 🧩 Project Vision

**LearnSmart** is a mobile e-learning application built using **Flutter**.
It enables learners to explore, enroll, and track various learning programs.
Admins can create and manage courses, view learners’ progress, and update content seamlessly.

The goal of LearnSmart is to provide a **simple, intuitive, and accessible platform** for both learners and admins to interact efficiently.

---

 🎯 Objectives

* Provide a smooth learning experience through mobile.
* Allow admins to manage learning programs dynamically.
* Make learning accessible offline and mobile-friendly.
* Build using Flutter for cross-platform compatibility (Android/iOS/Web).

---

 👥 Target Users

 1. Learners:

* Can register, log in, and browse available programs.
* View program details, enroll, and track progress.

 2. Admins:

* Can log in with admin credentials.
* Create, edit, or delete programs.
* View and manage enrolled learners.

---

 ⚙️ Key Features (Planned)

* 🔐 User Authentication (Login/Signup)
* 🏠 Home Page showing programs and recommendations
* 📚 Program Listing & Details
* ✅ Enrollment functionality
* 👤 Profile Page for learners
* 🧑‍💼 Admin Dashboard for content management
* 🔔 Notifications and updates

---

 🧭 Navigation Flow

**Learner Flow:**
`Splash → Login → Home → Program List → Program Details → Profile`

**Admin Flow:**
`Splash → Admin Login → Dashboard → Manage Programs → View Learners`

---

 🧑‍💻 Tech Stack

* **Flutter** – Frontend framework
* **Dart** – Programming language
* **Firebase (optional)** – Authentication & backend
* **GitHub** – Version control

---

 🗂️ Folder Structure (Initial)

```
lib/
 ├── main.dart
 ├── screens/
 │    ├── login_screen.dart
 │    ├── home_screen.dart
 │    ├── program_list_screen.dart
 │    ├── program_detail_screen.dart
 │    └── profile_screen.dart
 ├── widgets/
 └── models/
assets/
pubspec.yaml
README.md
```

---

 🚀 Setup Instructions

1. Clone the repository

   ```bash
   git clone https://github.com/sabzgunbad3/Weak1-LearnSmart.git
   cd learnsmart
   ```
2. Install dependencies

   ```bash
   flutter pub get
   ```
3. Run the app

   ```bash
   flutter run -d chrome
   ```

---

 🧾 Version Control

* Initial project setup committed to GitHub.
* All new updates pushed with descriptive commit messages.

---

 🏁 Current Status

✅ Week 1: App proposal, wireframes, and GitHub setup completed.
🔜 Week 2: UI screen development begins.

---
