# Dashboard-design-using-CAN-bus
Dashboard Design Using CAN Bus

This project demonstrates the implementation of a vehicle dashboard system utilizing the Controller Area Network (CAN) protocol. The system is designed to monitor and display critical vehicle information, such as fuel level, indicator status, and engine temperature, by enabling communication between various car components.
Project Overview

The dashboard system comprises multiple nodes connected via the CAN bus:

    Fuel Node: Monitors and reports the fuel level.

    Indicator Node: Detects and communicates the status of turn indicators.

    Main Node: Central unit that aggregates data from other nodes and displays it on an LCD screen.

The system is programmed to collect and display real-time data, providing essential information to the driver.
Features

    Real-time monitoring of vehicle parameters.

    Communication between nodes using the CAN protocol.

    Display of information on an LCD screen.

Hardware Requirements

    LPC21xx microcontroller.

    LCD display.

    CAN transceiver module.

    Various sensors for fuel level, temperature, and indicator status.

Software Requirements

    Keil µVision IDE.

    CAN protocol libraries.

    LCD and sensor drivers.

Installation and Setup

    Clone the repository:

    Open the project in Keil µVision IDE.

    Compile and upload the code to the LPC21xx microcontroller.

    Connect the hardware components as per the schematic.

    Power on the system to begin monitoring.

File Descriptions

    FUEL_NODE.c: Code for the fuel monitoring node.

    INDICATOR_NODE.c: Code for the indicator status node.

    MAIN_NODE.c: Code for the central unit aggregating data and controlling the LCD.

    LCD_defines.h: Header file containing LCD control definitions.

    MAJOR_PROJECT.axf: Compiled project file.

    MAJOR_PROJECT.hex: Hex file for programming the microcontroller.

