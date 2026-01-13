# ESP32 – Wireless Communication Layer

The ESP32 acts as the wireless communication bridge between the Raspberry Pi and Arduino UNO.

## Responsibilities
- Connect to Wi-Fi network  
- Measure RSSI signal strength  
- Relay navigation commands to Arduino via serial communication  

## Engineering Challenges
- Voltage-level mismatch between Arduino (5V) and ESP32 (3.3V)  
- Serial communication instability due to command flooding  

## Solutions Implemented
- Resistor voltage divider for safe RX communication  
- Controlled command transmission intervals  

The ESP32 layer significantly improved system scalability and wireless control capability.
