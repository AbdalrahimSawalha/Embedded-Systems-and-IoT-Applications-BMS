# IP-Based Building Automation and Integration of BACnet, DALI, and KNX Systems 🏢

---

## Overview 📘

- This project presents the design of an integrated smart control system for a university auditorium.

- The system is based on a multi-protocol building automation architecture where control, execution, and supervision layers are clearly separated.

- The implementation combines:

- KNX as the central control layer

- DALI for lighting execution

- BACnet for HVAC execution

- IP Application for monitoring and supervisory interaction

- The main concept of the project is architectural integration rather than isolated subsystem configuration.

---

## System Architecture 🧩

- The system follows a layered design:

- KNX acts as the central decision-making core.

- DALI executes lighting commands.

- BACnet executes HVAC control.

- The IP layer provides visualization and supervision.

- Control logic remains centralized within KNX, while gateways perform protocol translation only.

---

## Folder Structure 📁

- This Folder contains:

- project.knxproj  
→ Full implementation of the system inside ETS.  
This file represents the complete practical application of the project.

- IOT Project.pdf  
→ Full academic report and detailed technical documentation.  
The complete explanation of architecture, message translation, addressing, and system design is provided inside this document.

---

## How to Use ⚙️

- Open ETS software.

- Import the file:  
project.knxproj

- Review the configuration, addressing, and gateway mappings.

- For theoretical explanation and system analysis, refer to the PDF report.

---

## Author 👨‍💻

Abdalrahim Sawalha  

---
