# 📦 Smart Warehouse Inventory Tracking Using RFID

## 📖 Overview

Smart Warehouse Inventory Tracking Using RFID is an Arduino-based IoT project designed to automate inventory identification and warehouse monitoring. The system uses RFID technology to identify items, an ultrasonic sensor to monitor shelf occupancy, and a servo motor to simulate automated warehouse gate control. The project aims to improve inventory accuracy, reduce manual effort, and demonstrate practical applications of embedded systems and IoT.

---

## ✨ Features

- 📌 RFID-based inventory identification
- 🚪 Automatic gate control using a servo motor
- 📏 Shelf occupancy monitoring using an ultrasonic sensor
- 🔔 Audible notifications through a buzzer
- 📊 Real-time inventory data displayed via Serial Monitor
- 🔧 Modular design for future IoT integration

---

## 🛠 Hardware Components

- Arduino Uno
- MFRC522 RFID Reader
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Buzzer
- Breadboard
- Jumper Wires
- USB Cable

---

## 💻 Software & Technologies

- Arduino IDE / PlatformIO
- Arduino C++
- SPI Library
- MFRC522 Library
- Servo Library

---

## ⚙️ Working

1. Power on the Arduino Uno.
2. Scan an RFID tag using the MFRC522 reader.
3. The system reads and verifies the RFID tag.
4. The servo motor opens the warehouse gate.
5. The buzzer confirms successful access.
6. The ultrasonic sensor measures shelf occupancy.
7. Inventory data is displayed through the Serial Monitor.

---

## 📂 Project Structure

```
Smart-Warehouse-Inventory-Tracking-Using-RFID/
│
├── warehouse_inventory.ino
├── README.md
├── images/
│   ├── setup.jpg
│   ├── working.jpg
│   └── output.png
├── circuit_diagram.png
└── LICENSE
```

---

## 📈 Future Enhancements

- Cloud database integration
- IoT dashboard for real-time monitoring
- Mobile application support
- Multiple RFID reader support
- Wi-Fi connectivity using ESP32
- Email and SMS notifications

---

## 🎯 Applications

- Smart Warehouses
- Inventory Management
- Logistics & Supply Chain
- Industrial Automation
- Educational IoT Projects

---

## 👨‍💻 Author

**Suthari Rithwik**

- 🎓 B.Tech CSE (AI & ML), Woxsen University
- 💡 Interested in Artificial Intelligence, Machine Learning, IoT, and Software Development

---

## ⭐ If you found this project useful, consider giving it a star!
