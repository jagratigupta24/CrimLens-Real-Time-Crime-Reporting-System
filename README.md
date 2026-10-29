# 🔍 CrimeLens — Real-time Crime Reporting System

CrimeLens is a web-based platform that connects citizens with the police for faster crime reporting and emergency response. Users can report incidents with their GPS location, photos, videos, and a description. The report is then classified and sent to the nearest police dashboard.

🌐 **Live Demo:** [crimelens-real-time-crime.vercel.app](https://crimelens-real-time-crime.vercel.app/)

---

## 📌 Problem Statement

Crimes often go unreported or are reported late, which slows down the police response. There is no simple, single platform where citizens can share the exact location and evidence of an incident directly with the police.

## 💡 Our Solution

CrimeLens lets citizens report an incident in a few steps. The system captures the location automatically, classifies the incident using rule-based logic, and forwards it to the nearest police dashboard. This helps the police respond faster, preserves digital evidence, and helps identify high-risk areas.

## ✨ Features

- 📍 Automatic GPS location capture
- 📝 Incident reporting with description, photos, and videos
- 🗂️ Rule-based incident classification
- 🚓 Reports sent to the nearest police dashboard
- 🔄 Response status updates
- 🗺️ Map view using Leaflet.js and OpenStreetMap
- 🔥 Crime hotspot analysis
- 🔐 Secure login with JWT authentication and bcrypt password hashing

## 🔄 How It Works

1. Citizen selects the incident type and location
2. GPS location is captured automatically
3. Citizen uploads details and evidence (photos / videos / description)
4. Incident is classified using rule-based logic
5. Report is sent to the nearest police dashboard
6. Police unit is dispatched to the location
7. Response updates are shared back

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, Express |
| Database | JSON file |
| Maps | Leaflet.js, OpenStreetMap |
| Classification | Rule-based logic |
| Security | JWT Authentication, bcrypt |
| Hosting | Vercel |

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher)
- npm

## 🔮 Future Scope

- Cloud deployment and storage on AWS
- AI-based incident classification and crime prediction
- Integration with CCTV networks and Smart City systems
- Integration with ERSS-112 and existing emergency services
- Mobile application

## ⚠️ Disclaimer

This is a student project built for learning and demonstration. Please use only dummy data. In a real emergency, call **112** (India).


**Theme:** Security & Surveillance

## 📄 License

This project is licensed under the MIT License.
