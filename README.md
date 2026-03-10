# Autonomous Robotic Arm with Wireless Mobile Control

## Project Overview

This project presents the design and development of an autonomous robotic arm capable of executing programmed movements and performing object manipulation tasks. The robotic arm can also be controlled wirelessly through a mobile application, enabling remote operation.

The system integrates robotics, embedded systems, and wireless communication technologies to demonstrate how robotic devices can be programmed for automated tasks while still allowing real-time remote control by a user.

---

## Objectives

The objectives of this project include:

- Design and construct a functional robotic arm prototype
- Implement programmed autonomous movement sequences
- Enable wireless control of the robotic arm through a mobile application
- Explore practical applications of robotics and automation

---

## System Architecture

The robotic arm system consists of four main subsystems:

1. Mechanical robotic arm structure
2. Embedded control system
3. Wireless communication module
4. Mobile application interface

The robotic arm can operate in two modes:

- **Autonomous Mode:** executes pre-programmed movement sequences
- **Wireless Control Mode:** receives commands from a mobile app for real-time operation

System workflow:

Mobile App / Programmed Commands → Wireless Module → Microcontroller → Motor Drivers → Servo Motors → Robotic Arm Movement

---

## Hardware Components

The robotic arm prototype was developed using the following hardware components:

- Microcontroller (control unit) - Arduino Uno ![Arduino uno image](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/arduino%20image.jpg)
- Servo motors for joint movement - Mg996R ![Arduino uno image](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/servo%20image.webp)
- Wireless communication module (Bluetooth/WiFi) - Esp32 ![esp32 image](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/esp32%20image.jpg)
- Robotic arm frame
- Gripper (end effector)
- Power supply unit
- Connecting wires, breadboard and supporting components

Each servo motor controls a specific joint, allowing multi-axis movement of the robotic arm.

---

## Software Implementation

The system software manages both the autonomous movement routines and the wireless control commands.

Key software functions include:

- Executing programmed movement sequences
- Receiving commands from the mobile application
- Processing movement instructions using the microcontroller
- Sending control signals to the servo motors
- Controlling the gripper for object manipulation

The software enables smooth coordination of all robotic arm joints.

---

## Working Principle

The robotic arm operates in two modes.

### Autonomous Mode
The microcontroller executes predefined movement sequences stored in the program. These instructions control the servo motors to perform automated pick-and-place tasks.

### Wireless Control Mode
The user sends commands from a mobile application. These commands are transmitted wirelessly to the robotic arm's communication module. The microcontroller interprets the commands and activates the appropriate servo motors to perform the desired movement.

Typical operation sequence:

1. User sends command via mobile app or programmed routine
2. Wireless module receives the signal
3. Microcontroller processes the instruction
4. Servo motors move the robotic arm joints
5. Gripper performs object manipulation

---

## Applications

Robotic arms with wireless control can be used in:

- Industrial automation
- Smart manufacturing systems
- Remote material handling
- Robotics education and research
- Hazardous environment operations

---

## Skills Demonstrated

This project demonstrates knowledge and practical skills in:

- Robotics system design
- Embedded systems development
- Wireless communication systems
- Microcontroller programming
- Mechatronics integration
- Automation and control systems

---

## Project Images

Images of the robotic arm prototype below.

![Robotic Arm front View](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/robotic_arm_front_view_with_grip_closed.png)

Robotic arm front view with grip closed

![Robotic Arm front View](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/robotic_arm_front_view_with_grip_open.png)

Robotic arm front view with grip open

![Robotic Arm Side View](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/robotic_arm_side_view.png)

Robotic arm side view

![Robotic Arm Side View](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/robotic_arm_side_view2.png)

Robotic arm side view2

![Mobile Control Interface](https://github.com/Hackmonstar/Autonomous-Robotic-Arm/blob/main/image/mobile_app_interface.png)

Mobile App control Interface

---

## Demonstration Video

Watch the project demonstration here:

Project Demo:  
https://www.youtube.com/shorts/jeJxKYc6mj8

Demo of the Grip(end effector) test
https://www.youtube.com/shorts/gK2Ie0IIwsM

Demo of the skeletal structure wrist joint(end effector) test
https://www.youtube.com/shorts/XUgc-nxxgv8

Demo of the skeletal structure elbow joint(end effector) test
https://www.youtube.com/shorts/fNqK5qH4WYo

Demo of the skeletal structure shoulder joint(end effector) test
https://www.youtube.com/shorts/pFckaWutCT4


---

## Future Improvements

Possible future enhancements include:

- Integration of computer vision for object detection
- AI-based autonomous task planning
- Improved robotic arm precision
- Mobile app interface enhancements
- Internet of Things (IoT) connectivity

---

## Conclusion

The Autonomous Robotic Arm with Wireless Mobile Control demonstrates the integration of robotics, embedded systems, and wireless communication technologies to create a remotely operable and programmable robotic system. The project highlights how robotic systems can combine automation with user-controlled operation for flexible and intelligent applications.
