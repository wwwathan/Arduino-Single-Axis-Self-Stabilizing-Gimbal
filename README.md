

# Single-Axis Auto-Adjusting Gimbal
An Arduino-based gimbal that uses an MPU-6050 to detect changes in orientation and adjust a servo motor along one axis.

## How It Works
The MPU-6050 measures the device's movement. The Arduino processes the sensor data and adjusts the servo to move according to how much the device tilts. The repository includes the different stages of development, from early testing to the final implementation in the main branch.

### Watch The Demonstration and Explanation:
[![Watch the project demonstration](https://img.youtube.com/vi/lS9gYSJsHQ4/hqdefault.jpg)](https://youtu.be/lS9gYSJsHQ4)

## Hardware Used
- Elegoo UNO R3
- MPU-6050 accelerometer and gyroscope
- Servo motor
- Breadboard and jumper wires

## Setup
1. Open the final working sketch in the Arduino IDE.
2. Connect the Elegoo UNO R3 to your computer.
3. Verify and compile the code.
4. Upload the firmware to the microcontroller.
5. Use serial monitor to adjust offset

## Future Improvements
- Add a second stabilization axis
- Switch to a continuous rotation servo for 360 degree stabilization

## Author
Nathan Valenzuela
