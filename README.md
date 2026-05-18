# Smart Hospital Bed – Version 1
## Patient Presence Detection System

### Project Overview
This project is a Smart Hospital Bed system designed to detect whether a patient is present on the bed using an FSR402 pressure sensor and ESP32 microcontroller.

The pressure applied on the sensor changes its resistance, which is converted into a voltage signal using a voltage divider circuit with a 12kΩ resistor. The ESP32 reads this analog value and determines whether the bed is occupied or vacant. The status is displayed on an OLED display and can also be monitored through the serial monitor on a PC.

---

## Components Used
- ESP32 Development Board
- FSR402 Pressure Sensor
- 12kΩ Resistor
- OLED Display (I2C)
- Breadboard
- Jumper Wires
- USB Cable
- Monitor / PC

---

## Features
- Patient presence detection
- Real-time OLED display output
- Analog pressure sensing using voltage divider
- Serial monitor debugging and monitoring
- Compact and low-cost prototype design

---

## Working Principle
1. The FSR402 pressure sensor detects pressure applied on the bed.
2. The sensor and 12kΩ resistor form a voltage divider circuit.
3. ESP32 reads the analog voltage from the sensor.
4. The program checks whether the pressure crosses a threshold value.
5. The OLED display shows:
   - BED OCCUPIED
   - BED VACANT

---

## Block Diagrams (Version 1/Basic)
Block diagrams for:
- Overall System Architecture
- Sensor Interface
- Data Flow
- Hardware Connections

have been added to this repository.

---

## Demo Video
A short demonstration video of the project has been uploaded to this repository.

---

## Future Improvements
- Add DHT22 temperature and humidity monitoring
- Add motorized adjustment system
- Add IoT-based remote monitoring
- Add emergency alert system
- Add cloud data logging

---

## Project Updates

### 18 May 2026
- Added block diagrams.

---

## Author
Shreyash Shinde
ENTC Engineering Student
