
---
Title: L2 Snake-Like Modular Robot
---

# Home

### Team Members:
* Abdulrahman Abdullahi ID: 1093374
* Ahmad Eyad ID: 1093720
* Raghad Abdulla ID: 1093438
* Mohammed Nabil ID: 1081916

## Project Overview

Design and development of a snake-like modular robot inspired by the natural movement of a corn snake. The robot uses connected body modules and servo motors to create side-to-side movement, allowing it to move forward and turn on flat surfaces.

## Research Question

How can a modular robotic system be designed to imitate the natural movement of a snake using servo motors and connected joints while maintaining stable and efficient movement on flat surfaces?

## Background Research

### Research Paper 1

[The Mechanics of Slithering Locomotion](https://hu.gatech.edu/Publications/Hu09.pdf)

### Research Paper 2

[A Novel Architecture for Modular Snake Robots](https://www.cs.cmu.edu/~mtesch/publications/CMU-RI-TR-11-29.pdf)

### Research Paper 3

[Robotic Modelling of Snake Traversing Large, Smooth Obstacles](https://pmc.ncbi.nlm.nih.gov/articles/PMC7062058/)

### Research Paper 4

[Snakes Combine Vertical and Lateral Bending to Traverse Uneven Terrain](https://arxiv.org/abs/2112.08474)

## Updated Specifications

* Biological Inspiration: Corn Snake
* Movement: Lateral Undulation
* Mechanism: Servo-Driven Revolute Joints
* Servo Motors: MG996R
* Microcontroller: Arduino Uno R3
* Servo Controller: PCA9685
* Body Material: 3D-Printed PLA
* Ground Contact: Flexible Ribbed Pads
* Power Supply: Regulated 6V Supply

Final specifications will be updated after completing the CAD design.

## System Design

The proposed robot consists of connected body modules controlled by servo motors. Each servo rotates a joint left and right to create a travelling wave along the robot's body.

The Arduino Uno controls the movement through the PCA9685 servo controller, while the servo motors receive power from an external regulated supply.

System Design Image: To be uploaded.

## Snake Robot CAD Design

The preliminary CAD design includes the head shell, connected body links, servo motors, revolute joints, and ribbed contact pads.

The CAD demonstrates the proposed side-to-side movement of the robot.

CAD Image: To be uploaded.

CAD File: To be uploaded.

## Engineering Calculations

Preliminary engineering calculations include:

* Servo Motor Torque
* Servo Motor Mass
* Electrical Current Requirements
* Directional Friction
* Joint Movement Equations

Final calculations will be updated after confirming the number of joints and robot dimensions.

## Design Optimization

Three weighted decision matrices were developed to compare different design options.

### Movement Selection

Lateral undulation was selected over concertina movement and sidewinding.

### Motor Selection

MG996R servo motors were selected over micro servos and DC motors with encoders.

### Ground Contact Selection

Flexible ribbed pads were selected for the initial design. Passive wheels may be considered if the pads do not provide sufficient traction.

## Design & Manufacturing

The preliminary mechanical design has been developed using CAD software.

The proposed manufacturing process includes 3D printing the body modules, installing the servo motors, connecting the joints, and assembling the electronic components.

To be updated.

## Testing and Experimental Validation

Planned testing includes:

* Joint Movement Testing
* Ground Friction Testing
* Forward Movement Testing
* Turning Testing
* Electrical Current and Servo Load Testing

To be updated.

## Presentation 1

Presentation slides link: To be updated.

Video Link: To be updated.

## Presentation 2

Presentation slides link: To be updated.

Video Link: To be updated.

## Bibliography

1. Hu, D. L., et al. (2009). The Mechanics of Slithering Locomotion. Proceedings of the National Academy of Sciences.

2. Johnson, A., et al. (2011). A Novel Architecture for Modular Snake Robots. Carnegie Mellon University.

3. Fu, Q., & Li, C. (2020). Robotic Modelling of Snake Traversing Large, Smooth Obstacles Reveals Stability Benefits of Body Compliance. Royal Society Open Science.

4. Fu, Q., Astley, H. C., & Li, C. (2022). Snakes Combine Vertical and Lateral Bending to Traverse Uneven Terrain. Bioinspiration & Biomimetics.

5. [TowerPro MG996R Servo Motor](https://towerpro.com.tw/product/mg996R/)

6. [Arduino Uno R3 Documentation](https://docs.arduino.cc/hardware/uno-rev3/)

7. [Adafruit PCA9685 Servo Driver](https://learn.adafruit.com/16-channel-pwm-servo-driver)
