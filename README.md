# Pulse-Monitoring-device

# 💓 Pulse Monitoring Device using ESP32

This project is a compact **Pulse Monitoring Device** designed using **ESP32** and a **Pulse Sensor**, with a custom PCB layout created using **KiCad**. The objective is to create a wearable or portable health monitoring system capable of detecting and displaying heart pulse data.

## 🔧 Features
- Real-time pulse monitoring
- Compact custom-designed PCB
- Low power consumption
- Start/Stop switch control
- Future support for Bluetooth/Wi-Fi data transmission (optional via ESP32)

---

## 📦 Hardware Components Used

| Component       | Description                                  |
|----------------|----------------------------------------------|
| ESP32          | Microcontroller with Wi-Fi and BLE support   |
| Pulse Sensor   | Heartbeat monitoring sensor                  |
| Switch         | Push button to control data logging/power    |
| Resistors/Capacitors | Basic supporting components             |
| Custom PCB     | Designed using KiCad                         |

---

## 🖥️ Software Tools Used

- [KiCad](https://www.kicad.org/) – for PCB design
- Arduino IDE – for programming ESP32
- PulseSensor Playground Library – for reading pulse data

---

## 🧠 Working Principle

The **Pulse Sensor** detects heartbeats via changes in light absorption through skin and sends analog signals to ESP32. The microcontroller processes the signal and calculates Beats Per Minute (BPM). The device can be powered on/off using a simple switch.

---



