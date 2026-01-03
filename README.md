# Functional Robotic Surgical System Prototype (Personal Project)

## Overview
This project is a self-directed, functional prototype inspired by robotic surgical systems such as the da Vinci platform. It was designed and built independently to explore mechanical articulation, electromechanical control, and human-operated robotic motion using accessible materials and embedded systems.

The system is fully functional at a prototype level and demonstrates controlled, repeatable tool motion driven by user input.

---

## Project Motivation
The goal of this project was to:
- Design and build a working articulated robotic mechanism from scratch
- Translate human input into precise mechanical motion
- Explore constrained kinematics similar to robotic-assisted surgical tools
- Gain hands-on experience integrating mechanical design, electronics, and control logic

This was a personal project, developed outside of coursework.

---

## System Description
The prototype consists of:
- A user-operated input interface
- Mechanically articulated tool arms with multiple joints
- Servo-based actuation
- An Arduino-based control system that maps user inputs to joint motion

Rather than replicating a clinical system, the design focuses on motion control, repeatability, and mechanical constraints at a small scale.

---

## Materials and Components

### Mechanical Components
- Wooden base platform
- Popsicle sticks used as articulated arm segments
- Screws, bolts, and washers forming rotational joints
- Hinges and brackets for constrained articulation
- Elastic elements for passive compliance

### Electronics
- Arduino microcontroller
- Breadboard
- Servo motors
- Potentiometers for user input
- Jumper wires
- Battery pack / external power supply

### Tools
- Soldering iron
- Wire cutters and strippers
- Screwdrivers
- Hot glue gun for structural reinforcement

---

## Build Process

### 1. Mechanical Design and Assembly
- A rigid base was constructed to support the articulated arms.
- Joints were designed to allow rotation while preventing overextension.
- Multiple iterations were required to achieve smooth, stable motion.

### 2. Control Interface
- Potentiometers were used to provide direct user control over joint movement.
- Each control input was mapped to a corresponding joint or actuator.

### 3. Actuation and Control Logic
- Servo motors were mechanically coupled to the joints.
- The Arduino continuously reads input signals and converts them into servo commands.
- Motion limits were implemented to protect the mechanism and ensure repeatability.

### 4. Testing and Iteration
- The system was tested under continuous operation.
- Mechanical alignment and control mappings were refined through iteration.

---

## How the System Works
- User inputs are applied through potentiometers.
- The microcontroller maps input values to servo positions.
- Servo motors drive articulated joints through mechanical linkages.
- Physical constraints in the design limit motion and improve stability.

This architecture demonstrates key robotic system principles including:
- human-in-the-loop control
- input-to-actuation mapping
- constrained kinematics
- electromechanical integration

---

## Results
- Achieved controlled, repeatable articulated motion
- Stable mechanical behavior across operating ranges
- Reliable translation of user input into physical movement

---

## Limitations
- No force or haptic feedback
- Simplified kinematics compared to clinical robotic systems
- No imaging or vision integration

---

## Figures
*(Photos of the prototype, electronics, and testing setup are included to illustrate the system design and functionality.)*

---

## Author
Masa Damdoum  
Electrical Engineering (Co-op)  
University of Windsor

---

## Disclaimer
This project is a **personal engineering prototype inspired by robotic surgical systems**. It is not a medical device and is not intended for clinical use.
