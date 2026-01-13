# Arduino – Motor Control and Obstacle Avoidance

The Arduino UNO is responsible for real-time motor control and sensor-based obstacle avoidance.

## Responsibilities
- Control DC motors via L298N motor driver  
- Read ultrasonic sensor distance values  
- Rotate servo-mounted ultrasonic sensor  
- Execute obstacle avoidance logic with low latency  

## Why Arduino?
Arduino was chosen for its stable real-time performance and predictable GPIO behavior, which is critical for motor control and sensor timing.

## Limitations
- Limited sensor coverage (approx. 120°)  
- No high-level decision-making  
- Dependent on external controller for navigation commands  

These limitations were intentionally accepted to maintain real-time reliability.
