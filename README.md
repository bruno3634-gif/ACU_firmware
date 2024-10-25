# LART T24_E (Voidster) Safety Device Project

This project is developed for the Leiria Academic Racing Team (LART) and focuses on the T24_E vehicle, affectionately known as "Voidster."

#Overview
The primary goal of this unit is to serve as a crucial safety device for the vehicle's autonomous control system. It is designed to monitor and manage the vehicle's operations when in autonomous mode, ensuring safety and reliability.

# Key Features
Emergency Brake System (EBS) Activation: Enables the emergency brake system to ensure immediate vehicle halting in critical situations.

Pneumatic Pressure Monitoring: Reads pneumatic pressure from the EBS actuators to monitor their functionality.

Mission Selection and Transmission: Selects the autonomous mission and communicates it to the central control computer.

Responsiveness Check: Monitors the responsiveness of the control computer to ensure continuous safe operation.

Autonomous System Status Indicator (ASSI) Control: Manages the ASSI based on the current state of the selected mission.

Emergency Shutdown Circuit: Engages the shutdown circuit automatically in case of emergencies.

# Technical Details
The firmware for this unit is developed to run on a Teensy 4.1 microcontroller. It communicates with the vehicle's autonomous computer and other systems via a CAN bus, enabling efficient data exchange and control.
