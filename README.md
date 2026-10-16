# Arduino-Based-Intelligent-Dustbin

## 1. Project Overview

The **Arduino-Based Intelligent Dustbin** is an embedded systems project designed to automate the opening and closing of a dustbin lid using an ultrasonic sensor and a servo motor.

In a conventional dustbin, the user must manually open the lid to dispose of waste. This project explores a contactless alternative in which the system detects an object near the dustbin and uses a microcontroller to control the lid automatically.

The project uses an **Arduino Uno** as the main controller, an **HC-SR04 ultrasonic sensor** for distance measurement, and a **servo motor** to move the lid.

- **Project Category:** Embedded Systems, Arduino, Sensor Interfacing and Automation
- **Project Status:** Prototype Development and Documentation

## 2. Project Objectives

The main objectives of this project are:

- Develop a contactless dustbin lid-control system.
- Detect nearby objects using an ultrasonic sensor.
- Measure the distance between the sensor and the detected object.
- Process sensor readings using an Arduino Uno.
- Control a servo motor according to the detected distance.
- Understand microcontroller programming, sensor interfacing, and actuator control.

## 3. Components Required

| Component | Quantity | Function |
|---|---:|---|
| Arduino Uno | 1 | Processes sensor data and controls the servo motor |
| HC-SR04 Ultrasonic Sensor | 1 | Measures the distance to a nearby object |
| Servo Motor | 1 | Opens and closes the dustbin lid |
| Dustbin or Container | 1 | Provides the physical enclosure |
| Jumper Wires | As required | Connect the electronic components |
| USB Cable / Power Supply | 1 | Supplies power to the Arduino during testing |

## 4. Working Principle

1. **Object Detection:** The HC-SR04 sensor detects an object near the dustbin.
2. **Distance Measurement:** The sensor measures the distance by calculating the time taken for the ultrasonic echo to return.
3. **Data Processing:** The Arduino Uno compares the measured distance with a predefined threshold.
4. **Lid Opening:** If the object is within the specified distance, the Arduino commands the servo motor to open the lid.
5. **Automatic Closing:** After the programmed delay, the servo motor returns the lid to its closed position when the opening condition is no longer maintained.

## 5. Hardware Connections

| Component Pin | Arduino Uno Pin |
|---|---|
| HC-SR04 VCC | 5V |
| HC-SR04 GND | GND |
| HC-SR04 TRIG | Digital Pin 5 |
| HC-SR04 ECHO | Digital Pin 6 |
| Servo Signal | Digital Pin 7 |
| Servo VCC | Suitable regulated supply |
| Servo GND | Common GND |

**Note:** Verify the actual wiring and servo power requirements before testing.

## 6. Software Requirements

| Software / Library | Purpose |
|---|---|
| Arduino IDE | Writing, compiling and uploading the program |
| Arduino Servo Library | Controlling the servo motor |
| Arduino C/C++ | Programming the control logic |

## 7. Learning Outcomes

- Arduino programming and microcontroller fundamentals
- Ultrasonic sensor interfacing
- Distance measurement
- Servo motor control
- Digital input/output operations
- Basic hardware integration and troubleshooting

