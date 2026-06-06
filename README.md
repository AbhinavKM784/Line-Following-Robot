# Line-Following-Robot
<img width="1280" height="720" alt="maxresdefault" src="https://github.com/user-attachments/assets/c5233479-a9e9-41e7-a05a-365323582025" />


An autonomous line-following robot built using an Arduino, IR sensors, and DC geared motors. The robot detects a black line on a light-colored surface and adjusts its movement to remain on the track without human intervention.

## Overview

This project was developed to explore robotics, embedded systems, sensor interfacing, and motor control. The robot uses infrared sensors to detect line position and executes movement commands based on sensor feedback.

## Features

- Autonomous line following
- Real-time line detection using IR sensors
- Motor control through an H-bridge motor driver
- Compact and lightweight design
- Suitable for robotics competitions and educational demonstrations

## Hardware Used

| Component | Quantity |
|------------|----------|
| Arduino Uno | 1 |
| IR Line Tracking Sensor | 2 |
| L298N Motor Driver | 1 |
| DC Geared Motors | 2 |
| Robot Chassis | 1 |
| Wheels | 2 |
| Castor Wheel | 1 |
| Battery Pack | 1 |

## Schematics
<img width="2919" height="2403" alt="IMG-20260218-WA0031" src="https://github.com/user-attachments/assets/16d132e9-0510-4d34-9967-744d88a3eb99" />


## Working Principle

The robot continuously reads data from two infrared sensors mounted at the front.

- When both sensors detect the track, the robot moves forward.
- When the left sensor moves away from the track, the robot adjusts left.
- When the right sensor moves away from the track, the robot adjusts right.
- The process repeats continuously, allowing the robot to follow the line.

## Challenges Faced

- Sensor placement significantly affected detection accuracy.
- Initial tests produced unstable movement on sharp turns.
- Multiple rounds of calibration were required to achieve reliable tracking.

## Results

The completed robot successfully follows predefined tracks and navigates curves while maintaining stable movement. Testing demonstrated consistent performance across multiple runs.

## What I Learned

- Arduino programming
- Sensor interfacing
- Motor driver operation
- Robot testing and calibration
- Basic autonomous navigation concepts

## Media

### Robot Photo
<img width="2668" height="1540" alt="IMG_20260604_230252" src="https://github.com/user-attachments/assets/5e52446a-0326-4287-ae9f-eb6e26094739" />

### Demo Video

https://github.com/user-attachments/assets/a1a8f594-a612-4c63-b1e1-15dec6cf9382


Abhinav
B.Tech Electrical and Electronics Engineering
