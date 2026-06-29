# 🔫 Laser Tag Game

An open-source **IoT-based Laser Tag Game** built using the **ESP8266** microcontroller. This project recreates the laser tag experience with real-time hit detection, player health tracking, OLED display support, and embedded game logic.

---

## 📖 Overview

The Laser Tag Game is an interactive embedded systems project where players use laser-equipped blasters to tag opponents. Each player wears a target module capable of detecting laser hits. The system keeps track of player health, displays game information on an OLED screen, and can be expanded with wireless communication for multiplayer gameplay.

This project is ideal for learning about:

* Embedded Systems
* Internet of Things (IoT)
* ESP8266 Programming
* Sensor Integration
* Game Development with Microcontrollers

---

## ✨ Features

* 🔫 Laser shooting mechanism
* 🎯 Real-time hit detection
* ❤️ Player health system
* 📟 OLED display for game status
* 🔊 Sound effects using a buzzer
* 💡 LED hit indicators
* 🔋 Battery-powered portable design
* ⚡ Low-latency response
* 🛠️ Modular and customizable code
* 🌐 Expandable for wireless multiplayer

---

## 🛠️ Hardware Requirements

| Component                       |    Quantity |
| ------------------------------- | ----------: |
| ESP8266 Development Board       |           1 |
| Laser Diode Module              |           1 |
| Laser Receiver / IR Receiver    |           1 |
| 0.96" OLED Display (I2C)        |           1 |
| Push Button (Trigger)           |           1 |
| Buzzer                          |           1 |
| Resistors                       | As Required |
| Battery Pack / Li-ion Battery   |           1 |
| Switch                          |           1 |
| Jumper Wires                    | As Required |
| Custom Gun Enclosure (Optional) |           1 |

---

## 💻 Software Requirements

* Arduino IDE
* ESP8266 Board Package
* USB Driver for ESP8266
* Git

---

## 📚 Required Libraries

Install the following libraries from the Arduino Library Manager:

* Adafruit GFX
* Adafruit SSD1306
* ESP8266WiFi *(optional for wireless features)*
* Wire

---

## 📂 Project Structure

```text
Laser-Tag-Game/
│
├── Gun/
│   ├── gun.ino
│   └── README.md
│
├── Vest/
│   ├── vest.ino
│   └── README.md
│
├── Circuit/
│   ├── circuit_diagram.png
│   └── wiring.pdf
│
├── Images/
│
├── Docs/
│
├── LICENSE
├── README.md
└── .gitignore
```

---

## 🎮 Gameplay

1. Turn on both the gun and target modules.
2. The OLED display shows the player's current health.
3. Press the trigger button to fire the laser.
4. When another player's receiver detects the laser, health decreases.
5. LEDs and the buzzer provide hit feedback.
6. The game ends when a player's health reaches zero.

---

## 🔌 Future Improvements

* Wi-Fi multiplayer support
* Team game modes
* Mobile companion app
* Online score leaderboard
* Recharge and respawn system
* OLED game menu
* Bluetooth support
* RGB lighting effects
* Sound packs
* Cloud data logging

---

## 🐞 Reporting Issues

If you find a bug or have a feature request, please open an issue with:

* A clear description
* Steps to reproduce
* Expected behavior
* Screenshots (if applicable)
  
---

## 👥 Contributors

This project was collaboratively developed by:

* **Arjun Kumar Giri**
* **Bishal Adhikari**
* **Milan Paudal**
* **Meshak Budhathoki**
* **Sajin Pradhan**
* **Smriti Gurung**
* **Urisha Khanal**
  

 All of the contributors worked together on the design, development, testing, and documentation of the Laser Tag Game.


---

## ⭐ Support

If you found this project helpful:

* ⭐ Star this repository
* 🍴 Fork the project
* 🐞 Report issues
* 💡 Suggest new features
* 🤝 Contribute to the project

Your support helps improve the project and encourages future development.

