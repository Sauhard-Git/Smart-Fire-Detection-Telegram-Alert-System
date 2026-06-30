<div align="center">

# 🔥 Smart Fire Detection & Telegram Alert System

### *An IoT-Based Fire Safety Solution using ESP8266 & Telegram Bot*

![ESP8266](https://img.shields.io/badge/ESP8266-NodeMCU-blue?style=for-the-badge)
![IoT](https://img.shields.io/badge/IoT-Telegram%20Alert-success?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-IDE-00979D?style=for-the-badge&logo=arduino)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

</div>

---

# 📖 Overview

The **Smart Fire Detection & Telegram Alert System** is an IoT-based safety project designed to detect fire in real time and instantly notify users through **Telegram**.

Built using **ESP8266 NodeMCU**, a **Flame Sensor**, and the **Telegram Bot API**, this system continuously monitors its surroundings. Whenever a fire is detected, it immediately sends an emergency alert to the user's Telegram account, enabling a quick response during critical situations.

This project demonstrates the practical application of **Embedded Systems**, **IoT**, **Wireless Communication**, and **Real-Time Safety Automation**.

---

# ✨ Features

- 🔥 Real-Time Fire Detection
- 📲 Instant Telegram Notifications
- 🌐 Wi-Fi Enabled Monitoring
- ⚡ ESP8266 NodeMCU Based
- 💻 Serial Monitor Status Updates
- 🚨 Emergency Alert System
- 📡 IoT-Based Communication
- 🔋 Low Power Consumption
- 🛠 Easy to Customize & Expand

---

# 🛠 Components Used

| Component | Quantity |
|-----------|:--------:|
| ESP8266 NodeMCU | 1 |
| Flame Sensor Module | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |
| USB Cable | 1 |
| Wi-Fi Network | 1 |

---

# 🔌 Circuit Connections

## 🔥 Flame Sensor

| Flame Sensor Pin | ESP8266 Pin |
|------------------|-------------|
| OUT | D5 |
| VCC | 3.3V |
| GND | GND |

---

# ⚙️ Working Principle

```text
🔥 Fire Detected
        │
        ▼
📡 Flame Sensor Sends Signal
        │
        ▼
🧠 ESP8266 Processes Data
        │
        ▼
🌐 Connects via Wi-Fi
        │
        ▼
📲 Telegram Bot Sends Alert
        │
        ▼
🚨 User Receives Emergency Notification
```

---

# 💻 Software Used

- Arduino IDE
- Telegram Bot API

---

# 📚 Libraries Used

```cpp
#include <ESP8266WiFi.h>
#include <WiFiClientSecure.h>
#include <UniversalTelegramBot.h>
#include <ArduinoJson.h>
```

---

# 🚀 Future Improvements

- 🌫 Smoke Sensor (MQ-2)
- 🌡 Temperature Monitoring
- 🔊 Buzzer Alarm
- 💡 Emergency LED Indicator
- ☁ Firebase Cloud Logging
- 📱 Mobile Dashboard
- 📍 GPS-Based Location Sharing
- 📈 Live Sensor Analytics
- 🏠 Multi-Room Fire Detection

---

# 🎓 Learning Outcomes

- ESP8266 Programming
- IoT Communication
- Telegram Bot API
- Wi-Fi Networking
- Fire Sensor Interfacing
- HTTP Requests
- Embedded Systems
- Real-Time Alert Systems

---

# 📸 Project Preview

> Add your project images here.

### 📷 Hardware Setup

<p align="center">
<img src="Images/setup.jpg" width="800">
</p>

---

### 💻 Serial Monitor

<p align="center">
<img src="Images/serial_monitor.jpg" width="800">
</p>

---

### 📲 Telegram Alert

<p align="center">
<img src="Images/telegram_alert.jpg" width="350">
</p>

---

### 🎥 Demo Video

<p align="center">
<img src="Images/demo.gif" width="900">
</p>

---

# 🤝 Contributing

Contributions are always welcome!

⭐ Star this repository

🍴 Fork the repository

🔧 Create a new branch

🚀 Submit a Pull Request

---

# 👨‍💻 Author

## Sauhard Agnihotri

**Electronics & Communication Engineering Student**

### Interests

- 🤖 Embedded Systems
- 🌐 Internet of Things (IoT)
- 🔥 Smart Safety Systems
- ⚡ Arduino & ESP8266
- 📡 Wireless Communication
- 💡 Electronics & Automation

---

# ⭐ Show Your Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

<div align="center">

## ❤️ Thanks for Visiting!

**If you like this project, don't forget to leave a ⭐ on GitHub!**

</div>