# wro-future-engineers
Проект робота для WRO Future Engineers: код, электроника, механика и документация
# Team NEXUS – WRO Future Engineers 2026

## Building a Stable and Reliable Autonomous Vehicle
Welcome to the official GitHub repository of **Team NEXUS** from **Shymkent, Kazakhstan**, participating in the **World Robot Olympiad (WRO) Future Engineers** category.

Team NEXUS is developing an autonomous vehicle built around practical engineering principles. Our main goal is to create a robot that is **stable, reliable, and mechanically strong**, while also being capable of real-time perception and autonomous decision making on the competition field.

Our robot combines **Raspberry Pi 4**, **Arduino Uno**, **computer vision**, **sensor-based support**, and a **wooden chassis** to form a complete autonomous system. This repository documents our engineering process, including hardware, software, testing, and future improvements as we prepare for our first regional stage.

_Last updated: [DATE]_

---

## Team Information

| Category | Details |
|---|---|
| **Team Name** | NEXUS |
| **Country** | Kazakhstan |
| **City** | Shymkent |
| **Competition Category** | WRO Future Engineers 2026 |
| **Team Members** | Sadykbek Nurassyl, Yeshankul Zhansultan |
| **Mentor** | Orynbasarov Bakdaulet |

---

## Team Vision
Our main engineering objective is to build a robot that is:

- **stable in movement**
- **reliable in mechanical structure**
- **practical under real competition conditions**
- **easy to test, debug, and improve**

We believe that strong engineering is based not only on speed, but on **consistency, control, mechanical reliability, and continuous improvement**.

---

## Project Goal
The main goal of Team NEXUS is to develop a **stable and reliable autonomous robot** for the WRO Future Engineers challenge.

Our engineering priorities are:
- reliable mechanical construction
- stable camera-based perception
- robust autonomous decision making
- practical and easy-to-improve system architecture
- strong integration between hardware and software

---

## Our Robot

<p align="center">
  <img src="images/materials/full%20robot%20image1.jpeg" width="420">
  <img src="images/materials/full%20robot%20image%202.jpeg" width="420">
</p>

<p align="center">
  <b>Current robot photos / final assembled robot</b>
</p>

---

## Project Overview
This repository contains the documentation and source code for our WRO Future Engineers robot.

Our project combines:
- **computer vision** for field understanding
- **Arduino-based motion control**
- **color recognition**
- **wall and line detection**
- **gyroscope-supported orientation**
- **a wooden chassis designed for strength and simplicity**

At the current stage of development, our focus is on:
- stable camera calibration
- reliable color detection
- robust wall recognition
- line detection and counting
- consistent turning behavior
- integration between Raspberry Pi and Arduino
- mechanical stability

---

## Current Development Status
Our robot is currently under active development and testing.

At this stage:
- the mechanical structure is assembled
- the electronics are integrated
- the camera system is being calibrated
- the software is still under development
- final competition times will be added later

This is our **first regional stage**, and we continue improving both hardware and software through testing.

---

## Main Features
Our robot is being developed to support the following functions:

- autonomous driving on the WRO field
- red and green block detection
- blue and orange line detection
- wall recognition
- real-time decision making
- gyroscope-assisted orientation support
- modular software structure for future improvements

---

## Materials and Components

