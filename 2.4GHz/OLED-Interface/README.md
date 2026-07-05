# 2.4GHz OLED Interface

> ESP8266-based 2.4GHz wireless security research interface featuring a 0.96-inch OLED display, push-button navigation, battery-powered operation, and an embedded user interface for wireless networking demonstrations.

---

# 📖 Overview

The OLED Interface is a portable embedded implementation designed for wireless networking research and educational demonstrations using the ESP8266 microcontroller.

Unlike a traditional serial-monitor interface, this project provides a standalone graphical interface through a 0.96-inch OLED display. Navigation is performed using three tactile push buttons, allowing users to interact with the device without requiring a computer after programming.

The compact hardware design makes the project suitable for learning embedded systems, Wi-Fi communication, OLED graphics, GPIO programming, battery-powered devices, and interface design.

This project is intended for students, makers, embedded developers, and cybersecurity learners who want to explore Wi-Fi capable microcontrollers in a practical way.

---

# 🎯 Objectives

The project was developed to demonstrate:

- Embedded user interface development
- ESP8266 Wi-Fi capabilities
- OLED graphics programming
- GPIO button navigation
- Battery-powered embedded systems
- Wireless networking concepts
- Educational security demonstrations
- Portable embedded hardware design

---

# ✨ Features

- 2.4GHz Wi-Fi support
- Portable battery-powered design
- 0.96-inch OLED graphical interface
- Three-button navigation system
- Standalone operation
- Real-time menu interface
- Compact hardware
- Low power consumption
- Open-source implementation

---

# 🛠 Hardware Components

| Component | Description |
|-----------|-------------|
| ESP8266 Development Board | Main microcontroller with integrated Wi-Fi |
| 0.96" OLED Display (I²C) | Graphical user interface |
| 3 × Push Buttons | Menu navigation (Up, Down, OK) |
| 3.7V Li-ion/LiPo Battery | Portable power source |
| TP4056 Type-C Charging Module | Battery charging and protection |
| NeoPixel LED (Optional) | Status indication |
| Breadboard / PCB | Circuit assembly |
| Jumper Wires | Connections |

---

# ⚙ Hardware Connections

## OLED Display

| OLED Pin | ESP8266 |
|----------|---------|
| VCC | 3.3V |
| GND | GND |
| SDA | D2 (GPIO4) |
| SCL | D1 (GPIO5) |

---

## Navigation Buttons

| Button | ESP8266 Pin |
|---------|-------------|
| UP | D5 (GPIO14) |
| DOWN | D6 (GPIO12) |
| OK | D7 (GPIO13) |

---

## Status LED

| Device | ESP8266 Pin |
|---------|-------------|
| NeoPixel | D4 (GPIO2) |

---

# 🔋 Power System

The project is powered using a rechargeable 3.7V Li-ion/LiPo battery.

Charging is handled by a TP4056 Type-C charging module with integrated battery protection, providing:

- Over-charge protection
- Over-discharge protection
- Short-circuit protection
- Safe battery charging

This enables completely portable operation without requiring continuous USB power.

---

# 📂 Project Structure

```text
OLED-Interface/
│
├── circuit/
│   ├── Circuit Diagram
│   └── Wiring Images
│
├── code/
│   ├── Arduino Source Code
│   └── Libraries
│
├── hardware/
│   ├── Components List
│   ├── Pinout
│   └── Hardware Notes
│
├── images/
│   ├── Device Photos
│   ├── OLED Screens
│   └── Build Images
│
├── resources/
│   ├── Datasheets
│   ├── References
│   └── Documentation
│
├── videos/
│   └── Demonstration Videos
│
└── README.md
```

---

# 📁 Folder Description

### 📂 circuit

Contains wiring diagrams, circuit schematics, and connection references used for assembling the hardware.

---

### 💻 code

Contains the Arduino source code, project libraries, configuration files, and firmware required for programming the ESP8266.

---

### 🔧 hardware

Includes the hardware bill of materials (BOM), component information, module specifications, and pin configuration.

---

### 📷 images

Contains photographs of the completed hardware, OLED interface screenshots, PCB images, and project assembly pictures.

---

### 📚 resources

Provides useful reference materials including datasheets, documentation, library references, and learning resources.

---

### 🎥 videos

Contains demonstration videos showcasing hardware operation and interface functionality.

---

# 💻 Development Environment

- Arduino IDE
- ESP8266 Board Package
- U8g2 / SSD1306 OLED Library
- Adafruit GFX
- Git
- GitHub

---

# 📚 Learning Topics

This project demonstrates:

- ESP8266 Programming
- Embedded Systems
- OLED Graphics
- GPIO Programming
- Battery Management
- Wi-Fi Networking
- User Interface Design
- Portable Embedded Devices

---

# 📈 Future Improvements

- Improved menu animations
- Battery level indicator
- Settings menu
- OLED themes
- OTA firmware updates
- Enhanced interface responsiveness

---

# ⚠ Disclaimer

This project is intended solely for educational purposes, research, and authorized security testing.

Only perform testing on networks and systems that you own or for which you have explicit authorization. The author is not responsible for misuse of this project.

---

# 👨‍💻 Author

**Manoj A N**

Founder & CEO — **MR-BotX**

IoT Engineering Student

Passionate about Robotics • Embedded Systems • IoT • AI • Cybersecurity
