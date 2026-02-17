# 🌡 Embedded Temperature & Humidity Monitoring

![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Arduino-orange)
![Language](https://img.shields.io/badge/language-C++-blue)
![Status](https://img.shields.io/badge/status-educational-green)

An embedded data acquisition system using the DHT11 sensor for real-time temperature and humidity monitoring with structured documentation and Git workflow discipline.

---

## 📑 Table of Contents

- Project Overview
- Hardware Requirements
- Software Requirements
- Wiring Connections
- DHT11 Pinout
- Code Structure
- Documentation Requirement
- Submission Requirements
- Future Improvements
- License

---

## 🚀 Project Overview

This project demonstrates environmental monitoring using the DHT11 sensor and Arduino (Uno R4 recommended).

The system:

- Reads temperature data
- Reads humidity data
- Validates sensor readings
- Displays structured serial output
- Follows professional Doxygen documentation standards
- Implements Git-based development workflow

This project introduces:

- Sensor interfacing
- Data acquisition systems
- Embedded programming discipline
- Structured documentation practices

---

## 🔧 Hardware Requirements

- Arduino Uno R4
- DHT11 Sensor
- 10kΩ Pull-up resistor (if required)
- Breadboard
- Jumper wires
- USB cable

---

## 💻 Software Requirements

- Arduino IDE
- Adafruit DHT Library
- Git
- GitHub Account

---

## 🔌 Wiring Connections

| DHT11 Pin | Arduino |
|-----------|----------|
| VCC       | 5V       |
| GND       | GND      |
| DATA      | Pin 2    |

⚠ Ensure proper wiring before powering the board.

---

## 🔎 DHT11 Pinout

- VCC → Power (3.3V–5V)
- DATA → Digital Pin
- GND → Ground

Operating Voltage: 3.3V – 5V

---

## 🧠 Code Structure

The system:

1. Initializes Serial communication
2. Initializes DHT sensor
3. Reads humidity
4. Reads temperature
5. Validates readings
6. Prints structured output

---

## 📚 Documentation Requirement

Students must include:

- File-level Doxygen documentation block
- Function documentation for:
  - `setup()`
  - `loop()`
- Required tags:
  - `@file`
  - `@brief`
  - `@author`
  - `@date`

---

## 📊 Submission Requirements

- Minimum 5 meaningful commits
- Proper commit message format
- All TODO tasks completed
- Doxygen documentation included
- Code must compile successfully

---

## 🔮 Future Improvements

- Replace delay() with millis()
- Add LCD integration
- Log data to SD card
- Cloud integration (IoT)
- Threshold-based alert system

---

## 📜 License

This project is licensed under the MIT License.
