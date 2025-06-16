# Automatic Medicine Dispenser

An IoT-based smart device designed to automate medication delivery, ensuring timely and accurate dosage—especially useful for elderly or chronically ill patients.

## Project Overview

This project uses embedded systems and IoT to:
- Dispense medicine at scheduled intervals
- Alert users through buzzers/LEDs
- Ensure dose compliance
- Prevent missed or duplicate doses

## Features

- Timed medication alerts
- Automatic dispensing mechanism
- Remote control and monitoring (optional upgrade via mobile or web interface)
- Emergency alert or refill notification
- SOS button in case of emergencies to alert close contacts and doctor

## Tech Stack

- **Microcontroller:** ESP32 Wroom
- **Sensors & Modules:** RTC module, Servo motor, Buzzer, IR sensor
- **Connectivity:** Wi-Fi module (via ESP32) for remote features, GSM module
- **Code:** C/C++ (Arduino IDE)
- **UI:** Mobile app with FlutterFlow, Figma for wireframing and deployment and MQTT connection using Firebase.

