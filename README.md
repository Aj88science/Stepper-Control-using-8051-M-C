# Stepper-Control-using-8051-M-C

The AT89C51 is an 8-bit microcontroller based on the Intel 8051 architecture. It features 40 pins, including various ports and control pins that are essential for its operation and interaction with other devices. Here's a detailed description of the pins and ports of the AT89C51:
System Overview
The AT89C51 microcontroller outputs control signals on Port 2 pins (P2.0 to P2.3), which are connected to the input pins (IN1 to IN4) of the L293D motor driver.
The L293D motor driver then drives the stepper motor coils using its output pins (OUT1 to OUT4).
The motor’s power supply is connected to VCC2 on the L293D, while VCC1 provides the logic voltage for the L293D.
The common wire of the stepper motor (if it has one) should be connected to the power supply corresponding to the stepper motor’s voltage rating (not directly involved in the L293D connections).
This configuration allows the AT89C51 to control the unipolar stepper motor through the L293D motor driver, enabling precise stepper motor control for applications like the rover.
Components:
- AT89C51 Microcontroller
- L293D Motor Driver IC
- Unipolar Stepper Motor 
