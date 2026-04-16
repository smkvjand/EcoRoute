# 🌿 EcoRoute

### Smart Environmental Navigation System

EcoRoute is an intelligent navigation application that helps users choose **cleaner, quieter, and healthier routes** by integrating real-time environmental data with mapping technology.

---

## 🚀 Problem Statement

Traditional navigation systems optimize for **distance and time**, but ignore environmental factors such as:

* Air pollution (AQI)
* Noise pollution
* Pollen levels

This can negatively impact health, especially for individuals with respiratory conditions.

---

## 💡 Solution

EcoRoute introduces **environment-aware routing**, allowing users to:

* Avoid polluted zones
* Choose healthier paths
* Receive real-time environmental alerts

---

## 🧠 Key Features

### 🗺️ Smart Navigation

* Interactive map-based interface
* Route suggestions based on environmental conditions

### 🌫️ Pollution Monitoring

* Air Quality Index (AQI) integration
* Noise level detection using device microphone
* MQ135 sensor integration for real-world data collection

### 🌸 Pollen Mode

* Toggle to consider pollen levels while routing

### 🔥 Heatmap Visualization

* Visual representation of pollution zones
* Color-coded (Green → Safe, Red → Hazardous)

### 🎯 Eco Score

* Each route is assigned a score based on pollution exposure

### 🔔 Smart Alerts

* Notifications when entering high pollution zones
* Alternative route suggestions

---

## 🏗️ System Architecture

```text
User Device (Android App)
        ↓
Firebase Backend (Real-time Data Sync)
        ↓
Processing Layer (Pollution Analysis & Routing Logic)
        ↓
External APIs (AQI, Pollen, Weather)
```

---

## 🧰 Tech Stack

### 📱 Frontend

* Android (JAVA) and IOS
* Material Design UI

### ☁️ Backend

* Firebase (Realtime Database / Firestore)
* Firebase Cloud Messaging (Notifications)

### 🌍 APIs

* Google Maps Platform (Maps & Routing)
* OpenWeather API (Air Quality Data)
* Pollen API (optional integration)

### 🔧 Hardware

* MQ135 Gas Sensor (Air Quality)
* Mobile Microphone (Noise Detection)

---

## 📊 Data Sources

* Real-time sensor data (user + hardware)
* External environmental APIs
* Crowd-sourced pollution inputs

---

## ⚙️ Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/ecoroute.git
```

2. Open in Android Studio

3. Add your API keys:

   * Google Maps API Key
   * AQI / Weather API Key

4. Enable permissions:

   * Location
   * Internet

5. Run the application

---

## 🔐 Security

* API keys are restricted and secured
* Firebase rules configured for controlled access

---

## 📈 Future Enhancements

* AI-based pollution prediction
* Multi-user real-time heatmaps
* Wearable device integration
* Cross-platform (iOS + Web) support

---

## 🎯 Vision

To transform navigation systems into **health-aware intelligent platforms** that prioritize user well-being alongside efficiency.

---

## 👨‍💻 Contributors

* SriMuraliKrishna(web design, project lead, structure design , map layers, route alogritm, System architecture,data collection)
* Sujay(Report design, Presentation support maps api routes,data collection)
* Ankita
* Jaidev
* Sarayu
* Gaurav
* Harshini
* Mentored by: Dr. Anurag Srivatsav
Submitted to Anurag Srivatsava Sir for Evaluation for Subject EES Semester 2 IIITM Gwalior.
---

## 📌 Note

This project is developed as part of an academic initiative at IIITM Gwalior, focusing on combining environmental science with modern technology.

---
