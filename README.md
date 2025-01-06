# 🤖 Obstacle-Course Robot Project

This project involves the creation of a compact and efficient robot specifically designed to navigate an **obstacle course** and perform targeted tasks, such as **popping balloons**. The robot combines innovative movement mechanics with a simple and modular design, making it adaptable for various challenges.

## Key Features

1. **Balloon Popping Mechanism**:  
   - A functional attachment (e.g., a sharp or extendable tool) will allow the robot to pop balloons on the course, meeting task requirements.

2. **Innovative Movement**:  
   - The design eliminates the use of traditional wheels, replacing them with a crankshaft-driven system that provides unique motion dynamics.
   - Rotational stability is achieved through carefully designed support points.

---

## Draft Design Visualization
<p align="center">
📷 Draft Sketch of the Robot
</p>
<p align="center">
    <img src="https://github.com/user-attachments/assets/c720f304-706b-4fab-8ddb-1de5cc8a671a"  width="70%" height="70%"/>
</p>

## Draft Overview

The initial draft highlights the core structure and mechanism of the robot, including key components:  
- **Leg (Crankshaft)**: Responsible for the robot's movement by converting rotational motor energy into linear motion.  
- **Large Joint Mounts**: Designed for connecting and stabilizing the leg assembly, though improvements are needed to prevent looseness.  
- **Crankshaft System**: Central to the motion, translating motor power into smooth rotational and linear movement.  
- **Main Platform (Frame)**: A triangular structure that supports all components and ensures balance.  
- **Rotational Wheel (Support)**: Helps maintain stability during complex navigation.  
- **Motor Assembly**: Powers the crankshaft and supports the overall movement of the robot.

The draft also identifies areas for improvement, such as enhancing joint stability and optimizing the motor assembly for better torque.

---

## Components and Materials
The creation of the robot will involve the following components (as indicated in the draft materials):  
- **Motors (x2)**: Provide the primary movement force.  
- **Motor Holders (3D-Printed)**: Secure the motors in place (recommended PLA or PETG material).  
- **Crankshaft and Support Structures**: For the leg-driven movement mechanism.  
- **Platform (Plywood or PLA)**: Forms the triangular frame for stability and component attachment.  
- **18650 Batteries (x2)**: Power the motors and electronics.  
- **Wheels and Tires**: For rotational stability (if needed for specific iterations).  
- **PCB and Wiring**: Soldered to connect the motors, battery pins, and controllers.  
- **Battery Holder Pins**: Secure the 18650 batteries in place.  
- **LED Strips (Optional)**: For visual feedback or aesthetics during operation.

These components provide a balance between durability, modularity, and ease of assembly.

---

## Challenges Identified During the Initial Build

The first iteration of the **Obstacle-Course Robot** revealed several issues in its design and functionality that required significant modifications to improve performance:

1. **Friction Issues in the Belt Drive System**:
   - The friction between the **belt drive system** and the **wheels** was higher than the friction between the **shaft** and the **wheels**.  
   - This imbalance caused the wheels to slip, leading to inefficient movement and difficulty in navigating the obstacle course.

2. **Insufficient Stability with Four Legs**:
   - The initial design, featuring only **four legs**, proved unstable when encountering complex obstacles.
   - This limited the robot's ability to maintain balance and stability, particularly during sharp turns or uneven terrain.

---

## Initial Test Video

<p align="center">
    <b>Watch the video of the initial test run:</b><br>
    <a href="">
        <img src="" width="70%" height="70%"/>
    </a>
    <br>
    <i>The video demonstrates the issues encountered during the first test, including slipping wheels and instability.</i>
</p>

---

## Implemented Solutions

To address the identified challenges, the following adjustments were made:

1. **Improved Belt Drive System**:
   - **Thicker Belts**: The belt was redesigned to be thicker, reducing the likelihood of slipping and enhancing durability.  
   - **Revised Wheel Design**: The shape of the wheels was modified to increase the contact area and improve grip with the belt.  
   - **Bearing Installation**: Bearings were added to the wheels, ensuring smoother motion and reducing unwanted friction.

2. **Enhanced Stability with Six Legs**:
   - The number of legs was increased from **four to six**, providing better balance and allowing the robot to navigate obstacles more effectively.
   - The additional legs improved the robot's ability to distribute its weight evenly and maintain stability during challenging maneuvers.

