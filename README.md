<div align="center">

# 🎓 AMU BATCH X

### The Official Student Academic Companion App for Department of Computer Science
**Aligarh Muslim University (AMU) · MCA Batch 2026–2028**

[![Website](https://img.shields.io/badge/Official%20Website-amubatchx.app-166534?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.amubatchx.app)
[![Download APK](https://img.shields.io/badge/Download-Android%20APK%20(v1.0.8)-22c55e?style=for-the-badge&logo=android&logoColor=white)](https://www.amubatchx.app/download)
[![Direct Download](https://img.shields.io/badge/Direct%20CDN-Download%20Binary-0f172a?style=for-the-badge&logo=cloud-download&logoColor=white)](https://www.amubatchx.app/api/download)

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%208.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/iOS-In%20Development-lightgrey?style=flat-square&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Version-v1.0.8%20Stable-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Backend-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Push%20Alerts-Firebase%20FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Offline-SQLite%20Cache-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-gray?style=flat-square" />
</p>

</div>

---

## 📥 Direct Downloads & Web Platform

Get the latest Android release directly through the official website distribution engine or via GitHub:

| Channel | Destination | Details |
| :--- | :--- | :--- |
| 🌐 **Official Website Hub** | [**amubatchx.app/download**](https://www.amubatchx.app/download) | Interactive installation hub, verified builds & release notes |
| ⚡ **Direct APK Download** | [**amubatchx.app/api/download**](https://www.amubatchx.app/api/download) | Instant redirect to the latest verified APK binary |
| 📦 **GitHub Release** | [**Batch-X Releases (v1.0.8)**](https://github.com/sameerahmad005/Batch-X/releases/tag/v1.0.8) | Official GitHub release artifacts & assets |
| 📱 **Direct APK File** | [**Download v1.0.8.apk**](https://github.com/sameerahmad005/Batch-26/releases/download/v1.0.8/v1.0.8.apk) | Direct package build (~24.2 MB) |

> ℹ️ **iOS Users:** The native iOS edition for iPhone and iPad is currently in active development. Check [amubatchx.app/download](https://www.amubatchx.app/download) for updates.

---

## 📖 About AMU BATCH X

**AMU BATCH X** is a high-performance, offline-first digital academic companion platform engineered specifically for students in the **Department of Computer Science at Aligarh Muslim University (AMU)**, targeted for the **MCA 2026–2028 batch**.

It solves everyday academic friction: tracking attendance against the university's mandatory **75% minimum attendance rule**, viewing daily lecture timetables mapped to specific halls (**CS-01 to CS-04, Unix Lab 2, and Systems Labs**), receiving departmental circulars in real-time, accessing curated study notes, and managing previous-year question archives.

---

## 🌟 Core Features & Modules

### 1. 📊 Smart Attendance Ledger
- **AMU 75% Rule Cutoff Indicator**: Displays safe bunker margins and how many classes you must attend to stay above the 75% examination eligibility threshold.
- Separate ledgers for **Theory** and **Laboratory** courses.
- Historical attendance records with local SQLite persistence.

### 2. 📅 Room-Mapped Dynamic Timetable
- Day-wise and semester-wise lecture schedules.
- Exact department room locations (**CS-01, CS-02, CS-03, CS-04, Lab 1, Unix Lab 2**).
- Real-time indicator for ongoing, upcoming, and completed classes.
- Automatic holiday and vacation scheduling.

### 3. 🔔 Priority Circulars & Instant Push Notifications
- Sub-5-second push delivery for critical department circulars via **Firebase Cloud Messaging (FCM)**.
- Automated 5-minute pre-lecture reminders so you never miss a class.
- Exam schedule alerts, hall ticket notifications, and practical exam postings.

### 4. 📝 Crowdsourced Class Rescheduling
- Peer-reported class cancellations, delays, and room changes.
- Community voting verification to confirm changes before updating the schedule.
- Instant alert to batchmates when a class status changes.

### 5. 📚 Study Vault & Question Archives
- Curated MCA course notes, syllabus breakdowns, and lab manuals.
- Previous-year examination questions (PYQs) and model test papers.
- Fast offline access to downloaded study documents.

### 6. 🌐 Offline-First Architecture
- Full offline capability: Timetable, notes, and attendance remain fully accessible when campus Wi-Fi or cellular networks drop.
- Seamless background synchronization with **Supabase** once internet connectivity is restored.

---

## 🛠️ Technology Stack

| Layer | Technologies |
| :--- | :--- |
| **Mobile Runtime** | React 19, TypeScript, Vite, Capacitor 7 |
| **Styling** | Tailwind CSS v4, Modern OLED Dark & Light themes |
| **Backend & Database** | Supabase (PostgreSQL, Row Level Security, Storage Buckets) |
| **Cloud Storage** | Supabase Object Storage (`app-releases` CDN) |
| **Push Infrastructure** | Firebase Cloud Messaging (FCM) & Capacitor Local Notifications |
| **Web Distribution** | Next.js 16, Turbopack, Tailwind CSS, Vercel Edge Network |

---

## 📱 Installation Instructions

1. **Download the APK**:
   Tap [Download App](https://www.amubatchx.app/download) or use the [Direct Download Link](https://www.amubatchx.app/api/download).
2. **Allow Installation**:
   If prompted by Android, tap **Settings** and enable **Allow from this source** for Chrome or your browser.
3. **Install & Launch**:
   Open the downloaded `v1.0.8.apk` file and tap **Install**.
4. **Sign In**:
   Log in with your student credentials or enrollment identifier to activate your personalized timetable and attendance ledger.

---

## 📋 System Requirements

- **Operating System**: Android 8.0 (Oreo / API Level 26) or newer
- **Architecture**: Universal (ARM64-v8a, ARMv7a, x86_64)
- **App Size**: ~24.2 MB
- **Permissions**: Notifications (optional for lecture reminders), Storage (for notes downloads)

---

## 👨‍💻 Engineering Team

AMU BATCH X is built and maintained by students from the Department of Computer Science, Aligarh Muslim University:

- **Sameer Ahmad** — *Lead Mobile Developer & Architecture*  
  GitHub: [@sameerahmad005](https://github.com/sameerahmad005) · LinkedIn: [sameer-abrar](https://linkedin.com/in/sameer-abrar) · Website: [sameerahmadansari.me](https://sameerahmadansari.me)
- **Ali Saqulain** — *Web Platform & UI Engineering*  
  GitHub: [@Alisaqulain](https://github.com/Alisaqulain) · LinkedIn: [ali-saqulain](https://www.linkedin.com/in/ali-saqulain-7404a8287)
- **Okash** — *Student Engineering Contributor*

---

## 📄 Disclaimer

**AMU BATCH X** is an independent student companion application created for the MCA community in the Department of Computer Science at Aligarh Muslim University. It is not an official university administration platform and is not operated by AMU administrative offices.

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

Built with ❤️ for **Department of Computer Science · Aligarh Muslim University**

</div>
