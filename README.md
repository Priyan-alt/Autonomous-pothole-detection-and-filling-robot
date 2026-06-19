#Autonomous Pothole Detection and Filling Robot

## Overview

Road potholes are a major cause of accidents, vehicle damage, and traffic congestion. Traditional pothole repair methods are time-consuming and require significant manual effort.

This project presents an Autonomous Pothole Detection and Filling Robot that continuously monitors road surfaces using ultrasonic sensing technology. When a pothole is detected, the robot automatically stops and activates a servo-controlled filling mechanism to perform temporary road repair.

The project demonstrates the integration of embedded systems, robotics, sensor technology, and automation for smart road maintenance applications.

---

## Features

✔ Autonomous pothole detection

✔ Real-time road surface monitoring

✔ Ultrasonic sensor-based depth measurement

✔ Automatic pothole filling mechanism

✔ Servo-controlled hopper gate

✔ DC motor-based navigation

✔ Buzzer alert system

✔ Low-cost embedded implementation

---

## Components Used

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- L293D Motor Driver
- DC Motors with Gearbox
- Servo Motor
- Buzzer
- Hopper with Sand/Filling Material
- RC Car Chassis
- Battery Pack

---

## Working Principle

1. Robot moves continuously on the road surface.
2. Ultrasonic sensor measures the distance between robot and road.
3. Arduino continuously processes distance readings.
4. If a sudden increase in distance is detected:
   - A pothole is identified.
5. Robot stops above the pothole.
6. Servo motor opens hopper gate.
7. Sand is released into the pothole.
8. Filling operation completes.
9. Servo closes hopper gate.
10. Robot resumes movement.

---

## System Architecture

Road Surface

↓

Ultrasonic Sensor

↓

Arduino Uno

↓

Decision Algorithm

↓

Motor Control + Servo Control

↓

Pothole Filling Mechanism

↓

Continue Navigation

---

## Hardware Connections

### Ultrasonic Sensor

- VCC → 5V
- GND → GND
- TRIG → D6
- ECHO → D5

### Servo Motor

- Signal → D4
- VCC → 5V
- GND → GND

### Buzzer

- Positive → D2
- Negative → GND

### Motor Driver (L293D)

- IN1 → D10
- IN2 → D11
- ENA → D9

---

## Applications

- Smart City Infrastructure
- Automated Road Maintenance
- Municipal Road Monitoring
- Highway Maintenance
- Infrastructure Automation

---

## Advantages

- Reduces manual labour
- Improves worker safety
- Faster pothole repair
- Low-cost implementation
- Scalable design
- Suitable for smart cities

---

## Future Enhancements

- GPS Integration
- IoT Monitoring Dashboard
- AI-based Vision Detection
- Real-time Data Upload
- Cloud Analytics
- Autonomous Navigation

---

## Team Members

- Pranjal Singh
- Mellimpudi Bhuvana
- Aditya Bhardwaj
- B Priyadarshan
- Navya Sinha

---

## My Contribution

- Hardware assembly
- Documentation and reporting

---
