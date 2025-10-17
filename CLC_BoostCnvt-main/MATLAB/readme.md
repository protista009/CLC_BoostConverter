# CLC Boost Converter

A closed-loop, PID-controlled boost converter for DC-DC voltage regulation, featuring MATLAB simulation models and adaptable microcontroller firmware. This project demonstrates real-time analog feedback and PWM control for stable power supply.

---

## Features

- Closed-loop PID control for accurate voltage regulation
- MATLAB/Simulink models for system simulation
- Example firmware for analog and PWM-capable microcontrollers

---

## Hardware and Pinout

- Output voltage sensed via resistor divider to analog input
- PWM output pin drives MOSFET gate in boost converter stage
- Compatible with various microcontrollers

---

## Setup and Usage

1. Connect voltage divider to microcontroller analog input
2. Connect PWM-capable output pin to MOSFET gate driver
3. Power the system safely
4. Upload and run the firmware
5. Monitor real-time feedback for verification

---

## Requirements

- MATLAB/Simulink (for simulation)
- Microcontroller with analog input and PWM output (e.g., Arduino, STM32, ESP32)
- Circuit prototyping tools


