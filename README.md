# 🌍 TravelWise AI

**TravelWise AI** is an intelligent travel planning platform that helps users plan smarter journeys with route optimization, weather forecasting, transport fare estimation, nearby place discovery, and AI-powered travel recommendations.

Built with **React + Vite**, TravelWise AI provides an interactive map-based experience to simplify trip planning for tourists, office commuters, families, students, and medical travelers.

---

## ✨ Features

### 🗺️ Smart Route Planning

* Get optimized routes between locations
* Interactive map visualization using Leaflet
* Multiple travel route support

### 🌦️ Live Weather Forecast

* Weather updates for selected destinations
* Temperature, humidity, precipitation, and wind insights
* Helps users plan trips based on climate conditions

### 🚖 Fare Estimation

Travel cost estimation across multiple transportation modes:

* Walking
* Local Bus
* Train
* Rapido
* Auto
* Ola
* Uber

### 📍 Nearby Place Discovery

Find nearby:

* Restaurants & Cafes
* Hotels
* Tourist Attractions
* Hospitals
* Police Stations
* Bus Stops
* Essential Services

### 🤖 AI Travel Planning

Generates smart travel suggestions based on:

* Tour travel
* Office commute
* College travel
* Family trips
* Medical travel
* Budget travel

### 🧭 Interactive Maps

* Live route rendering
* Destination markers
* Route visualization using OpenStreetMap

---

## 🛠️ Tech Stack

### Frontend

* React 19
* Vite
* React Router DOM

### Maps & Location Services

* Leaflet
* React Leaflet
* OpenStreetMap (Nominatim)

### Routing & Navigation

* OSRM (Open Source Routing Machine)

### Nearby Search

* Overpass API

### Weather Services

* Open Meteo API

### UI & Icons

* Lucide React

---

## 📂 Project Structure

```bash
Travelwise-AI/
│── src/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   ├── main.jsx
│   └── services.js
│
├── public/
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/nirmalkumar703/Travelwise-AI.git
```

### Navigate to Project

```bash
cd Travelwise-AI
```

### Install Dependencies

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

The application will run at:

```bash
http://localhost:5173
```

---

## 🚀 Build for Production

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

## 🔄 Project Workflow

1. User enters start and destination locations
2. Geolocation service converts places into coordinates
3. Route engine calculates optimized travel path
4. Weather API fetches destination climate information
5. Nearby places API recommends useful locations
6. Fare estimation system predicts transport costs
7. AI suggests personalized travel plans based on travel mode

---

## 🎯 Use Cases

* Tourist trip planning
* Budget travel estimation
* Office commute optimization
* Family travel assistance
* Medical emergency route support
* College/student transportation planning

---

## 🔌 APIs Used

| API                     | Purpose             |
| ----------------------- | ------------------- |
| OpenStreetMap Nominatim | Geocoding           |
| OSRM                    | Route optimization  |
| Overpass API            | Nearby place search |
| Open Meteo API          | Weather forecasting |

---

## 📸 Screenshots
<img width="1427" height="778" alt="Screenshot 2026-06-15 at 22 05 18" src="https://github.com/user-attachments/assets/bcb2214c-a226-4bed-8045-0606624a3379" />

<img width="1427" height="778" alt="Screenshot 2026-06-15 at 22 05 27" src="https://github.com/user-attachments/assets/ec01af1e-07d2-497f-a145-7fe225145fa7" />

---

## 🔮 Future Enhancements

* Real-time traffic integration
* Hotel and flight booking
* Voice-based travel assistant
* Personalized AI recommendations
* Offline navigation support
* Multi-language support

---

## 🤝 Contributors

**Nirmal Kumar V**

GitHub:
https://github.com/nirmalkumar703

---

### ⭐ If you found this project useful, consider giving it a star on GitHub.
