# Intelligent Drawing Cobot

<p align="center">
  <img src="images/cobot_banner.png"
       alt="Intelligent Drawing Cobot"
       width="900">
</p>

A collaborative robotic drawing system developed as a BSc Mechatronics & Control Engineering capstone project at the University of Engineering & Technology (UET), Lahore.

The project investigates **human–robot interaction using admittance control**, allowing a user to physically guide a robotic manipulator through a desired trajectory. The demonstrated trajectory can then be processed using **curve fitting** and reproduced by the robot as a refined analytical shape.

## Project Overview

The Intelligent Drawing Cobot was developed using the **Serpent-I SCARA robotic manipulator** configured as a two-degree-of-freedom (2-DOF) planar system.

The system combines:

- Admittance control for human–robot interaction
- Forward and inverse kinematics
- Force-sensitive input
- Encoder-based position feedback
- PID position control
- Curve fitting for trajectory refinement
- Arduino-based embedded control
- MATLAB/Simulink and Simscape simulation
- Physical robotic hardware implementation

The overall objective was to demonstrate a simple **learning-by-demonstration approach**, where a user guides the robot along a trajectory and the system subsequently reproduces a refined version of the intended shape.

## System Architecture

The Intelligent Drawing Cobot was developed around a **2-DOF planar robotic manipulator** designed to support physical human–robot interaction and trajectory learning.

The system follows a learning-by-demonstration approach in which force applied by the user is interpreted through the admittance-control framework and converted into commanded manipulator motion. Position and force measurements provide feedback during interaction, while the demonstrated trajectory can subsequently be processed using curve fitting to obtain a refined path for autonomous reproduction.

The overall workflow therefore connects **human input, sensing, robotic motion, trajectory acquisition, curve fitting, and automated trajectory reproduction**.

### Project Workflow

<p align="center">
  <img src="images/01_project_workflow.png"
       alt="Intelligent Drawing Cobot Project Workflow"
       width="700">
</p>

<p align="center">
  <i>Figure 1. Overall workflow of the Intelligent Drawing Cobot, from physical human input to trajectory processing and robotic reproduction.</i>
</p>

The architecture was designed to allow a user to demonstrate a task through physical interaction rather than requiring the complete trajectory to be programmed manually. The demonstrated motion provides the basis for generating a refined trajectory that can subsequently be reproduced by the manipulator.

## Control Methodology

*Admittance control, kinematics and position-control methodology will be added here.*

## Simulation

*Simulink and Simscape implementation will be added here.*

## Hardware Implementation

*Physical Serpent-I robot implementation will be added here.*

## Results

*Simulation, curve-fitting and experimental results will be added here.*

## My Contributions

*Individual project contributions will be documented here.*

## Technologies & Engineering Concepts

- MATLAB
- Simulink
- Simscape
- Arduino / ATmega2560
- C/C++ Embedded Programming
- Admittance Control
- PID Control
- Forward & Inverse Kinematics
- Robot Dynamics
- Curve Fitting
- Human–Robot Interaction
- Sensor Integration
- DC Motor Control

## Repository Structure

```text
Intelligent-Drawing-Cobot/
│
├── README.md
├── docs/
└── images/
    └── selected-project-figures/
```

## Academic Context

This project was completed as the final-year capstone project for the **Bachelor of Mechatronics & Control Engineering** degree at the **University of Engineering & Technology (UET), Lahore**.
