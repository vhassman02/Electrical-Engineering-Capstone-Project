README Markdown File
Description: Complete set of design and firmware files for the Fan Test Fixture controller powered by STM32 microcontroller. 

---------------------
Design Files: 
* PCB Files - Contains drill and artwork gerber files for final PCB design
* System block diagram
* Schematic
* STM32 pin assignments

---------------------
STM32 Firmware Files: 
* Full_Test - Final testing code used to debug ADC, MODBUS, and SPI functions as separate header files. 
* Full_code_beta1 - Final version of firmware used on project. All functions are implemented as separate header files. 
* GPIO-Test - Simple program for testing STM32 GPIO pins
* MODBUS-RS485-Test - Simple program for testing MODBUS RS485 functionality
* SPI-Test - Tests SPI communication functionality on STM32
* SPI_MODBUS_Test - Tests SPI and MODBUS interfaces implemented as header files driven by main.c
* UART-Test - Simple program for testing UART (USB) functionality on STM32
