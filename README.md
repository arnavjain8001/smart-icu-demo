# 🏥 Smart ICU Monitoring & Patient Management System

A modern, real-time web application designed for intensive care units (ICU) to monitor patient vital signs, track emergency timelines, manage ward capacities, and coordinate healthcare staff efficiently.

---

## 🌟 Key Features

* 🩺 **Real-Time Patient Vitals:** Live monitoring of critical metrics including Heart Rate (BPM), SpO2 levels, Blood Pressure, and Body Temperature.
* 🚨 **Emergency Alerts & Timeline:** Instant visual popups and chronological emergency logging for quick medical intervention.
* 🏢 **Ward & Bed Overview:** Comprehensive dashboard to track available, occupied, and critical ICU beds.
* 👨‍⚕️ **Staff Management:** Track doctors and nursing staff on duty with real-time assignment statuses.
* 📋 **Patient History & Reports:** Detailed medical histories, past reports, and vital trend analytics.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, Vite
* **Styling:** CSS3, Tailwind CSS / Custom Styling
* **Icons:** Lucide React / SVG Icons
* **Data Management:** Mock Data Service for real-time state simulation

---

## 📁 Project Structure

```text
smart-icu-demo/
├── public/                 # Favicon & Static SVG icons
├── src/
│   ├── assets/             # Branding images & SVG assets
│   ├── components/         # Reusable UI components (Navbar, Sidebar, PatientCard, etc.)
│   ├── pages/              # Main view pages (Dashboard, WardOverview, EmergencyTimeline, etc.)
│   ├── mockData.js         # Simulated ICU patient vitals and hospital data
│   ├── App.jsx             # Main router & layout entry point
│   ├── index.css           # Global application styles
│   └── main.jsx            # React DOM render entry
├── package.json            # Project dependencies and scripts
└── vite.config.js          # Vite build configuration

