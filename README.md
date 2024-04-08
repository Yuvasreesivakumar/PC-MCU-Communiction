# PC-MCU-Communiction

This project provides an example of custom EEPROM access using Embedded C, showcasing how to read from and write to EEPROM memory using register-level operations. Instead of relying on the standard EEPROM library provided by development platforms like Arduino, this project demonstrates direct register manipulation to achieve EEPROM access. By implementing EEPROM read and write operations at the register level, developers gain a deeper understanding of EEPROM functionality and can optimize memory management for specific application requirements.

Key Features
- Demonstrates EEPROM read and write operations using Embedded C.
- Offers a lightweight alternative to the standard EEPROM library for efficient memory management.
- Provides flexibility and control over EEPROM memory management in microcontroller programming.

Usage
1. Connect your microcontroller unit (MCU) board to your computer.
2. Upload the provided Embedded C code to your MCU board using the appropriate development environment.
3. Open the Serial Monitor or equivalent terminal program to view the transmitted and received data.
4. Verify that the sketch performs EEPROM read and write operations correctly without using the built-in EEPROM library.

Components Used
- Microcontroller unit (MCU) compatible with Embedded C development
- Serial communication interface (USB cable)
- Host computer (for running the Python scripts and IDE)

Python Script
The Python script (transmit_data.py) included in the repository demonstrates how to transmit data from a file to the MCU board over the serial port. It reads data byte by byte from a file (Data.txt) and sends it to the MCU for storage in EEPROM memory.

To run the Python script:
python transmit_data.py

IDE Setup
Ensure that you have the necessary development environment and toolchain installed for programming your MCU board using Embedded C.

Highlights
- Gain a deeper understanding of EEPROM functionality in microcontroller programming.
- Optimize memory management for specific application requirements.
- Explore register-level operations for EEPROM access in Embedded C.
