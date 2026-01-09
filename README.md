# Autonomous-Robot-Guidance-System-
This project implements an autonomous robot guidance system using a microcontroller-based finite state machine (FSM) to navigate an unknown path environment. The robot performs line following, junction detection, turning, and obstacle recovery through real-time sensor feedback and control logic.

The system integrates IR sensors and bumper switches with ADC sampling to make real-time navigation decisions. Motor control routines are used to regulate speed, direction, and recovery behavior, while calibrated sensor thresholds ensure stable and reliable operation under varying conditions.

System behavior was verified through iterative hardware testing and live demonstrations, validating correct state transitions, sensor thresholding, and recovery logic. The project emphasizes embedded systems development, hardware–software integration, and real-time control, reflecting practical constraints encountered in physical robotic systems.

Key Features

Finite State Machine (FSM)–based navigation logic

- Real-time sensor integration and ADC sampling

- DC motor control and recovery behavior

- Sensor calibration and threshold tuning

- Hardware-validated autonomous operation

Technologies & Tools

- Microcontroller programming (Embedded C / Assembly)

- IR sensors, bumper switches, ADCs

- Real-time control logic

- Hardware debugging and verification
