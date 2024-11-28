# Syringe Pump Final Project

## 📌 Introduction
The Syringe Pump is a precision device used to control the delivery of fluids at controlled rates, often used in medical, laboratory, and research environments. This project involves designing and developing a syringe pump system that can provide accurate, repeatable delivery of fluids for various applications. Our goal is to create a user-friendly and efficient syringe pump system using microcontroller-based control, sensors, and actuators for fluid dispensing.

## 📊 Project Flow Chart
Below is a simplified flowchart of the syringe pump operation:
1. **User sets the desired flow rate and volume.**
2. **System verifies settings and checks for syringe installation.**
3. **Pump motor drives syringe to deliver fluid at the specified rate.**
4. **Feedback sensors monitor flow accuracy and detect errors (e.g., occlusions).**
5. **System stops automatically after delivering the programmed volume.**

## 🖧 Block Diagram
The system comprises the following blocks:
- **User Interface (UI):** Allows users to input desired parameters and view status.
- **Microcontroller:** Processes user input and controls the pump motor.
- **Motor Driver:** Drives the motor to operate the syringe.
- **Feedback Sensors:** Ensure precision and detect potential errors.
- **Power Supply:** Provides necessary power to the components.

## 🎭 State Diagram
The state diagram for the syringe pump system is as follows:
1. **Idle State:** System awaits user input.
2. **Setting State:** User configures parameters like flow rate and volume.
3. **Running State:** Pump operates based on the input parameters.
4. **Error State:** System pauses to alert users of any errors (e.g., occlusion).
5. **Complete State:** Pump stops after delivering the programmed volume.

## 🚀 Getting Started

### Prerequisites
- A basic understanding of electronics and microcontrollers.
- Familiarity with programming languages like C/C++ (for Arduino).

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/syringe-pump.git
