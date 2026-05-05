# HopeConnect: Finding Missing Peoples 🛡️ 🇮🇳
**AI-Powered Social Impact Platform for Locating Missing Persons**

> "Every year, over 100,000+ people go missing in India. HopeConnect is built to ensure that no family has to wait in silence during those critical first 72 hours."

HopeConnect is a high-performance Android application designed to centralize and accelerate missing person investigations. By combining **on-device AI (Face Recognition)** with community-driven reporting, it transforms the search process from a manual effort into a smart, collaborative network.

---

## 🚀 Experience the App
The source code is currently private to protect proprietary AI logic and security configurations. However, the application is available for testing and review:

[**📥 Download HopeConnect APK (v1.0.0)**](https://github.com/Ritesh-Shinde45/HopeConnect-App/releases/tag/v1.0.1)

[**📥 Source Code**](https://github.com/Ritesh-Shinde45/HopeConnect.git)

*Note: Optimized for Android devices.*

---

## ✨ Key Features & Innovation

### 🤖 AI-Powered Face Matching
- Uses **MobileFaceNet via TensorFlow Lite** for on-device facial recognition
- Automatically scans the database to surface potential matches
- No internet required for face comparison — fully on-device
 
### 📋 Smart Reporting & GPS Integration
- File detailed reports with photos, real-time GPS coordinates, age, gender, last seen location
- Reports go through admin verification before going live
 
### 💬 Witness Collaboration Hub
- Secure built-in chat for volunteers and families
- Personal phone numbers stay hidden for privacy
 
### 🛡️ Admin Moderation Panel
- Full admin dashboard to review and verify reports before publishing
- Prevents spam and false entries from polluting the database
 
### 🔔 Smart Notifications
- Case match alerts, new report updates, admin announcements
 
### 🏆 Achievement System
- Volunteers earn recognition for verified leads and community contributions

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
 
## 🚀 Roadmap

```text
Phase 1 — Cloud Migration (Appwrite → AWS)
│
├── Migrate database → AWS DynamoDB
├── Move file storage → AWS S3
└── Implement authentication → AWS Cognito

Phase 2 — Cloud-Based AI Processing
│
├── Shift face recognition → AWS Lambda + Rekognition
├── Build REST APIs → AWS API Gateway
└── Deploy backend services → AWS EC2 / ECS

Phase 3 — Scale & Expansion
│
├── Web dashboard for authorities → AWS Amplify
├── Real-time alerts → AWS SNS
├── Multilingual support (Marathi, Hindi)
└── NGO & system integration
```
---

## 👨‍💻 Developer

**Ritesh Shinde**
*IT Diploma Student | Cloud Security Learner*

I am passionate about building secure and reliable technology solutions, with a strong interest in cloud security and modern infrastructure.

**Kishan Alladwar**
*IT Diploma Student | Data Science Learner*

Special thanks to **Kishan Alladwar** for his support throughout this journey. 🤝


[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ritesh--shinde/)
[![github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ritesh-Shinde45)

---
*This repository contains documentation and releases only. The core source code is hosted privately.*
