# 🏥 Doctor Appointment Android App

A modern Doctor Appointment Android app built with **Java**, **Firebase Realtime Database**, and **Android Material Design**. This app features a clean dashboard, doctor categorization, top doctor listing, and detailed appointment booking functionality.

---

## ✨ Features

- ⚡ **Splash Screen** with branding
- 🧭 **Intro Activity** for first-time users
- 🏠 **Modern Material Dashboard**
- 🗂️ **Doctor Categories** (e.g., Cardiologist, Dentist, etc.)
- 👨‍⚕️ **Top Doctors List**
- 📋 **Detailed Doctor View & Booking Page**
- 🔄 **Firebase Integration** for real-time doctor data
- ✅ **Booking Confirmation and Details View**

---

## 🛠️ Tech Stack

- **Language**: Java
- **IDE**: Android Studio
- **Database**: Firebase Realtime Database
- **UI/UX**: Android Material Design Components

---

## 📱 Screens / UI Structure

1. **SplashActivity.java**
   - App logo display
   - Navigates to Intro or Dashboard based on user status

2. **IntroActivity.java**
   - Onboarding experience (can be skipped after first launch)

3. **DashboardActivity.java**
   - Home screen with categories and top doctors
   - Navigation to Category or Detail screens

4. **CategoryListActivity.java**
   - Shows list of doctors by category from Firebase

5. **TopDoctorsAdapter.java**
   - RecyclerView for top-rated doctors

6. **DoctorDetailActivity.java**
   - Shows complete profile of selected doctor
   - Appointment booking UI


---

## 🔌 Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new Firebase project
3. Add Android app package name
4. Download `google-services.json` and place it in `/app` directory
5. Enable Firebase Realtime Database and set rules
6. Add doctor data under a node like `/doctors/doctor_id/...`

---

## ✅ Prerequisites

- Android Studio (Arctic Fox or newer)
- Java 8+
- Firebase Project Setup
- Internet Connection

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/doctor-appointment-app.git



