Overview
========
The lpuart_edma Example project is to demonstrate usage of the KSDK lpuart driver.
In the example, you can send characters to the console back and they will be printed out onto console
 in a group of 8 characters.

Toolchain supported
===================
- GCC RISC-V Embedded 7.1.1
- RISC-V Eclipse IDE 4.7.2

Hardware requirements
=====================
- Mini/Micro USB cable
- RV32M1-VEGA board
- Personal Computer

Board settings
==============
No special is needed.

Prepare the Demo
================
1.  Connect a mini USB cable between the PC host and the OpenSDA USB port on the board.
2.  Open a serial terminal on PC for OpenSDA serial device with these settings:
    - 115200 baud rate
    - 8 data bits
    - No parity
    - One stop bit
    - No flow control
3.  Download the program to the target board.
4.  Reset the SoC and run the project.

Running the demo
================
When the demo runs successfully, the log would be seen on the OpenSDA terminal like:

~~~~~~~~~~~~~~~~~~~~~~~~~~~
LPUART EDMA example
Send back received data
Echo every 8 characters
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Customization options
=====================

