# Home Automation via Bluetooth
**Codtech IT Solutions Internship Project - Project 3**

A conceptual smart-home hardware model designed to wirelessly control household appliances (Lights, Fans, Relays) using a smartphone Bluetooth application and a central microcontroller hub.

## 📁 Project Submission Files
This repository contains the complete conceptual implementation details:
1. `Project_Report.txt`: Technical framework, circuit working methodology, and wireless architecture.
2. `App_Command_Dataset.csv`: Sample calibrated dataset mapping smartphone application string data to physical hardware switch relay states.
3. `UI_and_App_Concepts.txt`: Layout and specification matrix for the mobile application controller interface.

## ⚡ Core Concept & Wireless Logic
The framework shifts manual switchboards to an automated, wireless grid:
- **Control Interface:** The user presses a digital switch on a dedicated mobile app UI.
- **Wireless Link:** The smartphone transmits unique serial ASCII tokens wirelessly via Bluetooth frequencies.
- **Actuation Hub:** A central processing unit paired with a wireless transceiver captures the serial string and toggles mechanical electrical relay units to turn loads ON or OFF.
