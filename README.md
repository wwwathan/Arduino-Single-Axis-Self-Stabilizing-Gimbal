# Single-Axis Auto-Adjusting Gimbal
An Arduino-based gimbal that uses an MPU-6050 to detect changes in orientation and adjust a servo motor along one axis. This project was developed for the Robotics Club Firmware Trial Project in Fall 2026.

## Hardware Used
- Elegoo UNO R3
- MPU-6050 accelerometer and gyroscope
- Servo motor
- Breadboard and jumper wires

## How It Works
The MPU-6050 measures the gimbal's movement. The Arduino processes the sensor data and adjusts the servo to compensate for changes in orientation. The repository includes the different stages of development, from early testing to the final implementation in the main branch.

## Setup
1. Open the final Arduino sketch in the Arduino IDE.
2. Install the required libraries, such as Wire and Servo.
3. Connect the hardware according to the wiring table.
4. Select Arduino Uno and the correct serial port.
5. Upload the firmware and test the gimbal's response to movement.

## Future Improvements
- Add a second stabilization axis
- Switch to a continuous rotation servo for 360 degree stabilization

## Author
Nathan Valenzuela
