# NeerShuddh-ai-groundwater-safety-system
NeerShuddh is an AI-powered groundwater monitoring platform that detects contamination early using field inputs, image uploads, and machine learning. It connects volunteers and ASHA workers to generate alerts, analyze test data, and notify officials for timely action.

# 🌊 NeerShuddh — AI Groundwater Safety System

## 🚀 Overview
NeerShuddh is an AI-powered groundwater monitoring platform designed to detect contamination early and enable timely intervention. It connects Volunteers, ASHA Workers, and Health Officials through a real-time workflow supported by machine learning and geospatial visualization.

---

## 👥 User Roles & Workflow

### 🔹 1. Volunteer Module
- Secure login for volunteers
- Upload **strip test image**
- Automatic extraction of basic parameters (e.g., pH)
- Capture **geolocation (GPS)**
- On submission:
  - Data is stored
  - Initial risk is evaluated
  - Alert is sent to nearby ASHA Worker (SMS simulation)

---

### 🔹 2. ASHA Worker Module
- Login to view **Pending Alerts**
- Access volunteer-submitted reports
- Perform **detailed field testing**

#### 🧪 Manual Chemical Input (8 Parameters)
- Fluoride  
- Nitrate  
- Arsenic  
- pH Level  
- TDS  
- Iron  
- Rainfall  
- Depth  

- Upload additional test images
- Click **"AI Analysis"** to process data

#### 🤖 AI Output
- Risk Level: **Safe / At-Risk / Dangerous**
- Confidence Score
- Chemical Composition Analysis
- Health Risk Advice
- Recommended Actions

---

### 🔹 3. Health Admin Dashboard
- Role-based admin login
- **District-wise contamination analysis**
- View:
  - Total affected villages
  - Risk distribution (Safe / At-Risk / Dangerous)
  - Recent submissions across regions
- **Live Map Visualization**
  - Color-coded markers:
    - 🟢 Safe
    - 🟡 At-Risk
    - 🔴 Dangerous
- Data-driven insights for decision making

---

## 🔄 End-to-End Workflow

Volunteer Upload  
⬇  
AI Pre-Check + Geolocation  
⬇  
ASHA Worker Alert (SMS Simulation)  
⬇  
Manual Chemical Analysis  
⬇  
AI Prediction & Risk Classification  
⬇  
Admin Dashboard + Live Map Update  

---

## 🧠 Key Features

- 📸 Image-based water testing input  
- 📍 Real-time geolocation tracking  
- 📩 Automated alert system  
- 🧪 Multi-parameter chemical analysis  
- 🤖 AI-powered contamination prediction  
- 🗺️ Interactive map visualization  
- 📊 District-level analytics dashboard  

---

## 🎯 Impact

NeerShuddh enables **early detection, faster response, and informed decision-making**, helping prevent groundwater-related health risks in rural communities.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Material UI, Google Maps API  
- **Backend:** FastAPI (Python), Firebase  
- **Database:** Firestore  
- **AI/ML:** Random Forest Model  
- **Alerts:** SMS Simulation (Twilio-ready)  

---

## 📌 Future Enhancements

- Real-time IoT water sensors  
- Advanced geospatial spread prediction  
- Multilingual mobile support  
- Government integration APIs  

---
