# HopeConnect 🛡️ 🇮🇳
**AI-Powered Social Impact Platform for Locating Missing Persons**

> "Every year, over 100,000+ people go missing in India. HopeConnect is built to ensure that no family has to wait in silence during those critical first 72 hours."

HopeConnect is a high-performance Android application designed to centralize and accelerate missing person investigations. By combining **on-device AI (Face Recognition)** with community-driven reporting, it transforms the search process from a manual effort into a smart, collaborative network.

---

## 🚀 Experience the App
The source code is currently private to protect proprietary AI logic and security configurations. However, the application is available for testing and review:

[**📥 Download HopeConnect APK (v1.0.0)**](PE)

*Note: Optimized for Android devices. This build serves as a Final Year Diploma Project showcase.*

---

## ✨ Key Features & Innovation

### 🤖 **AI-Powered Face Matching**
HopeConnect features integrated **MobileFaceNet via TensorFlow Lite**, moving beyond simple text searches.
* **The Tech:** Performs high-speed on-device facial embedding comparisons.
* **The Result:** When a sighting is reported, the AI automatically scans the database to surface potential matches, significantly reducing search time.

### 📋 **Smart Reporting & GPS Integration**
Users can file detailed reports with high-resolution photos, real-time GPS coordinates, and biometric data (age, gender, last seen).

### 💬 **Witness Collaboration Hub**
A secure, built-in chat system allows volunteers to share leads with families directly—ensuring privacy by keeping personal phone numbers hidden.

### 🛡️ **Verified Moderation (Admin Panel)**
To prevent spam, a full admin dashboard was built to review and verify entries before they go live, maintaining the platform's integrity.

---

## 🔧 Engineering Challenges & Solutions

* **The Appwrite/Java Bridge:** Solved breaking compatibility issues between the latest Appwrite SDK and Java by engineering a **Kotlin-based service layer**. This allowed the existing Java codebase to utilize modern backend services seamlessly.
* **On-Device ML Optimization:** Integrated **MobileFaceNet** for its lightweight architecture, ensuring real-time facial matching without compromising mobile performance or battery life.
* **Data Integrity:** Developed a manual moderation workflow to filter false reports, ensuring the platform remains a reliable tool for authorities and families.

---

## ⚙️ Tech Stack
* **Mobile:** Android (Kotlin & Java), XML, Material Design 3
* **Backend:** Appwrite (Database & Storage)
* **AI/ML:** TensorFlow Lite, MobileFaceNet
* **Architecture:** Modular Clean Architecture

---

## 🌍 Roadmap
* **Gamification:** Rewarding volunteers with badges for verified leads.
* **Reward System:** Integrated platform for families to offer rewards for verified information.
* **Multilingual Support:** Adding Marathi and Hindi for pan-India reach.

---

## 👨‍💻 Developer

**Ritesh Shinde**
*IT Diploma Student | Cloud Security Enthusiast*

I am passionate about building secure and reliable technology solutions, with a strong interest in cloud security and modern infrastructure.

Special thanks to **Kishan Alladwar** for his support throughout this journey. 🤝


[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ritesh--shinde/)
[![github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ritesh-Shinde45)

---
*This repository contains documentation and releases only. The core source code is hosted privately.*
