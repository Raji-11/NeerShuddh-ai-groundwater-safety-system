💧 NeerShuddh — AI-Powered Shield for India's Groundwater

Data-Driven Volunteer Coordination Platform for Community Water Safety

🚀 Live Links

🌐 Web App: https://neershudh-web.vercel.app

⚙️ Backend API: https://ais-dev-btdhj7cqc7qxyfgigwwczz-293106883282.asia-southeast1.run.app

📖 API Docs: https://ais-dev-btdhj7cqc7qxyfgigwwczz-293106883282.asia-southeast1.run.app/docs

💻 GitHub: https://github.com/Raji-11/NeerShuddh-ai-groundwater-safety-system

🌊 The Problem

India is facing a silent public health crisis.

600 million Indians drink contaminated water every day — not because it looks dirty, but because the poison is invisible.

230 districts report excess fluoride

153 districts report arsenic contamination

Nalgonda (Telangana): 1M+ affected

25 years of groundwater data exists but doesn’t reach villages

No early warning system

Detection happens only after people fall sick

💡 Solution

NeerShuddh is an AI-powered system that:

Predicts contamination before health damage occurs

Enables volunteers to test water locally

Alerts villages using SMS (works on 2G phones)

Shows contamination on a live map dashboard

Generates government-ready reports

🧠 System Workflow
🦺 Volunteer (Water Guardian)

Register and receive village assignment

Perform strip test

Upload image or send via SMS

AI detects result (Green / Yellow / Red)

Unsafe results trigger alert

🏥 ASHA Worker

Receives SMS alert

Visits village

Conducts 8-chemical test

Uploads results

AI performs detailed analysis

Sends warning if water is dangerous

👨‍💼 Admin

Views live contamination map

Analyzes trends and comparisons

Exports reports

🧪 Chemical Detection

Fluoride

Arsenic

Nitrate

pH

TDS

Iron

Hardness

Lead

🤖 AI / ML Model

Dataset: CGWB (2012–2021)

Records: 6,316

Algorithm: Random Forest

Accuracy: 99.5%

Additional techniques:

Geospatial prediction

Time-series forecasting

🛠️ Tech Stack

Frontend: React + TypeScript + Vite

Styling: Tailwind CSS

Backend: FastAPI (Python)

ML: scikit-learn

Database: Firebase

Auth: Firebase Auth

Maps: Google Maps API

SMS: Twilio API

AI: Gemini API

📁 Project Structure
neershudh/
├── src/
├── backend/
├── server.ts
├── package.json
└── README.md
🚀 Run Locally
Frontend
git clone https://github.com/Venkata-Harika09/neershudh.git
cd neershudh
npm install
npm run dev
Backend
cd backend
python -m venv venv
pip install -r requirements.txt
uvicorn main:app --reload
📊 Dataset

CGWB Groundwater Data (2012–2021)

IMD Rainfall Data

Census Village Data

🌍 Impact

600M people can be protected

6.5 lakh villages covered

Faster response (years → days)

Zero-cost alert system

🎯 SDG Goals

Clean Water & Sanitation

Good Health

Reduced Inequalities

Sustainable Cities

🏆 Hackathon

Event: 24-Hour Hackathon

Domain: Social Impact

Date: March 2026

Team:

Boddupalli Venkata Harika

Bondada Raja sri yasaswini

Malla Geetamaaduri

💧 Final Note

Clean water is not a privilege — it is a basic human right.
