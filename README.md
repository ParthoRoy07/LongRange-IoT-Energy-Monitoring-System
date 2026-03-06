# LoRa-Based Industrial IoT Energy Monitoring System

This project implements a real-time Industrial IoT energy monitoring system using ESP microcontrollers, LoRa communication, and a Python Flask dashboard.

## Features

- Real-time voltage monitoring
- Temperature and humidity sensing
- Long-range wireless communication using LoRa
- Web dashboard for monitoring
- Remote relay control
- Serial communication between ESP and server

---

## System Architecture

Sensor Node (ESP + Sensors)
        ↓
LoRa Wireless Communication
        ↓
Gateway ESP
        ↓
USB Serial
        ↓
Python Flask Server
        ↓
Web Dashboard

---

## Tech Stack

Hardware
- ESP8266 / ESP32
- LoRa SX1278 module
- DHT11 / DHT22 sensor
- Voltage sensor
- Relay module

Software
- Arduino IDE
- Python
- Flask
- PySerial
- HTML / CSS / JavaScript

---

## Project Screenshots

### Hardware Prototype
![Prototype](images/prototype.jpg)

### Dashboard
![Dashboard](images/dashboard.png)

---

## Running the Dashboard

Install dependencies
pip install flask pyserial


Run server


python main.py


Open browser


http://localhost:9000


---

## Future Improvements

- Multi-node LoRa monitoring
- Cloud integration
- Mobile application
- PCB-based hardware design

---

## Author

Partho Roy  
Electronics & Computer Science Engineering  
KIIT University
