# Distributed Smart Car System

## Overview
This project implements a distributed smart robotic car using Raspberry Pi, ESP32, and Arduino UNO.  
Each controller is assigned a dedicated responsibility to ensure modularity, stability, and real-time performance.

The project focuses on real-world embedded system challenges such as voltage-level mismatches, power distribution, serial communication stability, and multi-controller synchronization.

---

## Why a Distributed Architecture?
Instead of using a single controller, the system is divided into three logical layers:

- **Raspberry Pi** – Vision processing and decision logic  
- **ESP32** – Wi-Fi communication and signal-based data handling  
- **Arduino UNO** – Real-time motor control and obstacle avoidance  

This approach reflects how real autonomous systems are designed and debugged in industry environments.

---

## Key Features
- Motion detection using Raspberry Pi camera  
- Face recognition using live video feed  
- Obstacle avoidance using ultrasonic sensors  
- Wi-Fi communication and RSSI measurement via ESP32  
- Modular and scalable system design  

---

## Engineering Challenges Solved
- 5V (Arduino) ↔ 3.3V (ESP32) logic-level mismatch  
- Centralized power distribution without random resets  
- Serial communication flooding and timing issues  
- Sensor interference during servo-based scanning  
- CPU load optimization during continuous video processing  

---

## Project Status
The system successfully demonstrates modular integration and real-world embedded debugging.
Full autonomous navigation using wireless commands is under refinement.

---

## Documentation
- System architecture and wiring diagrams are available in the `docs/` folder  
- Controller-specific explanations are provided inside each module folder  

---

## Future Enhancements
- ESP32-only motor control architecture  
- 360° obstacle awareness using additional sensors  
- Face-recognition-triggered navigation  
- RSSI-based indoor navigation  

---

## Note
This repository documents a complete end-to-end project developed through extensive local hardware testing and iterative debugging.
