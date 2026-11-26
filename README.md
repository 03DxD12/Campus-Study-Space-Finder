# 🎓 Campus Study Space Finder
### *A Data-Driven UX Case Study & Comprehensive Research Documentation*

![UX Case Study](https://img.shields.io/badge/Course-ITST%20306%20--%20UX%2FUI%20Design-006B3C?style=for-the-badge)
![Institution Context](https://img.shields.io/badge/Institution-DLSP%20%2F%20PLSP-FFD700?style=for-the-badge&labelColor=000000)
![SUS Usability Score](https://img.shields.io/badge/SUS%20Score-87.5%2F100%20(Grade%20A)-1E90FF?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed%20%26%20Documented-brightgreen?style=for-the-badge)

---

## 📌 Project Identification & External Links

* **Student's Full Name:** Denmhar S. Dimaculangan  
* **Lead Researcher, Designer & Developer:** Denmhar Suaze Dimaculangan  
* **Published Behance Project URL:** [https://www.behance.net/portfolio/editor?project_id=257152609](https://www.behance.net/portfolio/editor?project_id=257152609)  
* **Figma Link (Final Prototype - Design View):** [https://www.figma.com/design/mI3IJc3ZHZFHTVlyQgzyKJ/Campus-Study-Space-Finder--Final-Version?node-id=0-1&t=o1ad1NBsoze8Q2sw-1](https://www.figma.com/design/mI3IJc3ZHZFHTVlyQgzyKJ/Campus-Study-Space-Finder--Final-Version?node-id=0-1&t=o1ad1NBsoze8Q2sw-1)  
* **Figma Link (Preview Mode - Presentation):** [https://www.figma.com/proto/mI3IJc3ZHZFHTVlyQgzyKJ/Campus-Study-Space-Finder--Final-Version?node-id=3-29431&p=f&t=syIVmg44HQ7ypJ7W-0&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1](https://www.figma.com/proto/mI3IJc3ZHZFHTVlyQgzyKJ/Campus-Study-Space-Finder--Final-Version?node-id=3-29431&p=f&t=syIVmg44HQ7ypJ7W-0&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1)  
* **Figma Published Working Site (Working from Figma FINAL):** [https://print-mural-71153100.figma.site](https://print-mural-71153100.figma.site)  
* **Figma Link (Low-Fidelity Prototype):** [https://www.figma.com/design/YZJ0DFEugKZAJKTQvuSK3R/Low-Fidelity-Prototype-of-Campus-Study?node-id=0-1&t=jteepnYhBn7owRbh-1](https://www.figma.com/design/YZJ0DFEugKZAJKTQvuSK3R/Low-Fidelity-Prototype-of-Campus-Study?node-id=0-1&t=jteepnYhBn7owRbh-1)  
* **Interactive Mobile Simulator (Local):** [prototype.html](prototype.html)  
* **UX Portfolio Case Study (Local):** [index.html](index.html)  

---

## 1. Project Overview and UX Project Brief

College students at **Dalubhasaan ng Lunsod ng San Pablo (DLSP)** and **Pamantasan ng Lungsod ng San Pablo (PLSP)** experience significant daily spatial friction during class gaps spanning **1 to 4 hours**. Overcrowding in primary campus facilities including the Main Library, canteens, and building corridors forces students into trial-and-error roaming. Students routinely spend up to **30 minutes** walking across campus in high tropical heat searching for an available seat, a functional power outlet, or a quiet environment.

This case study documents the end-to-end human-centered design process for a mobile-first Progressive Web Application (PWA) designed to eliminate spatial navigation friction. This case study documents the end-to-end human-centered design process for a mobile-first Campus Study Space Finder. The proposed platform is designed to reduce trial-and-error searching by providing occupancy information, environmental filters, and crowdsourced status reporting, with a target of allowing students to **identify a suitable space in under 30 seconds**.

### UX Project Brief

* **Lead Researcher, Designer & Developer:** Denmhar Suaze Dimaculangan
* **Academic Context:** ITST 306 — UX/UI Design (LSPU / PLSP / DLSP context)
* **Timeline:** Academic Term 2026
* **Core Deliverables:** UX Research Plan, Quantitative Survey Analytics (N=27), Thematic Affinity Mapping, Target User Persona, Verbatim User Story, User Journey Map, Problem Statement, Design Requirements, Design Goals, Information Architecture, Task-Based User Flow, Storyboard Narrative, Low-Fidelity Wireframes, WCAG-Compliant Design System Specification, High-Fidelity UI Design, Interactive Figma Prototype, Usability Testing Plan & Report (N=3), Before-and-After Iteration Change Logs, Limitations, and Future Roadmap.
* **Tooling Stack:** Figma, Google Forms, VS Code, HTML5, Tailwind CSS.

---

## 2. UX Research Plan, Surveys and/or Interviews, and Research Findings

### UX Research Plan

A mixed-methods research methodology was executed to evaluate campus spatial utilization, student behavior, and physical pain points:

* **Quantitative Data Collection:** Online survey administered via Google Forms (**N=27** enrolled DLSP / PLSP students across academic colleges) measuring time loss, search habits, and environmental pain points.
* **Qualitative Data Synthesis:** Thematic affinity mapping and clustering of open-ended participant responses to isolate primary friction points.

### Surveys and/or Interviews

Participant privacy was strictly maintained in compliance with data protection standards. Email addresses, student identification numbers, and personal identifiers were anonymized prior to synthesis. Explicit digital consent was obtained from all participants before survey submission.

### Research Findings

Quantitative survey analytics (N=27) revealed major bottlenecks in campus study habits:

#### Key Quantitative Metrics

| Metric Category | Data Percentage (Ratio) |
| :--- | :--- |
| **Trial-and-Error Physical Roaming** | **70.4%** (19 / 27 respondents) |
| **Peak-Hour Bottleneck Difficulty (10 AM - 2 PM)** | **88.9%** (24 / 27 respondents) |
| **Thermal Discomfort & Poor Ventilation** | **63.0%** (17 / 27 respondents) |
| **Wasted Gap Time / Leaving Campus Entirely** | **51.9%** (14 / 27 respondents) |
| **Severe Power Outlet Shortage** | **40.7%** (11 / 27 respondents) |

#### Top Study Locations Utilized on Campus (Multiple Selections)

| Location Category | Response Share (Ratio) |
| :--- | :--- |
| **Corridor Benches / Hallway Seats** | **50.0%** (12 / 24 respondents) |
| **Library / Reading Rooms** | **37.5%** (9 / 24 respondents) |
| **Empty / Unlocked Classrooms** | **29.2%** (7 / 24 respondents) |
| **Canteen / Cafeteria Area** | **25.0%** (6 / 24 respondents) |
| **Open Areas / Campus Grounds** | **20.8%** (5 / 24 respondents) |

---

## 3. User Persona, User Stories, and User Journey Map

### Target User Persona

* **Full Name:** Peter Parker
* **Demographics:** 20 years old | 3rd Year BS Psychology Student, College of Arts and Sciences (CAS), DLSP / PLSP Campus
* **Behavioral Context:** Spends 1 to 4 hours on campus between lectures; carries a laptop continuously to analyze psychology case studies and draft research modules.
* **Verbatim Quote:** *"Ikot muna bago makaupo is real during midterms—I just want a quiet spot with an outlet so I can finish my case studies."*
* **Primary Goals:** Locate quiet study spaces quickly during class gaps; find functional tables with accessible power outlets to keep devices charged.
* **Primary Frustrations:** Severe overcrowding during peak hours (10:00 AM – 2:00 PM); hot, poorly ventilated reading rooms; losing 20–30 minutes of study gap time to trial-and-error roaming.

### User Story

> *"As a dedicated DLSP / PLSP Psychology (CAS) student who spends long class gaps on campus, I want to check real-time study space availability, noise levels, and power outlet access on my phone, so that I can secure a quiet spot quickly without wasting break time walking around or missing out on study time."*

#### Structure Breakdown

* **Type of User:** Dedicated DLSP / PLSP Psychology (CAS) student who spends long class gaps on campus
* **Action:** Check real-time study space availability, noise levels, and power outlet access on my phone
* **Benefit:** Secure a quiet spot quickly without wasting break time walking around or missing out on study time

### Part 3: User Journey Map

* **User:** Peter Parker (BS Psychology, CAS)
* **Goal:** Locate and secure an available, quiet, and well-ventilated study spot during a 2-hour class gap at DLSP / PLSP to review research modules and case studies.

| Phase / Stage | 1. Step Out of Class | 2. Search for Space | 3. Evaluate Options | 4. Secure & Settle | 5. Complete Study Session |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Task List** | **A.** Finish Psychology lecture.<br/><br/>**B.** Check class schedule for break duration.<br/><br/>**C.** Decide to review for the upcoming midterm exam. | **A.** Walk to the primary spot (Library).<br/><br/>**B.** Check if seats/tables are available.<br/><br/>**C.** Message class group chat to ask peers if other areas are open. | **A.** Notice Library is overcrowded and hot.<br/><br/>**B.** Walk to the secondary spot (CAS hallway benches/Canteen).<br/><br/>**C.** Check for accessible power outlets. | **A.** Find an open bench near the CAS building.<br/><br/>**B.** Deal with surrounding background noise.<br/><br/>**C.** Unpack laptop and reading materials. | **A.** Attempt to focus on reading case studies.<br/><br/>**B.** Monitor laptop battery level due to lack of outlets.<br/><br/>**C.** Pack up to head to the next lecture room. |
| **Feeling Adjective** | Hopeful, Determined | Confused, Frustrated | Annoyed, Overwhelmed | Relieved, Slightly Disappointed | Exhausted, Distracted |
| **Pain Points** | Short break time (1–2 hours) available to complete tasks. | The library is overcrowded ("tambayan"); 66.7% of students are forced to walk around campus to find spots. | Excessive heat, poor air conditioning, and a severe lack of power outlets for devices. | Background noise from passing students makes deep concentration difficult. | Wasted 20–30 minutes searching, leaving significantly less time to study before the next class. |
| **Improvement Opportunities** | Mobile notifications for schedule updates and class gap reminders. | **Live Occupancy Status:** Centralized digital map showing real-time seat availability. | **Facility Tags:** Clear indicators for "Quiet Zones", AC status, and power outlet availability. | **Reservation System:** Option to book study slots during peak hours (10:00 AM – 2:00 PM). | **Covered Benches:** Additional shaded outdoor tables with built-in outlets around department buildings. |

---

## 4. Problem Statement, Design Requirements, and Design Goals

### Problem Statement

> **DLSP / PLSP students waste up to 30 minutes of class gap time wandering around campus because they lack visibility into room occupancy, indoor temperature, noise levels, and power outlet availability.**

### Design Requirements

* **Status Badges:** Color-coded occupancy indicators (Green = Available 0–50%, Amber = Filling Up 51–79%, Red = Full 80–100%).
* **One-Tap Filter Bar:** Horizontal category chip row for immediate one-tap filtering with zero sub-menu depth.
* **Crowdsourced Reporting Engine:** A simplified reporting flow designed with a target completion time of under 10 seconds, supported by data-freshness timestamps.

### Design Goals

* **Search Acceleration:** Enable users to identify and select a suitable study space within a target of 30 seconds.
* **Navigation Friction Elimination:** Eliminate trial-and-error roaming through real-time occupancy status badges.
* **Environmental Filtering:** Provide instant filtering for environmental attributes (Quiet Zone, Working A/C, Power Outlets).

---

## 5. Information Architecture, Sitemap, and User Flow

### Information Architecture

To minimize tap depth for students walking between classes, the application utilizes an intuitive, hierarchical feature structure that connects room details and reporting directly beneath the primary discovery flow:

* **1.0 Home / Explore (Primary Main Section)**
  * **1.1 Search & Autocomplete:** Global search across campus buildings, room names, and floor levels.
  * **1.2 Live Occupancy Filter:** Instant filtering by real-time crowd status (Available, Filling Up, Full).
  * **1.3 Quiet & Comfort Filters:** Quick-access category chips for noise ratings, working A/C, and power outlets.
  * **1.4 Map / List Toggle:** Instant view state switcher between interactive campus map and spatial list cards.
  * **1.5 Nearby Spaces:** Proximity-sorted card feed displaying real-time space conditions.

### Sitemap

```
1.0 Home / Explore
   ├── 1.1 Search & Autocomplete
   ├── 1.2 Live Occupancy Filter
   ├── 1.3 Quiet & Comfort Filters
   ├── 1.4 Map / List Toggle
   └── 1.5 Nearby Spaces
        │
        └── 2.0 Space Details (Child Overlay / Drawer)
             ├── 2.1 Live Capacity
             ├── 2.2 Temperature & Noise
             ├── 2.3 Amenities
             ├── 2.4 Get Directions
             └── 2.5 Photos & Reviews
                  │
                  └── 3.0 Report Space Status (Child Action Modal)
                       ├── 3.1 Start a Report
                       ├── 3.2 Select Occupancy Level
                       ├── 3.3 Update Comfort Conditions
                       ├── 3.4 Review & Submit
                       └── 3.5 Submission Confirmation

4.0 Profile (Secondary Main Section)
   ├── 4.1 Saved Spaces
   ├── 4.2 Contribution History
   ├── 4.3 Notification Preferences
   └── 4.4 Help & Campus Information
```

### User Flow: Find a Quiet Study Space

**User Goal:** Identify and select an available, quiet study space with power outlets within 30 seconds, then navigate to the selected location.

| Step | Action Screen | Interaction Detail | Primary Output / System Response |
| :--- | :--- | :--- | :--- |
| **1. Open App** | Launch | App opens and the proximity-sorted live feed loads automatically. | Proximity feed initialized. |
| **2. View Feed** | Home / Explore | Student scans real-time availability badges and nearby study spaces. | Live space list rendered. |
| **[Decision 1]** | Suitable space visible? | Evaluates if a nearby spot meets immediate criteria directly from feed badges. | **Yes** $\rightarrow$ Step 4 \| **No** $\rightarrow$ Step 3 |
| **3. Apply Filters** | Filter Bar | Taps Quiet + Outlets inline category chips. | Feed updates with compliant study spots only. |
| **4. Select Space** | Space Details Trigger | Taps CAS Bench 3 card from the filtered or primary list. | Space detail overlay expands. |
| **5. Inspect Space Details** | Space Details | Checks real-time temperature (24°C), decibel level (Quiet), and power outlets (8 Outlets). | Environmental conditions verified. |
| **[Decision 2]** | Meets study needs? | Confirms if room attributes meet study requirements. | **Yes** $\rightarrow$ Step 6 \| **No** $\rightarrow$ Return to Feed |
| **6. Get Directions** | Direction CTA | Taps sticky full-width Get Directions button. | In-campus route overlay rendered. |
| **7. Arrive & Study** | Destination | Student follows the route, arrives at selected location, and begins studying (< 30s elapsed time). | Task completed. |

---

## 6. Storyboard, Sketches & Low-Fidelity Wireframes

### Storyboard Narrative

* **Frame 1:** Peter finishes his Psychology lecture at 10 AM, facing a 2-hour class break.
* **Frame 2:** Instead of walking blindly across campus, he launches the Campus Study Space Finder app on his phone.
* **Frame 3:** He taps "Quiet" and "Outlets" filter chips; the app reveals the Main Library is 90% full, but CAS Bench Cluster 3 has open seats and power access.
* **Frame 4:** Peter walks directly to CAS Bench 3, plugs in his laptop, and begins reviewing his case studies immediately.

### Sketches

Early conceptual sketches focused on evaluating thumb-zone ergonomics for single-handed smartphone interaction while walking:
* **Header Zone:** Sticky search bar and category chip row positioned within comfortable thumb reach.
* **Body Zone:** Vertical card feed prioritized by real-time distance and capacity status.
* **Bottom Zone:** Persistent action drawers anchored to the lower viewport edge.

### Low-Fidelity Wireframes

Low-fidelity wireframes were created in Figma using grayscale layout blocks to validate information architecture, layout density, and navigation before applying visual styling:
* **Screen 1 (Home Feed):** Top sticky search bar, horizontal scrollable filter chip row, vertical stream of space cards with grayscale placeholder badges.
* **Screen 2 (Detail Drawer):** Bottom overlay card containing occupancy percentage bar, amenity grid, and full-width bottom button.
* **Screen 3 (Crowd Report Form):** Minimalist radio selector modal designed for fast thumb interaction.
* [View Low-Fidelity Prototype on Figma ↗](https://www.figma.com/design/YZJ0DFEugKZAJKTQvuSK3R/Low-Fidelity-Prototype-of-Campus-Study?node-id=0-1&t=jteepnYhBn7owRbh-1)

---

## 7. High-Fidelity Mockups and Visual Interface Design

### High-Fidelity Mockups

High-fidelity Figma screens establish pixel-perfect visual hierarchy, adhering strictly to the design system:
* **Home Feed Screen:** Displays color-coded capacity badges (Available, Filling Up, Full), distance indicators, and front-facing micro-badges.
* **Space Detail Overlay:** Expands to show real-time temperature (24°C), decibel level rating (Quiet), exact power outlet availability (4 Outlets), and Wi-Fi performance.
* **Crowd Report Modal:** Features clean radio inputs and single-tap submit toggles to reduce friction for reporting students.

### Visual Design System & Accessibility Considerations

| Color Name | Hex Code | System Role | Accessibility & Usage Application |
| :--- | :---: | :--- | :--- |
| **Forest Green** | `#006B3C` | Primary Brand | Primary headers, active buttons, positive badges |
| **Gold / Yellow** | `#FFD700` | Accent / Highlighting | Active filter chips, rating stars, key accents |
| **Flame Red** | `#FF4500` | Alert / Warning | Full status indicators, high heat alerts (>30°C) |
| **Sky Blue** | `#1E90FF` | Environmental Data | Temperature indicators, Wi-Fi tags, link states |
| **Pure White** | `#FFFFFF` | Base Canvas | High-contrast background for body legibility |

* **Typography:** Set in Inter / System Sans-Serif. Scale ranges from 9px uppercase captions up to 24px/32px bold headers, adhering to a 4pt/8pt baseline grid.
* **Component Architecture:** Space cards incorporate micro-badges (e.g., 24°C, 4 Outlets, Quiet) directly on the preview layout, eliminating unnecessary taps.

---

## 8. Interactive Prototype and Cross-Platform Design Considerations

### Interactive Prototype

The high-fidelity solution is implemented as a mobile-first web application engineered with HTML5 and Tailwind CSS.

#### Core Operational Features

* **Live Occupancy Badging:** Color-coded badges (Available in Green, Filling Up in Amber, Full in Red) displaying live capacity ratios (e.g., 12/35 Seats).
* **Environmental Micro-Badges:** Front-facing indicators for ambient temperature (24°C), accessible power outlet count (4 Outlets), and noise level tags.
* **Freshness Timestamping:** Explicit data freshness captions (Updated 5 mins ago) displayed on every card to establish trust in crowdsourced reports.

### Cross-Platform Design Considerations

* **Mobile-First Responsive Layout:** Engineered primarily for 375px–430px smartphone viewports, scaling seamlessly up to tablet and desktop screens.
* **PWA Capability & Service Worker Caching:** The mobile-first architecture can be extended with installable Progressive Web App capabilities and offline caching in a production implementation.
* **Thumb-Zone Ergonomics:** All primary interactive controls including filter chips, detail drawers, and submit buttons are placed within the lower half of the screen for comfortable one-handed use while walking.

---

## 9. Usability-Testing Plan, Observations, and Findings

### Usability-Testing Plan

Moderated task-based usability testing was executed with **N=3** DLSP / PLSP student participants representing different academic colleges on the interactive Figma prototype.

#### Test Tasks Executed

* **Task 1:** Search and filter for a quiet study space near CAS with accessible power outlets.
* **Task 2:** Select a room, inspect its environmental details, and initiate navigation.

### Usability-Testing Observations

* **Observation 1 (Environmental Visibility):** Participants praised occupancy percentages but requested temperature readings and power outlet counts visible directly on card thumbnails without opening detail drawers.
* **Observation 2 (Data Trust):** Users wanted explicit timestamps showing when crowd data was last updated to ensure accuracy before walking across campus.
* **Observation 3 (Control Discoverability):** Participants expected inline filter controls rather than relying on hidden icon-only buttons.

### Usability-Testing Findings

* **Task Completion Rate:** **100% success rate** across all participants for both assigned tasks (3/3 completed).
* **System Usability Scale (SUS) Score:** **87.5 / 100** (Grade A, Excellent usability rating).
* **Validation:** **100%** of participants confirmed the application solved a recurring daily problem and expressed intent to use it during class gaps.

---

## 10. Design Iteration, Before-and-After Comparisons, and Design Rationale

### Design Iteration

Systematic iterations were implemented following usability testing feedback to optimize visual scanning and interaction speed between prototype versions V1 and V2.

### Before-and-After Comparisons

* **Iteration 01: Filter Control Discoverability**
  * *Before (V1):* Icon-only control enclosed inside the search bar.
  * *After (V2 Implementation):* Visible, horizontal labeled filter chips (Quiet, Outlets, A/C) placed inline directly below the search header.
* **Iteration 02: Directions CTA Visual Hierarchy**
  * *Before (V1):* Small inline text link within the detail drawer.
  * *After (V2 Implementation):* Sticky full-width Forest Green button (Get Directions →) anchored to the bottom screen edge.
* **Iteration 03: Environmental Micro-Badges**
  * *Before (V1):* Temperature ratings and outlet counts were enclosed inside the space detail drawer.
  * *After (V2 Implementation):* Placed 24°C and 4 Outlets micro-badges directly on preview thumbnails.

### Design Rationale

* **Inline Filter Chips:** Moving filter controls inline reduced tap depth and eliminated menu navigation for walking students.
* **Sticky Full-Width CTA:** Elevating the navigation link to a full-width primary button made the core call-to-action visually dominant and easily thumb-reachable.
* **Thumbnail Micro-Badges:** Exposing key environmental metrics directly on card thumbnails reduced cognitive load, enabling instant visual scanning without extra taps.

---

## 11. Final Solution, Reflection, Limitations, and Future Improvements

### Final Solution

The Campus Study Space Finder presents a research-informed mobile solution designed to reduce trial-and-error searching by giving students centralized visibility into occupancy, environmental conditions, and available amenities. The final prototype targets a study-space identification time of under 30 seconds, while real-world performance would require deployment and field validation.

### Reflection

Designing this platform highlighted the critical necessity of balancing automated UI clarity with crowdsourced data dynamics. Designing specifically for students on the move emphasized that mobile-first UX design requires extreme tap-depth reduction, high visual contrast, and clear visual feedback.

### Limitations

* **Crowdsourced Dependence:** Initial releases rely on peer crowd reports, which may experience data freshness lag during off-peak campus hours.
* **Testing Environment:** Usability testing was conducted on simulated interactive Figma prototypes rather than live production environments with hardware sensors.

### Future Improvements

* **IoT & Sensor Integration:** Connect platform backends to campus optical door sensors and automated library turnstiles for real-time occupant counting.
* **Seat Reservation Engine:** Implement a short-term holding feature (e.g., 15-minute desk holding) to guarantee seat availability upon arrival during peak hours (10:00 AM – 2:00 PM).
* **QR-Code Check-Ins:** Deploy desk-level QR codes for self-service seat check-ins and automatic check-outs.

---

## 👨‍💻 Author & Credits

* **Student's Full Name:** Denmhar S. Dimaculangan  
* **Lead Researcher, Designer & Developer:** Denmhar Suaze Dimaculangan  
* **Academic Course:** ITST 306 — UX/UI Design  
* **Academic Institutions:** Dalubhasaan ng Lunsod ng San Pablo (DLSP) / Pamantasan ng Lungsod ng San Pablo (PLSP)  
* **License:** Open Source under the MIT License
