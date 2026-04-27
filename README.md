
# 🚗 Real-Time Automotive Instrument Cluster using ARM & CAN Protocol

> 🚗 Designed with real automotive architecture concepts including ECU communication and CAN-based networking  
> ⚡ A real-time embedded system that simulates an automotive instrument cluster using ARM microcontroller and CAN communication for efficient vehicle data monitoring

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Embedded Systems-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Microcontroller-ARM-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Protocol-CAN-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 🌟 Project Overview

This project implements a **real-time automotive instrument cluster system** using an ARM microcontroller integrated with the **Controller Area Network (CAN) protocol**.

The system simulates how modern vehicles:
- Collect sensor data  
- Communicate between ECUs  
- Display critical information to the driver  

💡 The instrument cluster acts as a **central display unit**, showing parameters like speed, fuel, and system status. 

---

## 🎯 Objective

To design and develop a **real-time embedded system** that:
- Monitors vehicle parameters  
- Transmits data using CAN protocol  
- Displays information on an instrument cluster  

---

## 🧠 Problem Statement

Modern vehicles require:
- ⚡ Real-time communication  
- 🔄 Reliable data transfer  
- 🚗 Centralized monitoring system  

Traditional systems lack efficient communication.

✅ This project solves it using **CAN-based embedded architecture**

---

## ⚙️ System Workflow

Sensors → ARM Controller → CAN Transceiver → CAN Bus → Instrument Cluster Display

👉 The system uses CAN bus for communication between nodes, ensuring reliable and real-time data exchange.

---

🛠️ Hardware Components
🔹 ARM Microcontroller (LPC / similar)
🔹 CAN Controller (MCP2515)
🔹 CAN Transceiver (TJA1050)
🔹 Sensors (Temperature, Fuel, etc.)
🔹 LCD / Display Unit
🔹 Power Supply

---

## 💻 Software & Tools

- Embedded C  
- Keil uVision / Arduino IDE  
- CAN Libraries  
- Debugging Tools  

---

## 🔗 Communication Protocol (CAN)
- Message-based communication system
- High reliability & fault tolerance
- Used widely in automotive ECUs

👉 CAN enables multiple devices to communicate without a central computer.

---

✨ Key Features
🚗 Real-time vehicle data monitoring
🔄 CAN-based communication between nodes
📟 Instrument cluster display simulation
⚡ Fast and reliable data transfer
🔔 Alert system for abnormal values

---

## 📊 Parameters Monitored

- 🌡️ Temperature  
- ⛽ Fuel Level  
- 🚗 Speed  
- ⚙️ Engine Status  

---

📂 Project Structure
```bash
ARM_PROJECT_REAL_TIME_AUTOMOTIVE/
│
├── src/             # Embedded C source code
├── drivers/         # CAN & hardware drivers
├── docs/            # Documentation
├── assets/          # Images / diagrams
└── README.md
```

---
## 🚀 How It Works
- Sensors collect real-time vehicle data
- ARM controller processes the data
- Data is transmitted via CAN bus
- Instrument cluster displays output
- Alerts generated if abnormal conditions detected
---

## 💥 Why This Project Matters

- Demonstrates real-world automotive system design  
- Shows strong understanding of embedded systems  
- Implements CAN protocol used in industry  
- Reflects readiness for embedded/automotive roles  
---

## 🔮 Future Enhancements
- IoT integration for remote monitoring
- Mobile app dashboard
- Advanced digital cluster UI
- CAN FD implementation

---

## 🧠 Learnings
- Embedded C programming
- ARM microcontroller interfacing
- CAN protocol implementation
- Real-time system design
- Hardware-software integration

---

## 👨‍💻 Author

Mahidhar Reddy
🚀 Embedded Systems Developer | Backend Developer

💼 GitHub: https://github.com/Code-with-Mahidhar  
🔗 LinkedIn: https://www.linkedin.com/in/mahidhar-reddy-bandre-009894264  
📧 Email: mahidharreddybandre@gmail.com  
