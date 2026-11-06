# 🚁 UAV Development & Multi-Sensor Integration Project

### Research | Design | 3D Printing | Embedded Systems | Flight Control | Computer Vision

## 📌 Project Overview

This project focuses on the research, design, development, and integration of a multi-system Unmanned Aerial Vehicle (UAV), combining mechanical engineering, electronics, embedded computing, flight control, and intelligent sensing.

Developed over approximately **1.5 months with college funding**, the project involved exploring different drone architectures, selecting hardware components, designing mechanical structures, 3D printing, assembling electronic subsystems, configuring flight controllers, and working on sensor and imaging integration.

The goal was to develop a functional aerial robotics platform with the potential for RGB imaging, thermal imaging, LiDAR-based sensing, telemetry, and onboard computing.

## 🎯 Project Objectives

- Design and develop a custom UAV platform.
- Research and integrate suitable propulsion and power systems.
- Implement flight control using Pixhawk and ArduPilot.
- Integrate GPS, telemetry, and RC communication.
- Explore onboard image processing using Raspberry Pi 5.
- Investigate RGB, thermal, and LiDAR-based sensing.
- Develop mechanical components using CAD and 3D printing.
- Understand hardware-software communication and system integration.

## ⚙️ Hardware Components

### 1. Flight Control & Navigation

| Component | Model |
|---|---|
| Flight Controller | Pixhawk 2.4.8 |
| Flight Firmware | ArduPilot / ArduCopter |
| GPS Module | Holybro M9N GPS |
| Power Module | Holybro PM02D HV |
| Telemetry | Holybro SiK Telemetry Radio V3 |
| Telemetry Frequency | 433 MHz |
| RC Transmitter | RadioMaster TX12 MKII ELRS |

### 2. Propulsion System

| Component | Specification |
|---|---|
| Frame | ZD550 – 550 mm |
| Motors | 4 × MAD 4014 IPE 400KV |
| ESCs | 4 × Hobbywing XRotor 40A APAC OPTO |
| Battery | BONKA 6200mAh 35C 6S LiPo |
| Power Distribution | SwiftWing PDB-02-XT60 |
| Battery Connector | XT60 |

### 3. Onboard Computing & Imaging

| Component | Model |
|---|---|
| Companion Computer | Raspberry Pi 5 |
| RGB Camera | Raspberry Pi Camera Module 3 Wide |
| Thermal Camera | TOPDON TC001 USB Thermal Camera |
| Storage | microSD Card |
| Wireless Connectivity | Wi-Fi / Wireless Networking |

### 4. Additional Sensors & Research Hardware

- Unitree LiDAR L2 – LiDAR integration and ranging experiments.
- DFRobot IMX678 4K USB Camera – evaluated for high-resolution imaging.
- FLIR Lepton 3.5 – explored for thermal imaging applications.
- Additional sensor interfaces and communication modules.

*Some of these components were evaluated during the development and integration process rather than being confirmed as permanently installed hardware.*

### 5. Supporting Equipment

- IMAX B6AC 80W LiPo Battery Charger.
- USB-to-serial communication interfaces.
- Telemetry antennas and adapters.
- JST-GH and DF13 connectors.
- XT60 power connectors.
- Wiring, soldering and assembly equipment.
- 3D-printed mechanical components and mounting structures.

## 💻 Software & Technologies

| Technology | Application |
|---|---|
| ArduPilot | UAV flight control firmware |
| ArduCopter | Multirotor flight control |
| MAVLink | Communication protocol |
| QGroundControl | Flight monitoring and configuration |
| Python | Sensor integration and image processing |
| OpenCV | Computer vision and image processing |
| Raspberry Pi OS | Companion computer environment |
| Linux | Embedded development |
| CAD Software | Mechanical design |
| 3D Printing | Custom component fabrication |

## 🏗️ System Architecture

The project is divided into multiple interconnected subsystems:

1. **Flight Control:** Pixhawk manages flight stabilization, motor outputs, navigation, and flight control.
2. **Propulsion:** Brushless motors and ESCs provide the thrust required for flight.
3. **Power Management:** LiPo battery, power distribution, and power monitoring supply the electronic systems.
4. **Navigation & Communication:** GPS provides positioning, while the SiK telemetry system enables MAVLink communication with the ground station.
5. **Companion Computing:** Raspberry Pi 5 provides an onboard computing environment for camera and sensor processing.
6. **Imaging & Sensing:** RGB, thermal, and LiDAR technologies are explored for environmental perception and data acquisition.

## 🔬 Development Workflow

The development process involved:

- Researching UAV architectures and component specifications.
- Selecting motors, ESCs, batteries, flight controllers, and supporting electronics.
- Mechanical frame planning and structural design.
- Designing and fabricating components using 3D printing.
- Power distribution and electronic hardware integration.
- Pixhawk configuration and ArduPilot setup.
- ESC calibration and motor testing.
- GPS, RC receiver, and telemetry configuration.
- Raspberry Pi and camera integration.
- Investigating thermal imaging and LiDAR communication.
- Troubleshooting hardware, firmware, and communication issues.

## 🧠 Key Engineering Domains

- Unmanned Aerial Vehicle (UAV) Development
- Robotics and Embedded Systems
- Mechanical Design and 3D Printing
- Flight Control Systems
- Power Electronics
- Sensor Integration
- Computer Vision
- Thermal Imaging
- LiDAR Technology
- Wireless Communication
- Hardware-Software Integration

## 📚 Key Learnings

This project provided practical experience in understanding how multiple engineering subsystems interact within a real-world robotic platform.

Some of the major learning areas included:

- Flight controller configuration and troubleshooting.
- ESC calibration and motor signal analysis.
- Battery and power distribution considerations.
- MAVLink communication and telemetry.
- Embedded Linux and Raspberry Pi development.
- Camera and sensor communication interfaces.
- Mechanical design and hardware assembly.
- System-level integration and debugging.

## 👥 Acknowledgement

This project was undertaken with institutional funding and support from **CGC University, Mohali**, providing an opportunity to explore practical applications of robotics, artificial intelligence, and UAV technology.

The project was also presented at **AVISKAR 2026 – AI Summit for Nation Building**, where the work and contribution received a Certificate of Appreciation.

---

**Project Focus:** UAV Development | Robotics | AI | Embedded Systems

**Development Duration:** Approximately 1.5 Months

**Development Support:** College Funded

**Status:** Development and integration project

*Building, experimenting, integrating, and learning — one subsystem at a time.* 🚀
