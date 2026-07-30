# Automated IoT-Based Drainage Monitoring and Solid Waste Management

A complete IoT project demonstrating **Arduino programming**, **sensor integration**, **real-time monitoring**, and **IoT dashboard visualization**.  
This repository showcases hardware + software implementation, simulation in Java, and cloud integration using ThingSpeak/Blynk.

---

## 📚 Contents
🔹 Arduino Code (`drainage_monitor.ino`) – Ultrasonic + Gas sensor monitoring  
🔹 Java Simulation (`DrainageMonitoring.java`) – Console-based simulation of sensor logic  
🔹 IoT Integration (`iot_integration.ino`) – ESP8266/NodeMCU code for ThingSpeak dashboard  
🔹 Documentation (`project_report.pdf`, `presentation.pptx`) – Project report and slides  
🔹 README.md – Project overview and usage guide  

---

## 🚀 Project: IoT Drainage Monitoring System

### 📄 Description
This project addresses urban drainage challenges like **blockages, overflow, and toxic gas hazards**.  
It uses **IoT sensors, Arduino, and cloud dashboards** to provide **real-time monitoring and automated alerts** for timely intervention.

---

### ✨ Features
- 🌊 Measure wastewater levels using ultrasonic sensors  
- 🧪 Detect toxic gases (Methane, Hydrogen Sulfide) with MQ sensors  
- 📟 Display live readings on LCD  
- 🔔 Trigger buzzer alerts for critical issues  
- 🌐 Send data to IoT dashboards (ThingSpeak/Blynk) for remote monitoring  

---

### 🧠 Concepts Used
- ⚡ Arduino Programming (C++)  
- 📡 IoT Cloud Integration (ThingSpeak/Blynk)  
- 🖥️ Java Simulation for sensor logic  
- 🔁 Real-time monitoring & alert systems  
- 🛠️ Hardware integration (Ultrasonic, Gas sensors, LCD, Buzzer)  

---

## 💡 How to Run

### Arduino Code
1. Open `drainage_monitor.ino` in Arduino IDE.  
2. Connect ultrasonic sensor, gas sensor, LCD, and buzzer to Arduino Uno.  
3. Upload the code and monitor readings via LCD + Serial Monitor.  

### Java Simulation
```bash
javac DrainageMonitoring.java
java DrainageMonitoring
