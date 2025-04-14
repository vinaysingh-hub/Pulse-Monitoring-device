# Pulse-Monitoring-device


This project is a compact Pulse Monitoring Device designed using ESP32 and a Pulse Sensor, with a custom PCB layout created using KiCad. The aim is to build a low-cost, real-time heart rate monitoring system with basic control features and future expandability.

## Features

- Real-time pulse monitoring
- Custom-designed PCB layout
- Switch-controlled operation
- Compact and low-power design
- Scope for wireless data transmission (optional via ESP32)

## Hardware Components Used

| Component       | Description                                  |
|----------------|----------------------------------------------|
| ESP32          | Microcontroller with Wi-Fi and BLE support   |
| Pulse Sensor   | Heartbeat monitoring sensor                  |
| Switch         | Push button for control                      |
| Resistors/Capacitors | Basic supporting components             |
| Custom PCB     | Designed using KiCad                         |

## Software Tools Used

- KiCad – for schematic and PCB layout design
- Arduino IDE – for firmware development
- PulseSensor Playground Library – for reading pulse data from the sensor

## Working Principle

The Pulse Sensor detects the heartbeat based on changes in light absorption through the skin. This analog signal is fed to the ESP32, which processes the data to calculate the Beats Per Minute (BPM). A push-button switch is used to control data logging or device power.



## How to Use

1. Assemble the hardware components on the custom PCB.
2. Upload the firmware (`pulse_monitor.ino`) to the ESP32 using Arduino IDE.
3. Power on the device and place the Pulse Sensor on the fingertip or earlobe.
4. Monitor the pulse data via serial monitor or an optional OLED display.

## Future Enhancements

- Integration of OLED display for visual BPM output
- Bluetooth/Wi-Fi support for remote monitoring
- Mobile app connectivity for data logging and visualization

