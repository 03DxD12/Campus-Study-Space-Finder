# 🎓 Campus Study Space Finder
### *A Data-Driven UX Case Study on Solving Peak-Hour Overcrowding and Navigation Bottlenecks*

![UX Case Study](https://img.shields.io/badge/Course-ITST%20306%20--%20UX%2FUI%20Design-006B3C?style=for-the-badge)
![Institution](https://img.shields.io/badge/Institution-PLSP%20%2F%20DLSP-FFD700?style=for-the-badge&labelColor=000000)
![Status](https://img.shields.io/badge/Status-Completed%20%26%20Published-brightgreen?style=for-the-badge)
![SUS Score](https://img.shields.io/badge/SUS%20Score-87.5%2F100%20(Grade%20A)-1E90FF?style=for-the-badge)

---

## 📌 Project Overview & Metadata

* **Project Name:** DLSP / PLSP Campus Study Space Finder
* **Author:** Denmhar Suaze Dimaculangan
* **Course:** ITST 306 — UX/UI Design
* **Institution:** Pamantasan ng Lungsod ng San Pablo (PLSP) / De La Salle Philippines (DLSP)
* **GitHub Repository:** [https://github.com/03DxD12/Campus-Study-Space-Finder](https://github.com/03DxD12/Campus-Study-Space-Finder)
* **Tools Used:** Figma, Google Forms, VS Code, HTML5, Tailwind CSS, JavaScript

---

## ❓ Problem Background & Context

College students at DLSP / PLSP frequently encounter long class gaps (1 to 4 hours) throughout the school day. During these breaks, students need functional spaces to review for exams, write research papers, and charge devices. However, because popular spots like the main library, canteens, and building corridors quickly become overcrowded, hot, and noisy, students spend up to 30 minutes walking around campus just trying to find a seat.

### Project Purpose
This case study documents the end-to-end human-centered design process for a mobile-first web application designed to eliminate the guesswork of finding available study spaces on campus through real-time occupancy data, environmental comfort filters, and proactive peak-hour alerts.

---

## 📊 Key Research Findings (N = 27 Survey Data)

Quantitative survey data gathered from **N = 27 enrolled students and stakeholders** across various departments revealed severe operational and environmental pain points:

| Metric | Stat | Impact / User Pain Point |
| :--- | :---: | :--- |
| **Trial-and-Error Searching** | **70.4%** | Students physically roam campus to find open seats before settling. |
| **Peak-Hour Overcrowding** | **88.8%** | Rated finding a space during peak hours (10:00 AM – 2:00 PM) as difficult. |
| **Thermal Discomfort** | **63.0%** | Poor ventilation and extreme indoor heat identified as major obstacles. |
| **Power Outlet Shortage** | **40.7%** | Inadequate charging stations for laptop-dependent tasks. |
| **Wasted Gap Time** | **51.9%** | Spend >15–30 minutes searching for space or leave campus entirely. |

### Verbatim User Voices
> *"Mahirap maghanap ng vacant room lalo na pag hapon at mainit maglakad-lakad."*  
> — **BS Psychology Student**

> *"Kadalasan puno ang library at canteen, kaya sa hallway na lang kami nag-aaral kahit maingay at mainit."*  
> — **BSIT Student**

> *"Sana may central hub or app kung saan makikita kung aling rooms ang walang klase."*  
> — **Engineering Student**

---

## 👤 User Persona & Journey Map

### Primary Persona: Peter Parker
* **Demographics:** 20 years old · 3rd Year BS Psychology (College of Arts and Sciences)
* **Schedule:** Back-to-back lectures with 2-hour gaps between classes.
* **Primary Device:** Laptop (essential for research papers & lab reports).
* **Core Goal:** Quickly locate quiet, cool study spaces with power outlets without wasting energy roaming campus.
* **Verbatim User Story:**
  > *"As a busy college student with tight class gaps, I want to view real-time occupancy and amenity status of campus study spaces, so that I can immediately head to a suitable location without wasting time or energy."*

### 5-Phase User Journey
1. **Trigger:** Class ends; Peter has a 2-hour gap and low laptop battery.
2. **Search & Discovery:** Opens the Study Space Finder app on mobile to inspect campus occupancy map.
3. **Filter & Select:** Filters spaces by `Quiet Zone` + `Available Outlets` + `Air Conditioned`.
4. **Navigate & Arrive:** Selects Library 2F (12 seats free) and follows direct directions.
5. **Post-Use Feedback:** Studies productively for 1.5 hours and submits space feedback upon departure.

---

## 💡 Proposed Solution Concept

The **Campus Study Space Finder** app features:
1. **Live Occupancy Status:** Color-coded crowd density indicators (Green: <50% full, Amber: 50-79%, Red: ≥80% full).
2. **Smart Comfort Filters:** Filter spaces by noise level, temperature, air conditioning, and power outlet count.
3. **Amenity Badging:** Immediate visibility for Wi-Fi strength, food policy, and desk space.
4. **Peak-Hour Alerts:** Proactive notifications warning students before 10:00 AM rush hour begins.

---

## 🧪 Usability Testing & System Usability Scale (SUS)

* **Participants:** N = 3 DLSP / PLSP students across different colleges.
* **Evaluation Method:** Moderated usability testing on Figma interactive prototype + System Usability Scale (SUS) questionnaire.
* **Tasks Executed:**
  * *Task 1:* Search & Filter study space by Quiet + Outlet availability (100% completion rate).
  * *Task 2:* Select room, view detail page, and initiate navigation (100% completion rate).
* **System Usability Scale (SUS) Score:** **87.5 / 100** (`Grade A`, *Excellent Usability*).

### Iterations & Improvements
* **Filter Discoverability:** Replaced top-right icon-only filter with a visible horizontal chip filter row directly beneath the search bar.
* **CTA Prominence:** Converted small text directions link into a sticky full-width primary action button (`📍 Get Directions`) on room detail screens.

---

## 📁 Repository Structure

```
Campus-Study-Space-Finder/
├── index.html        # Interactive UX Case Study Portfolio Web Application
├── README.md         # Documentation & Research Summary
├── .gitignore        # Git ignore rules
└── LICENSE           # MIT License
```

---

## 🚀 Local Setup & Preview

1. **Clone the repository:**
   ```bash
   git clone https://github.com/03DxD12/Campus-Study-Space-Finder.git
   ```
2. **Navigate to project directory:**
   ```bash
   cd Campus-Study-Space-Finder
   ```
3. **Open in browser:**
   Double-click `index.html` or run with VS Code Live Server.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

Developed with ❤️ by **Denmhar Suaze Dimaculangan** for **ITST 306 — UX/UI Design**.
