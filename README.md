# Syringe Pump Final Project

## 📌 Introduction
Our project focuses on designing a smart syringe pump that delivers precise and controlled volumes of fluid for medical applications. Syringe pumps are essential in healthcare settings for administering medication, delivering nutrients, or other medical fluids. We aim to integrate advanced features such as automation, safety mechanisms, and user-friendly interfaces to enhance usability and efficiency.

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

## 👥 Team Members
**Nguyen Quoc Trung Nhan
**Au Doan Doan Truc
**Pham Hoang Anh Thu
**Kim Phuong Thuy
