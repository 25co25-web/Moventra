# MOVENTRA 🚌

### Real-Time Public Transport Tracking for Small Cities

**MOVENTRA** is a smart public transport tracking system designed to make bus travel easier and more predictable, especially in small cities and rural areas.

It helps passengers check bus locations, view stops and estimated arrival times, while providing drivers and administrators with tools to manage trips and live transport data.

---

## 🚀 Features

### 👤 Passenger

* View buses and routes
* Track buses on a live map
* View nearby bus stops
* Check estimated arrival times
* See current bus status
* Search for buses and routes
* Get notified when a bus is approaching a stop

### 👨‍✈️ Driver

* Driver login
* Start and end trips
* Share real-time GPS location
* View assigned route
* Track trip progress
* Automatic location updates during an active trip

### 🛠️ Admin

* Manage buses and routes
* Manage drivers
* Monitor active trips
* View live bus locations
* Manage transport data

---

## 🗺️ Example Route

**Bicholim Court → AIEM College, Assagao**

**Bus:** 101
**Route Code:** `BIC-AIEM-01`

### Stops

1. Bicholim Court
2. Assonora Bus Stand
3. Cansa Board
4. Vision Hospital
5. Mapusa Court
6. Mapusa Bus Stand
7. AIEM College, Assagao

---

## 🏗️ System Overview

```text
                ┌─────────────────┐
                │     Driver      │
                │   Mobile App    │
                └────────┬────────┘
                         │
                    GPS Location
                         │
                         ▼
                ┌─────────────────┐
                │     Backend     │
                │   & Database    │
                └────────┬────────┘
                         │
             ┌───────────┴───────────┐
             │                       │
             ▼                       ▼
      ┌──────────────┐       ┌──────────────┐
      │  Passenger   │       │    Admin     │
      │   Website    │       │   Dashboard  │
      └──────────────┘       └──────────────┘
```

---

## 📱 Applications

MOVENTRA consists of three main interfaces:

| Interface             | Purpose                                 |
| --------------------- | --------------------------------------- |
| **Passenger App/Web** | Track buses, routes and ETAs            |
| **Driver App**        | Send live GPS location and manage trips |
| **Admin Dashboard**   | Manage and monitor the transport system |

---

## 🛠️ Technology

The project uses a combination of web, mobile and backend technologies.

* **Frontend:** React / TypeScript
* **Styling:** Tailwind CSS
* **Maps:** Map-based location visualization
* **Driver App:** Expo / React Native
* **Backend:** Supabase
* **Database:** PostgreSQL
* **Authentication:** Supabase Auth
* **Location:** Device GPS
* **Realtime Data:** Supabase Realtime

> The exact technologies may vary between development versions of the project.

---

## 📍 Live Location

MOVENTRA uses the driver's device GPS to provide the current bus location.

The driver application periodically sends location information to the backend while a trip is active.

This allows passengers to see the bus moving along its route instead of relying only on static schedules.

---

## ⏱️ ETA

MOVENTRA calculates estimated arrival information using the bus's current location and route information.

ETA is shown only when sufficient live location data is available. If the location is unavailable, stale or unreliable, the system avoids displaying a misleading ETA.

---

## 🎯 Goal

The goal of MOVENTRA is simple:

> **Make public transport easier to understand and easier to use.**

Many passengers in smaller cities and rural areas do not have access to reliable real-time information about where their bus is or when it will arrive.

MOVENTRA aims to bridge that information gap using accessible technology and real-time GPS tracking.

---

## 🔮 Future Scope

Possible future improvements include:

* Support for more routes and buses
* Better route-based ETA calculation
* Transport analytics
* Service and trip history
* Improved offline support
* Transport operator integration
* Passenger feedback and reporting
* Expansion to additional cities

---




## 🧪 Project Status

**Development / Prototype**

MOVENTRA is currently being developed and tested as a real-time public transport tracking solution.

---

## 🤝 Contributors

Jonathan De Sa
Arnav Singh
Yash Gaonkar
Tanisha Sawant
Mihir Kesarkar

---

## 📄 License

This project is currently intended for educational and project-development purposes.

A formal open-source license can be added when the project is ready for public contribution.

---

## 🚌 MOVENTRA

**Move smarter. Know your bus.**
