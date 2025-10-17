# CLC Boost Converter

A closed-loop PID-controlled boost converter system featuring simulation models, hardware schematics, and microcontroller-agnostic control firmware. This project demonstrates real-time DC-DC voltage regulation using analog feedback and PWM control.

---

## Features

- Stable closed-loop PID voltage regulation
- MATLAB simulation files included
- Hardware schematics for buck and boost converters
- Example firmware for any microcontroller with analog input and PWM output

---

## Hardware and Pinout

- Output voltage sensed via resistor divider connected to an analog input pin.
- PWM output pin drives the power MOSFET gate in the boost converter.
- Adaptable to any microcontroller platform.

---

## Setup and Usage

1. Connect the voltage divider output to your microcontroller's analog input.
2. Connect a PWM-capable output pin to the MOSFET gate driver.
3. Power the circuit appropriately.
4. Upload the firmware to the microcontroller.
5. Monitor serial output (or equivalent) for regulation feedback.

