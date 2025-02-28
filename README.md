# Autonomous Self-Driving RC Car

## Team Members:
- **Nageswara Janapareddy**, njanapar@buffalo.edu

## Project Objective
We propose to develop an autonomous RC car that uses machine learning and sensor integration for self-driving capabilities. The car will navigate its environment by using sensors such as a camera, ultrasonic sensors, and an IMU to make real-time driving decisions such as steering, obstacle avoidance, and path-following.

## Contributions
This project will combine machine learning techniques for real-time autonomous driving with hardware integration, including the development of software to process camera and sensor inputs, and control the motors. The unique aspect of this project is the integration of end-to-end machine learning models (such as a pre-trained PilotNet model) and sensor fusion (combining data from cameras, ultrasonic sensors, and an IMU) to allow the car to autonomously navigate a predefined track or area.

## Project Plan
We will use a Raspberry Pi or NVIDIA Jetson as the main processing unit for running the machine learning model and handling real-time data from the sensors. The project will require the following resources:
- Online resources for machine learning (TensorFlow, OpenCV)
- Documentation for hardware setup (camera, ultrasonic sensors, motor controllers)
- Raspberry Pi or Jetson Nano with appropriate software environment
- Pre-trained machine learning models (e.g., PilotNet)

We will implement a path-following model using computer vision techniques and sensor inputs. Additionally, we will train or fine-tune an end-to-end model to enable the car to autonomously adjust its steering and speed. As a potential extension of the project, we may also explore optimizing lap times on a race track, if feasible.

## Milestones/Schedule Checklist
- **Complete hardware setup (RC car, motors, sensors, microcontroller)**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 10
- **Install operating system and libraries (Raspberry Pi setup)**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 12
- **Set up camera, ultrasonic sensors, and IMU for real-time data collection**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 15
- **Integrate machine learning model (PilotNet or similar)**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 25
- **Test basic control system with manual input**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 30
- **Implement path-following and obstacle avoidance using sensor inputs**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 5
- **Create progress report**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 6
- **Test and refine the autonomous driving system**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 15
- **Optimize lap times on the race track (if feasible)**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 25
- **Create final presentation**
  - Assigned to: Nageswara Janapareddy
  - Due Date: May 6
- **Provide system documentation (README.md)**
  - Assigned to: Nageswara Janapareddy
  - Due Date: May 13

## Measures of Success
We will measure success based on the ability of the RC car to autonomously navigate a predefined track without human intervention. Partial credit will be given if:
- The car is able to detect and avoid obstacles in its path.
- The car demonstrates real-time path-following with smooth steering and speed adjustments.
- The system is able to process sensor data and control the car using an end-to-end machine learning model.
- If feasible, optimizing lap times and successfully navigating the track faster while maintaining stability will be considered an additional achievement.
