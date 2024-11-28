# Syringe Pump Project

## 📌 Introduction  
The Syringe Pump project aims to develop a device that can precisely control the flow of fluids by using a syringe. These pumps are typically used in medical, laboratory, and research settings for delivering medications, chemicals, or biological substances at a controlled rate. The goal of this project is to design a syringe pump that ensures accurate dosing, adjustable flow rates, and user-friendly interface.

This project focuses on the automation of the syringe pump, allowing users to control parameters such as flow rate, volume, and time duration. The system will be designed with safety features to prevent over-pressurization, air bubbles, or other potential failures.

## 📊 Project Flow Chart  
Below is a simplified flowchart of the syringe pump operation:  
![Flow Chart](D:/Code/2B/1.jpg)

## 🖧 Block Diagram  
The system comprises the following blocks:  
- **User Interface (UI):** Allows users to input desired parameters and view status.  
- **Microcontroller:** Processes user input and controls the pump motor.  
- **Motor Driver:** Drives the motor to operate the syringe.  
- **Feedback Sensors:** Ensure precision and detect potential errors.  
- **Power Supply:** Provides necessary power to the components.  

![Block Diagram](D:/Code/2B/2.jpg)

## 🎭 State Diagram  
The state diagram for the syringe pump system is as follows:  
- **Idle State:** System awaits user input.  
- **Setting State:** User configures parameters like flow rate and volume.  
- **Running State:** Pump operates based on the input parameters.  
- **Error State:** System pauses to alert users of any errors (e.g., occlusion).  
- **Complete State:** Pump stops after delivering the programmed volume.

![State Diagram](D:/Code/2B/3.jpg)
