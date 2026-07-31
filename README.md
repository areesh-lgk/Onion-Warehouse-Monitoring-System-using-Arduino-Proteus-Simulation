# 🧅 Onion Warehouse Monitoring System using Arduino & Proteus Simulation

## 📌 Overview

The **Onion Warehouse Monitoring System** is an Arduino-based embedded system designed to monitor the environmental conditions inside an onion storage warehouse. The project uses multiple sensors to continuously measure temperature, humidity, gas concentration, and fire hazards, helping prevent onion spoilage and ensuring safe storage conditions.

The complete system is designed and tested in **Proteus Simulation**, allowing users to validate the hardware and firmware before implementing it on physical hardware.

---

## 🎯 Objectives

* Monitor warehouse environmental conditions in real time.
* Detect abnormal temperature and humidity levels.
* Identify gas leakage or harmful gas accumulation.
* Detect fire or flame hazards.
* Display sensor readings on an LCD.
* Provide early warning through alarms for unsafe conditions.

---

## ✨ Features

* 🌡️ Real-time Temperature Monitoring
* 💧 Humidity Detection
* 🔥 Fire/Flame Detection
* 💨 Gas Leakage Monitoring
* 📟 LCD Display for Live Sensor Values
* 🚨 Automatic Alarm/Buzzer Alerts
* ⚡ Arduino-based Embedded System
* 🖥️ Fully Simulated in Proteus

---

## 🛠 Hardware Components

* Arduino Uno
* DHT11 Temperature & Humidity Sensor
* MQ Gas Sensor
* Flame Sensor
* LCD Display (16×2)
* Buzzer
* LEDs
* Resistors
* Connecting Wires
* Power Supply

---

## 💻 Software Used

* Arduino IDE
* Proteus Professional
* Embedded C

---

## 📂 Project Structure

```text
Onion-Warehouse-Monitoring/
│
├── Arduino_Code/
│   └── Onion_Warehouse_Monitoring.ino
│
├── Proteus_Simulation/
│   ├── Warehouse_Monitoring.pdsprj
│   └── Circuit_Design.dsn
│
├── Images/
│   ├── Circuit.png
│   └── Output.png
│
└── README.md
```

---

## ⚙️ Working Principle

1. The DHT11 sensor measures temperature and humidity.
2. The MQ gas sensor monitors harmful gases.
3. The flame sensor detects fire hazards.
4. Arduino processes all sensor inputs.
5. Live values are displayed on the LCD.
6. If any parameter exceeds the predefined threshold:

   * The buzzer is activated.
   * Warning LEDs turn ON.
   * Users are alerted immediately.

---

## 📊 Applications

* Onion Storage Warehouses
* Agricultural Cold Storage
* Food Storage Facilities
* Smart Farming
* Warehouse Safety Monitoring
* Industrial Storage Units

---

## 🚀 Future Enhancements

* IoT-based Remote Monitoring
* ESP32 Wi-Fi Integration
* Mobile Application Dashboard
* Cloud Data Logging
* SMS/Email Alerts
* Predictive Analytics using AI
* Automatic Ventilation Control

---

## 📸 Simulation

Add screenshots of your Proteus simulation here.

```text
Images/
├── Circuit.png
├── Simulation_Output.png
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Onion-Warehouse-Monitoring.git
```

2. Open the `.ino` file using **Arduino IDE**.
3. Compile the code.
4. Open the Proteus project (`.pdsprj`).
5. Load the generated HEX file into the Arduino Uno.
6. Run the simulation.

---

## 📚 Technologies Used

* Embedded Systems
* Arduino Programming
* Embedded C
* Proteus Simulation
* Sensor Interfacing
* Environmental Monitoring

---

## 🤝 Contributions

Contributions, improvements, and suggestions are welcome. Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Areesh A**

* Electronics & Communication Engineer
* Embedded Systems & IoT Enthusiast
* GitHub: https://github.com/areesh-lgk
* LinkedIn: https://www.linkedin.com/in/areesh-a-2a038a3ab

---

⭐ If you found this project useful, don't forget to **Star** this repository!
# Onion-Warehouse-Monitoring-System-using-Arduino-Proteus-Simulation
