# Single-Axis Auto-Adjusting Gimbal
An Arduino-based single-axis gimbal that uses an MPU-6050 inertial measurement unit to detect changes in orientation and automatically adjust a servo motor. This repository documents the development process, including early experiments, intermediate versions, and the final implementation in the main branch.

## Project Overview
The goal of this project was to create a simple stabilizing system that responds to the motion of its platform. The MPU-6050 measures the platform's movement, the Arduino processes the sensor readings, and the servo adjusts the gimbal along one axis to help maintain its desired position.

## Hardware Used
- Elegoo UNO R3
- MPU-6050
- Servo Motor
- Breadboard
