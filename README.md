# Servo Testbed Project

Team members:
- Jayden
- Aleks
- Dwayne
- Cason

# Project Overview

Design and print a PCB to test the functionality of different types of servos for the SDSU Mechatronics Club during the 2026 Fall semester
- "create a pcb board that outputs a pwm signal that has .5-2.5ms high period (just like intro project) that is manually controlled by potentiometer"

PCB schematic and layout designed using KiCAD V10.0

MCU programmed using STM32CubeIDE in C

# Capabilities

- STM32F103C8T6 controlled

- Testing mode control:
  - Manual potentiometer sweep
  - Automatic sweep, potentiometer speed control
  - X degree step increment, potentiometer speed control
  - WIP
  
- 12V, 8.4V, 7.4V, 6V, 5V, 3V3 voltage outputs
  - 3/4 of each, two 12V outputs. 16/22 outputs total
  - reverse polarity protection up to (insert pmos ratings)

- Status display
  - Current draw
  - Expected output angle
  - Potentiometer angle
  - PWM data (duty cycle, frequency)

- 2 DC motor outputs
  - CAN control
