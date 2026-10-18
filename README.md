Real-Time Vision-Based Precision Landing of UAV in GPS-Limited Environments

Project Overview

This project presents a real-time vision-based precision landing system for an Unmanned Aerial Vehicle (UAV), designed to achieve accurate and autonomous landing in GPS-limited and GPS-denied environments. The system integrates a Pixhawk 2.4.8 flight controller with an OpenMV H7 machine-vision camera to detect and track AprilTag markers placed on a designated landing pad.

Using onboard image processing, the camera calculates the angular offsets between the UAV and the landing target and transmits the information to the flight controller through MAVLink communication. The flight controller processes these measurements and performs closed-loop corrections to guide the UAV toward the landing pad.

The system was evaluated in outdoor, semi-outdoor, and indoor environments at descent altitudes of 2 m and 3 m, achieving landing deviations of approximately 9–12 cm. The project demonstrates the feasibility of a cost-effective vision-based precision landing solution that reduces dependence on GPS for accurate UAV landing.

Objectives

- Develop a real-time vision-based precision landing system for UAVs.
- Implement AprilTag detection and target tracking using the OpenMV H7 camera.
- Integrate camera-based landing guidance with the Pixhawk flight controller through MAVLink.
- Achieve autonomous landing through closed-loop flight control.
- Evaluate landing accuracy under varying environmental and GPS conditions.

Hardware Components

- Pixhawk 2.4.8 Flight Controller
- OpenMV H7 Machine-Vision Camera
- S500 Quadcopter Frame
- Brushless DC Motors and Electronic Speed Controllers
- GPS and Compass Module
- FlySky FS-i6 Transmitter and Receiver
- Telemetry Communication Module
- LiPo Battery and Power Distribution System
- AprilTag Landing Marker

Software and Technologies

- ArduCopter Firmware
- Mission Planner
- MicroPython
- MAVLink Communication Protocol
- AprilTag Detection
- PID-Based Flight Stabilization
- Extended Kalman Filter (EKF)
Working Principle

1. The downward-facing OpenMV H7 camera captures images of the landing area.
2. The onboard image-processing algorithm detects the AprilTag marker and calculates its angular offsets relative to the camera's center.
3. The calculated target information is transmitted to the Pixhawk flight controller using MAVLink LANDING_TARGET messages.
4. The flight controller processes the visual measurements and generates appropriate control corrections.
5. The UAV adjusts its position during descent to align with the landing marker and achieve a precise touchdown.

Results

The system demonstrated precision landing performance across outdoor, semi-outdoor, and indoor environments at different descent altitudes. Experimental results reported mean landing deviations of approximately less than 12 cm, demonstrating the effectiveness of visual target detection and closed-loop control for precision landing in GPS-limited conditions.

Applications

- Autonomous UAV landing and navigation
- Package and medical-supply delivery
- Infrastructure inspection
- Search-and-rescue operations
- Indoor drone navigation
- Industrial and remote-area surveillance

Future Scope

Potential improvements include integrating advanced object-detection algorithms, enhancing performance under poor lighting and partial marker occlusion, incorporating additional vision-inertial fusion techniques, and extending the system to dynamic landing platforms.

Conclusion

The project demonstrates a vision-based approach to autonomous UAV precision landing by combining embedded machine vision, AprilTag detection, MAVLink communication, and flight-controller stabilization. The achieved landing accuracy highlights the potential of affordable vision-guided systems for reliable UAV operation where conventional GPS-based landing is insufficient.

Project Information
Real-Time Vision-Based Precision Landing of UAV in GPS-Limited Environments
Institution: Bangalore Institute of Technology, Bengaluru
Department: Electronics and Telecommunication Engineering
Academic Year: 2026-2027
Project Guide: Thyagaraj R

Team Members:
- Amruth M Kashyap
- Chiranth B M
- Nihal S Jamakhandi
- Prajwal S
**Institution:** Bangalore Institute of Technology, Bengaluru  
**Department:** Electronics and Telecommunication Engineering  
**Academic Year:** 2025–2026  
**Project Guide:** Thyagaraj R
