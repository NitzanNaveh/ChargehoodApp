# 🚗 Chargehood - Electric Vehicle Charging App

Welcome to **Chargehood**, an app for managing electric vehicle charging stations!  
Find charging stations, start a charging session, and track your booking history.

![Chargehood Logo](https://imgur.com/a/s6ny3JF)


---

## 📌 Key Features

**🔍 Find Charging Stations** - View all stations on an interactive map.  
**⚡ Manage Your Stations** - Add, edit, and delete your own charging stations.  
**🛠 Start a Charging Session** - Charge your car at supported stations.  
**💳 Booking History** - Track past charging sessions.  
**📜 Payment Management** - Save credit cards for quick payments.  
**🗺 Navigation Support** - Navigate to stations via Waze & Google Maps.  
**🔐 User Authentication** - Secure login with Firebase Authentication.

---


## 🛠 **Tech Stack**

🚀 **Kotlin** – Modern, safe, and concise programming language.  
📱 **Jetpack Compose & XML** – Hybrid UI development for a seamless user experience.  
🗄 **Room Database** – Local storage solution for offline support.  
🔥 **Firebase Firestore** – Real-time cloud database for user and station data.  
🔑 **Firebase Authentication** – Secure user authentication (email/password, Google login).  
🗺 **Google Maps API & FusedLocationProvider** – Location tracking and navigation support.  
⚙ **Custom Dependency Management** – Implemented via **MyApplication** for global variables.  
🎯 **Jetpack Navigation Component (NavGraph)** – Ensures smooth and structured in-app navigation.  
☁ **Cloudinary API** – Image uploads for charging station photos.   
📂 **Single-Activity Architecture** – The app is built with a single MainActivity and multiple Fragments.
🔄 **LiveData & ViewModel** – Ensures reactive UI updates and separation of concerns.

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/chargehoodapp.git
cd chargehood
```
### 2️⃣ Open in Android Studio
Ensure you have Android Studio Giraffe (or newer).

Select Open an Existing Project and navigate to the project folder.

### 3️⃣ Set Up Firebase
Create a new project on Firebase Console.

Download google-services.json and place it inside app/ .

### 4️⃣ API Keys Configuration
Add your API keys in local.properties:
```sh
MAPS_API_KEY=your_google_maps_key
```
Add your API keys in gradle.properties:
```sh
CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_name
API_SECRET=your_cloudinary_api_secret
GOOGLE_MAPS_API_KEY=your_google_maps_key
```
### 5️⃣ Run the App
In Android Studio:

Connect a physical device or use an emulator.

Click ▶️ Run to start the app.

---
## 📸 Screenshots
Home Screen	Interactive Map	Manage Stations

---
## 🏛️ Project Architecture
This project follows MVVM (Model-View-ViewModel) principles with NavGraph for navigation.

```sh
📂 app/
 ├── 📂 base/               # Global configurations (MyApplication), Constants 
 ├── 📂 data/               # Data layer - Repositories, Models, Room DB, Firebase, Cloudinary
 ├── 📂 presentation/       # UI - Fragments, Activities, ViewModels
 ├── 📂 utils/              # Helper classes and global utilities
```
---
## 👨‍💻 Contributing
💡 Have an idea for improvement? Open an Issue or submit a Pull Request.

🛠️ Found a bug? Report it in GitHub Issues.

⭐ Enjoyed the project? Leave a star (⭐) to support us!

---
## 📜 License
MIT License

Copyright © 2025 Ofek Amirav.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[...]

