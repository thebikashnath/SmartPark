# SmartPark 🚗

> A modern digital parking management system for malls, offices, hospitals and managed buildings.

SmartPark is designed around a simple parking journey:

**Enter → Get QR Ticket → Find a Vacant Space → Reserve → Park → Scan QR → Exit**

The current repository is a polished frontend prototype demonstrating the complete user experience. It is structured so the frontend can later be connected to a Java/Spring Boot backend, PostgreSQL database, real QR generation, ANPR, payment gateway, IoT sensors and entry/exit barriers.

---

## ✨ Features

- 🅿️ **Live Parking Availability** — View vacant, occupied and reserved spaces.
- 🏢 **Floor-wise Parking Map** — Ground Floor, First Floor and Basement.
- 📱 **Digital Parking Experience** — Designed around a web/mobile app flow.
- 🎟️ **QR Parking Ticket** — Digital entry and exit pass.
- 🚘 **Vehicle Registration** — Capture the vehicle number during reservation.
- ⚡ **Instant Space Reservation** — Select an available space and reserve it.
- 🔐 **Entry & Exit QR** — The same ticket is designed for both barriers.
- 📊 **Parking Dashboard** — Total, available, occupied and occupancy metrics.
- 📱 **Responsive UI** — Works across desktop, tablet and mobile.

---

## 🧭 User Journey

```text
Vehicle arrives
      ↓
Entry gate / kiosk
      ↓
QR ticket generated
      ↓
Ticket appears in web / mobile app
      ↓
Live vacant spaces
      ↓
User selects a space
      ↓
Parking space reserved
      ↓
Vehicle parks
      ↓
Same QR scanned at exit
      ↓
Fee calculated + payment
      ↓
Exit barrier opens
```

---

## 🖥️ Current Prototype

The frontend currently demonstrates:

| Module | Status |
|---|---|
| Landing page | ✅ |
| Live parking map | ✅ Prototype |
| Floor selection | ✅ |
| Space selection | ✅ |
| Reservation flow | ✅ Prototype |
| Digital ticket | ✅ Prototype |
| QR ticket UI | ✅ Prototype |
| Vehicle number | ✅ |
| Entry/exit journey | ✅ UI |
| Real QR scanner | 🔜 |
| Authentication | 🔜 |
| Backend API | 🔜 |
| Database | 🔜 |
| Real-time WebSocket updates | 🔜 |
| Payment gateway | 🔜 |
| ANPR / number plate recognition | 🔜 |
| IoT parking sensors | 🔜 |
| Gate/barrier integration | 🔜 |
| Admin dashboard | 🔜 |

---

## 🛠️ Planned Production Stack

### Frontend
- React.js
- HTML5 / CSS3
- JavaScript
- Responsive UI

### Backend
- Java
- Spring Boot
- REST APIs
- WebSocket for live parking updates

### Database
- PostgreSQL

### Smart Parking
- QR generation/scanning
- ANPR / OpenCV / YOLO
- IoT parking sensors
- ESP32
- Entry & exit barrier integration

### Deployment
- GitHub
- Render
- Docker
- AWS (future production deployment)

---

## 📁 Repository Structure

```text
SmartPark/
│
├── index.html              # Frontend prototype
├── README.md               # Project documentation
│
├── docs/
│   ├── ARCHITECTURE.md     # System architecture
│   ├── API.md              # Planned API design
│   └── ROADMAP.md          # Development roadmap
│
├── assets/
│   └── README.md           # Asset guidelines
│
├── .gitignore
└── LICENSE
```

---

## 🚀 Run Locally

No build tools are required for the current prototype.

### Option 1 — Open directly

Open `index.html` in your browser.

### Option 2 — VS Code

Use the **Live Server** extension and open `index.html` 
https://smartpark-cyxs.onrender.com

---

## 🌐 Deploy on Render

Create a **Static Site** in Render and connect this GitHub repository.

Use:

```text
Build Command:       leave empty
Publish Directory:   .
Branch:              main
```

---

## 🎯 Future Development

The long-term goal is to turn this prototype into a complete building parking platform where:

- parking occupancy updates in real time,
- users receive genuine QR tickets,
- reservations are stored in a database,
- vehicle number plates can be recognized automatically,
- parking fees are calculated automatically,
- users can pay digitally,
- barriers validate QR tickets,
- admins can monitor the entire building,
- and IoT sensors provide live slot availability.

---

## 👨‍💻 Project

**SmartPark — Digital Parking Management System**

Built as an industry-oriented software project demonstrating parking operations, digital tickets, reservation workflows and real-time parking concepts.

> Frontend prototype — production integrations are planned for the next development phase.
