Raspberry Pi and ESP32 Based Distributed Smart Car
Introduction

This project focuses on designing and implementing a distributed smart robotic car by integrating Raspberry Pi, ESP32, and Arduino UNO. Each controller is assigned a specific role to ensure modularity, stability, and easier debugging.

The system combines computer vision, wireless communication, and real-time motor control to simulate a real-world autonomous robotic platform.

Why Multiple Controllers?

Raspberry Pi handles vision and decision logic

ESP32 manages Wi-Fi communication and signal strength

Arduino ensures reliable real-time motor and sensor control

This separation prevents overloading a single controller and reflects real embedded system design practices.

System Architecture

📌 Architecture diagrams and wiring images are available in the docs/ folder.

Features

Motion detection using Raspberry Pi camera

Face recognition using live video feed

Obstacle avoidance using ultrasonic sensors

Wi-Fi-based command relay via ESP32

Modular and scalable system design

Project Status

The system successfully demonstrates modular integration and real-world embedded system challenges. Full autonomous navigation using wireless commands is under refinement.
