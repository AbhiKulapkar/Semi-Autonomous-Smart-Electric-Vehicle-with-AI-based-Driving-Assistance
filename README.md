# Semi-Autonomous Smart Electric Vehicle with AI-Based Driving Assistance

Welcome to the Semi-Autonomous Smart Electric Vehicle (SASEV) project! This project integrates advanced AI-based driving assistance technologies into an electric vehicle (EV) to enhance safety, convenience, and energy efficiency. The vehicle is designed to provide a semi-autonomous driving experience, incorporating features that support both the driver and the environment.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Project Overview
The Semi-Autonomous Smart Electric Vehicle (SASEV) is an innovative project that focuses on integrating AI-driven features into an electric vehicle. The primary goal is to enhance the driving experience by providing semi-autonomous capabilities that include smart parking, adaptive lighting, efficient battery management, and real-time pothole detection.

## Features
1. **Self-Parking System**
   - Utilizes AI and sensor data to autonomously park the vehicle in tight spaces.
   - Supports both parallel and perpendicular parking.

2. **Adaptive Headlight Intensity Control**
   - Automatically adjusts the headlight brightness based on ambient light conditions and the presence of other vehicles.
   - Enhances night driving safety and energy efficiency.

3. **Battery Management System (BMS)**
   - Monitors and manages the battery's state of charge, health, and thermal conditions.
   - Ensures optimal performance and longevity of the EV battery.

4. **AI-Based Pothole Detection**
   - Real-time detection of potholes and rough terrains using AI algorithms and sensor data.
   - Provides warnings to the driver and adjusts the suspension system accordingly.

## System Architecture
The SASEV system architecture is divided into several key modules:
- **Sensor Integration:** Collects data from various sensors (cameras, LiDAR, ultrasonic sensors) to perceive the vehicle's environment.
- **AI Processing Unit:** Processes sensor data using machine learning algorithms to make real-time decisions.
- **Control Systems:** Executes commands for steering, acceleration, braking, and other vehicle functions.
- **Human-Machine Interface (HMI):** Provides the driver with feedback and options to interact with the system.
- **Communication Module:** Enables V2X (Vehicle-to-Everything) communication for enhanced situational awareness.

## Technologies Used
- **Machine Learning & AI:** TensorFlow, PyTorch
- **Programming Languages:** Python, C++
- **Embedded Systems:** Raspberry Pi, Arduino
- **Sensors:** LiDAR, Ultrasonic sensors, Cameras
- **Communication Protocols:** CAN Bus, V2X
- **Software Tools:** MATLAB, Simulink

## Installation
To install and run the project on your system, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/SASEV.git
    cd SASEV
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Flash the Embedded System**
   - Follow the instructions in the `/embedded/README.md` file to flash the microcontroller with the necessary code.

4. **Run the Simulation**
    ```bash
    python run_simulation.py
    ```

## Usage
- **Simulation Mode**
  - Launch the simulation to test the vehicle's features in a controlled environment.
  - Use the HMI dashboard to monitor and interact with the vehicle in real-time.

- **Real-World Testing**
  - Deploy the system on a real vehicle by following the instructions in the `/deployment/README.md`.
  - Ensure all safety protocols are followed during testing.



## Contact
If you have any questions or suggestions, feel free to contact us:

- **Abhishek Kulapkar** - [abhishekkulapkar@gmail.com]