<table>
  <tr>
    <th>Photo</th>
    <th>Component</th>
    <th>Function in the Robot</th>
  </tr>
  <tr>
    <td><img src="images/materials/raspberry-4-modele-b-4go.jpg" width="220"></td>
    <td><b>Raspberry Pi 4</b></td>
    <td>Main onboard computer responsible for computer vision, image processing, and high-level decision making.</td>
  </tr>
  <tr>
    <td><img src="images/materials/OIP.webp" width="220"></td>
    <td><b>Raspberry Pi Camera</b></td>
    <td>Captures the field view and provides image data for detecting colored blocks, lines, and walls.</td>
  </tr>
  <tr>
    <td><img src="images/materials/arduino-uno-r3-1-1.jpg" width="220"></td>
    <td><b>Arduino Uno</b></td>
    <td>Handles low-level control tasks and executes movement-related commands.</td>
  </tr>
  <tr>
    <td><img src="images/materials/REPLACE_WITH_EXACT_MOTOR_FILENAME" width="220"></td>
    <td><b>DC Motor with Encoder</b></td>
    <td>Drives the robot forward and provides motion feedback for more accurate control.</td>
  </tr>
  <tr>
    <td><img src="images/materials/mg996r-metal-gear-torque-digital-servo.jpg" width="220"></td>
    <td><b>Servo Motor</b></td>
    <td>Controls the steering angle of the robot.</td>
  </tr>
  <tr>
    <td><img src="images/materials/bts7960-motor-driver-module.png" width="220"></td>
    <td><b>Motor Driver</b></td>
    <td>Supplies and regulates power for the drive motor according to control commands.</td>
  </tr>
  <tr>
    <td><img src="images/materials/mpu6050-6-axis-gyroscope-accelerometer-sensor.jpg" width="220"></td>
    <td><b>Gyroscope</b></td>
    <td>Provides orientation-related data to improve turning consistency and heading stability.</td>
  </tr>
  <tr>
    <td><img src="images/materials/R.png" width="220"></td>
    <td><b>Power Converter / Voltage Regulator</b></td>
    <td>Ensures stable voltage delivery to different electronic subsystems.</td>
  </tr>
  <tr>
    <td><img src="images/materials/bateria-lipo-74v2s35c-1550mah.jpg" width="220"></td>
    <td><b>Battery / Power Source</b></td>
    <td>Supplies electrical power to the robot during operation.</td>
  </tr>
  <tr>
    <td><img src="images/materials/image.png" width="220"></td>
    <td><b>Wooden Chassis</b></td>
    <td>Serves as the main structural frame of the robot and supports all mounted components.</td>
  </tr>
</table>

---

## Mechanical Design

| Mechanical Element | Description |
|---|---|
| **Chassis Material** | Wood |
| **Design Goal** | Strong, stable, and reliable construction |
| **Main Priority** | Mechanical stability and reliability |
| **Structure Type** | Simple and practical layout for easier maintenance and upgrades |
| **Development Focus** | Stable component mounting, balanced structure, and reliable steering mechanics |

Our robot uses a **wooden chassis** because it allows practical construction, fast modification, and stable mounting of major subsystems. The design is focused on reliability and straightforward engineering rather than unnecessary complexity.

---

## Electronic System

| Subsystem | Role |
|---|---|
| **Vision System** | Raspberry Pi 4 + Raspberry Pi Camera |
| **Control System** | Arduino Uno |
| **Drive System** | DC motor with encoder + motor driver |
| **Steering System** | Servo motor |
| **Orientation Support** | Gyroscope |
| **Power Distribution** | Battery and voltage converters |

The robot electronics are divided into two logical layers:

1. **High-level processing on Raspberry Pi**
   - camera input
   - image processing
   - color detection
   - wall detection
   - decision making

2. **Low-level execution on Arduino**
   - steering control
   - motor control
   - receiving motion commands

This architecture makes the system more modular and easier to debug.

---

## Software Architecture
The software is designed with a modular structure so that each subsystem can be tested and improved independently.

### Main software tasks
- camera initialization
- frame capture
- HSV-based color detection
- red and green block recognition
- blue and orange line detection
- wall detection
- movement decision logic
- communication between Raspberry Pi and Arduino
- future lap / line counting logic
- challenge completion logic

### Planned movement logic
- detect important field objects through the camera
- classify relevant objects in real time
- determine whether the robot should go forward, turn left, turn right, or stop
- combine camera-based logic with gyroscope support for stability

---

## Repository Structure

```text
/docs/                  -> main technical documentation
/images/                -> robot photos, material photos, diagrams
/src/raspberry_pi/      -> Raspberry Pi vision and decision-making code
/src/arduino/           -> Arduino control code
/config/                -> camera, HSV, and robot parameters
/tests/                 -> testing notes and debugging results
/media/                 -> videos or video links
