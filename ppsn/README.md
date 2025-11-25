# Predictive Personal Safety Network (PPSN)

A community-driven and AI-assisted safety platform that predicts potential risk areas before incidents occur. PPSN analyzes location, time patterns, and community reports to deliver real-time warnings, safer routing, and automated safety workflows.

---

## Project Overview

PPSN is built as an intelligent personal safety layer that fuses mapping, user data, and community reporting into a predictive safety engine. The platform aggregates spatiotemporal data, performs risk scoring, and provides customized safety insights.

Core system capabilities include:

- Predictive danger zone modeling  
- Safety-first routing  
- Automated check-ins with trusted contacts  
- Real-time pre-alert notifications  
- Anonymous community reporting  
- Future goal: AR-based immersive navigation

---

## Tech Stack

- **Frontend:** React.js, Mapbox GL JS, Geolocation API, Web Push  
- **Backend:** Node.js, Express.js, MongoDB  
- **Real-Time:** Firebase Cloud Messaging or WebSockets  
- **AI Layer:** Lightweight risk prediction (time + location heuristics)

---

## 13-Hour MVP Development Plan

### Team Member 1 — Frontend & Map Integration

- Initialize React structure  
- Implement Mapbox maps and risk layers  
- Build safety-route visualization  
- Create user profile and preferences page  
- Connect to backend APIs  

**Deliverables:** Map UI, route display, user settings, risk overlay

---

### Team Member 2 — Backend & API Services

- Initialize Express backend  
- Create MongoDB models (Users, Reports, Incidents)  
- Implement authentication  
- Build REST endpoints for risks, routes, and reporting  
- Implement basic safest-path algorithm  

**Deliverables:** REST API, DB schemas, auth logic, routing engine

---

### Team Member 3 — AI & Real-Time Safety

- Implement time-based risk scoring engine  
- Configure push notifications via Firebase/WebSockets  
- Build automated check-in workflow  
- Implement anonymous reporting ingestion  
- Integrate external crime/safety datasets  

**Deliverables:** risk predictor, notification system, reporting pipeline

---

## MVP Features (13-Hour Goal)

1. Map interface with placeholder danger zones  
2. Simple safest-path routing  
3. User profile with mock preferences  
4. Basic time-based risk scoring  
5. Anonymous incident reporting

---

## Stretch Goals

1. Real-time notifications  
2. Check-in automation  
3. Crime API integration  
4. AR navigation prototype  
5. Mobile responsiveness

---

## Project Structure

```
ppsn-project/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── backend/
│   ├── api/
│   ├── models/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## Setup Instructions

### Frontend

```
cd frontend
npm install
cp .env.example .env
npm start
```

### Backend

```
cd backend
npm install
cp .env.example .env
npm start
```

### Next Steps (Post-MVP)
•	Upgrade prediction model to ML-based risk forecasting
•	Add AR navigation mode
•	Improve mobile-first UI/UX
•	Integrate more real-time data sources
•	Conduct user testing and iterative design

## Build by Team 44
### Team Members - Dhwanil Ranpura, David Song and Krishiv Haranathl









