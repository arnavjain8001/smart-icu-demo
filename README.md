# 🏥 Smart ICU Monitoring & Patient Management System

A modern, real-time web application designed for intensive care units (ICU) to monitor patient vital signs, track emergency timelines, manage ward capacities, and coordinate healthcare staff efficiently.

---

## 🌐 Live Demo

Check out the live working demo here: 
👉 **[https://smart-icu-projects.netlify.app/](https://smart-icu-projects.netlify.app/)**

---

## 🌟 Key Features

* 🩺 **Real-Time Patient Vitals:** Live monitoring of critical metrics including Heart Rate (BPM), SpO2 levels, Blood Pressure, and Body Temperature.
* 🚨 **Emergency Alerts & Timeline:** Instant visual popups and chronological emergency logging for quick medical intervention.
* 🏢 **Ward & Bed Overview:** Comprehensive dashboard to track available, occupied, and critical ICU beds.
* 👨‍⚕️ **Staff Management:** Track doctors and nursing staff on duty with real-time assignment statuses.
* 📋 **Patient History & Reports:** Detailed medical histories, past reports, and vital trend analytics.

---

## 🚀 Future Roadmap & Hardware Integration

We are actively working to transition this web platform into a fully automated IoT-enabled Smart ICU ecosystem:

* 📡 **Custom Hardware Integration:** Developing a physical IoT device equipped with biosensors to record live patient vitals directly from the bedside and stream data wirelessly to the web dashboard in real time.
* 🔄 **Real vs Simulated Data Transition:** While current secondary beds use simulated mock data, the system will gradually sync with live hardware data for all operational ICU beds.
* 🔔 **Smart Emergency Routing & Escalation:** In critical scenarios (e.g., sudden drop in SpO2 or spike in Heart Rate):
  * **Instant Doctor Alerts:** Automated high-priority alerts dispatched directly to the assigned primary doctor.
  * **Proximity Nurse Dispatch:** Real-time push notifications routed to the nearest available on-duty nurse for immediate bedside intervention.

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