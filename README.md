# Autonomous Guard Bot

**Personal Project | Robotics | Embedded Systems | Computer Vision**

An Arduino UNO Q-based autonomous security and surveillance robot designed to integrate computer vision, adaptive navigation, remote monitoring, and automated security responses.

## Overview

The Autonomous Guard Bot is a personal robotics project focused on developing a mobile security platform capable of monitoring its surroundings, detecting and recognizing faces, and responding to predefined events.

The system is designed around the **Arduino UNO Q**, selected as a cost-effective alternative to the Raspberry Pi for the project's embedded control and onboard processing requirements.

The proposed design integrates ultrasonic and IR sensors, an HD camera, a 3D-printed chassis, and a servo-mounted camera turret. The goal is to combine autonomous robotics with remote monitoring and two-way communication through a mobile device.

**Project Status:** In Development

## Project Objectives

- Develop an autonomous mobile security and surveillance robot.
- Integrate Python-based computer vision with C/C++ embedded control.
- Implement adaptive navigation using ultrasonic and IR sensors.
- Develop facial detection, tracking, and recognition capabilities.
- Enable automated responses to unfamiliar individuals and predefined events.
- Support real-time video/audio streaming and remote monitoring.
- Create a modular software architecture for future expansion.

## Planned System Features

### Computer Vision
- Real-time face detection and tracking using OpenCV.
- Facial recognition for distinguishing enrolled and unfamiliar individuals.
- Automated camera turret positioning.
- Event-driven visual monitoring.

### Navigation and Motion Control
- Ultrasonic and IR-based obstacle detection.
- Adaptive navigation and collision avoidance.
- Servo and motor control.
- Autonomous patrol behaviors.

### Security and Automation
- Automated alerts and notifications.
- Programmable responses to unfamiliar faces.
- Upright mechanical response when predefined detection conditions are met.
- Event logging and monitoring history.

### Remote Monitoring
- Real-time WebRTC video and audio streaming.
- Two-way communication through a mobile device.
- Remote access to camera feeds and system status.
- Future remote-control functionality.

## Hardware Components

| Component | Purpose |
|---|---|
| Arduino UNO Q | Embedded control and onboard processing |
| Ultrasonic Sensors | Distance measurement and obstacle detection |
| IR Sensors | Proximity sensing |
| HD Camera | Video capture and computer vision |
| Servo Motors | Camera turret movement |
| Drive Motors | Robot mobility |
| 3D-Printed Chassis | Mechanical structure and component mounting |

## Software and Tools

- **Languages:** Python, C/C++
- **Computer Vision:** OpenCV
- **Embedded Development:** Arduino IDE
- **Communication:** WebRTC, serial communication
- **Mechanical Design:** 3D CAD modeling, 3D printing
- **Version Control:** Git and GitHub

## Proposed System Workflow

1. **Sensor Input:** Ultrasonic and IR sensors collect environmental data.
2. **Video Capture:** The HD camera captures live visual information.
3. **Computer Vision:** OpenCV processes video for face detection and tracking.
4. **Decision Logic:** The system evaluates sensor readings and detection events.
5. **Motor Control:** The controller sends commands to the camera turret and drive motors.
6. **Security Response:** Predefined events trigger alerts, logging, or mechanical actions.
7. **Remote Monitoring:** Video, audio, and system status are accessible through a mobile interface.

## Development Roadmap

### Phase 1: Computer Vision and Software
- [ ] Implement face detection using OpenCV.
- [ ] Develop face tracking and target-position calculations.
- [ ] Simulate camera turret movement.
- [ ] Implement event logging.
- [ ] Establish modular Python project structure.

### Phase 2: Embedded Systems and Hardware
- [ ] Configure the Arduino UNO Q development environment.
- [ ] Develop servo and motor control firmware.
- [ ] Integrate ultrasonic and IR sensors.
- [ ] Design and 3D-print the chassis.
- [ ] Establish communication between onboard processing and hardware control.

### Phase 3: Autonomous Navigation
- [ ] Implement obstacle avoidance.
- [ ] Develop autonomous movement routines.
- [ ] Integrate facial recognition.
- [ ] Implement event-triggered motion responses.
- [ ] Test coordinated navigation and camera tracking.

### Phase 4: Remote Monitoring
- [ ] Implement WebRTC video streaming.
- [ ] Enable two-way audio communication.
- [ ] Develop a mobile monitoring interface.
- [ ] Implement alerts and event history.
- [ ] Test remote accessibility and connection security.

## Planned Repository Structure

```
Autonomous-Guard-Bot/
├── vision/             # Face detection and tracking
├── control/            # Navigation and turret control
├── firmware/           # Arduino C/C++ code
├── sensors/            # Sensor processing and simulation
├── monitoring/         # Streaming, alerts, and logging
├── hardware/           # CAD models and mechanical designs
├── tests/              # Software and hardware tests
├── docs/               # Documentation and architecture
├── requirements.txt    # Python dependencies
└── README.md
```

## Future Improvements

- Improve recognition accuracy under varying lighting conditions.
- Optimize computer vision performance for embedded deployment.
- Expand autonomous navigation and patrol capabilities.
- Improve system power efficiency.
- Develop a more advanced remote monitoring interface.
- Integrate additional sensors and automation features.

## Author

**Franceli Gonzalez**  
Texas State University

---

*This project is currently under development. Features and system architecture will evolve as software development, hardware prototyping, and integration testing progress.*
