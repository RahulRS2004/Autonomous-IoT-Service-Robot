# 🤖 Smart IoT Service Robot

## 📌 Project Overview
This project demonstrates a Smart IoT Service Robot with:
- Autonomous Navigation
- Follow Mode
- Manual WiFi Control
- Obstacle Detection
- Safety Control

The robot is developed using ESP8266, ultrasonic sensing, and IoT-based wireless communication.

---

# ⚙️ Features
- Manual Control using Web Browser
- Autonomous Obstacle Avoidance
- Follow Mode
- Real-Time Distance Monitoring
- Wireless IoT Control
- Rule-Based AI Decision Making

---

# 🧩 Components Used
- ESP8266 NodeMCU
- L298N Motor Driver
- HC-SR04 Ultrasonic Sensor
- DC Motors
- Mecanum Wheel Chassis
- Battery Pack
- Jumper Wires
- Power Switch

---

# 🔌 Hardware Connections

## ESP8266 ↔ L298N

| ESP8266 Pin | L298N Pin |
|------------|-----------|
| D1 (GPIO5) | IN1 |
| D2 (GPIO4) | IN2 |
| D5 (GPIO14) | IN3 |
| D6 (GPIO12) | IN4 |
| 3V3 | ENA |
| 3V3 | ENB |
| GND | GND |
IF ENA and ENA has JUMPER CAPS THEN ABOVE CONNECTION OF ENA and ENB is not needed

---

## Ultrasonic Sensor

| Sensor Pin | ESP8266 Pin |
|------------|-------------|
| TRIG | D7 |
| ECHO | D8 |
| VCC | 5V |
| GND | GND |

---

# 🌐 Working Principle

The system operates on a closed-loop architecture involving sensing, processing, decision-making, and actuation. The ultrasonic sensor continuously measures environmental distance data, which is processed by the ESP8266 microcontroller. Based on the selected operating mode and sensor feedback, the controller generates appropriate control signals for the motor driver, enabling autonomous navigation and intelligent movement.

---

# 🧠 AI-Based Concept

The robot uses rule-based AI decision-making logic.

Example:
- If obstacle detected → Change direction
- If path clear → Move forward

---

# 🚀 Modes of Operation

## Manual Mode
Controlled through WiFi web interface.

## Autonomous Mode
Robot detects obstacles and changes direction automatically.

## Follow Mode
Robot maintains distance from nearby object.

---

# 💻 Technologies Used
- Embedded Systems
- Robotics
- IoT
- ESP8266 Programming
- Wireless Communication
- Rule-Based AI

---

