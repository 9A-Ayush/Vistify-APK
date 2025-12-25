# Visitify 🏢🔐📱  

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)  
![Flutter](https://img.shields.io/badge/Framework-Flutter-blue?style=for-the-badge&logo=flutter)  
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange?style=for-the-badge&logo=firebase)  
![PWA](https://img.shields.io/badge/Visitor-PWA-green?style=for-the-badge&logo=pwa)  
![Cloudinary](https://img.shields.io/badge/Media-Cloudinary-blue?style=for-the-badge&logo=cloudinary)  

---

## 📌 About Visitify

**Visitify** is a smart visitor and delivery management system designed to simplify and secure entry operations in societies, offices, hostels, and residential complexes.  
It replaces manual registers with a **QR-based, real-time approval system** connecting visitors, guards, residents, and admins on a single platform.

---

## ✨ Features

### 🧍 Visitor PWA (No Login Required)
- QR scan-based entry
- Live photo capture (camera only)
- Phone number validation (+91, 10 digits)
- Wing → Flat dropdown selection
- Real-time approval animation

### 🛡️ Guard Mobile App
- Scan visitor QR codes
- Add walk-in visitors
- View pre-logged visitors
- Receive instant notifications
- Entry & exit logging

### 🏠 Resident Mobile App
- Pre-log visitors & generate QR
- Approve or reject visitor requests
- Visitor history
- Real-time alerts

### 🧑‍💼 Admin Panel
- Manage societies, wings & flats
- Add/remove guards & residents
- Control QR settings
- View logs & activity history

### 🔔 Other Highlights
- Real-time notifications (FCM)
- Light & Dark mode support
- Fully responsive UI
- Secure cloud-based system

---

## 🔄 Visitor Entry Workflow

### Case 1: Resident Pre-Logs Visitor
1. Resident adds visitor
2. System generates QR code
3. Guard scans QR
4. Visitor auto-approved
5. Approved animation shown

### Case 2: Visitor Not Pre-Logged
1. Guard provides gate QR
2. Visitor scans → PWA opens
3. Visitor fills details + captures live photo
4. Resident receives approval request
5. Approval animation shown after approval

---

## 🚀 How to Run

### Flutter Apps (Guard & Resident)
```bash
git clone https://github.com/9A-Ayush/visitify.git
cd visitify
flutter pub get
flutter run
```
## 🌐 Visitor PWA

- Built using **HTML, CSS, JavaScript**
- Hosted on **Firebase Hosting**
- Accessed directly by **QR code scan**
- No authentication required for visitors

---

## 🧠 Tech Stack

### Frontend
- Flutter (Guard & Resident Apps)
- HTML, CSS, JavaScript (Visitor PWA)

### Backend & Cloud
- Firebase Authentication (Email/Password, Gmail Auth)
- Firebase Firestore
- Firebase Cloud Messaging (FCM)
- Firebase Hosting

### Media Storage
- Cloudinary (Live visitor images)

---

## 🔐 Authentication Rules

- Email + Password authentication
- Gmail (Google OAuth) login
- Email verification mandatory
- No OTP-based authentication
- Visitor PWA does not require login

---

## 📐 UI & Responsiveness

- Mobile-first design
- Media queries for all screen sizes
- Flutter `MediaQuery` & `LayoutBuilder`
- Consistent theme across all modules
- Smooth approval & rejection animations

---

## 🌐 Links & Profiles  

[![GitHub](https://img.shields.io/badge/GitHub-9A--Ayush-black?logo=github&style=for-the-badge)](https://github.com/9A-Ayush)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayush%20Kumar-blue?logo=linkedin&style=for-the-badge)](http://www.linkedin.com/in/ayush-kumar-849a1324b)  
[![Instagram](https://img.shields.io/badge/Instagram-%40ayush__ix__xi-pink?logo=instagram&style=for-the-badge)](https://www.instagram.com/ayush_ix_xi)  

---

## 📦 Main Repo

[![Main Repo](https://img.shields.io/badge/Related%20Repo-Visitify-#1871CD?style=for-the-badge&logo=github)](https://github.com/9A-Ayush/visitify-.git)  

---

## 👨‍💻 Author
**Ayush Kumar**  

[![GitHub followers](https://img.shields.io/github/followers/9A-Ayush?style=social)](https://github.com/9A-Ayush)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow-blue?logo=linkedin)](http://www.linkedin.com/in/ayush-kumar-849a1324b)  

---
## ☕ Support My Work  

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/9a.ayush)
 

---

🔥 **Visitify – Smart, Secure & Seamless Entry Management**  
_Code. Secure. Innovate._


   


