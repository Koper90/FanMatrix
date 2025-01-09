# FanMatrix

![image](https://github.com/user-attachments/assets/46d7d377-fca2-4142-a8db-c55ef6df10a0)


This board was created out of necessity, as I found myself needing more fan and thermistor ports for my own 3D printers. It's perfect for expanding cooling systems, temperature monitoring, and fan control setups in Klipper-based 3D printers, with minimal additional cost.

This repository contains the design files and firmware for a low-cost PCB-based port expander, specifically designed to run Klipper firmware for controlling cooling and sensor peripherals in 3D printing. The board takes in 24V DC and steps it down to 12V and 5V, each capable of delivering up to 1A of current, making it ideal for controlling fans and sensors.

Key features include:

- 5 PWM fan outputs with selectable fan voltage via jumper (12V or 5V).
- 4 tacho fan outputs to monitor fan RPM.
- 9 thermistor inputs for temperature monitoring.
- STM32 32-bit ARM Cortex M0 microcontroller for efficient processing and control.
- A serial connection via USB-C allows easy communication with external systems.
- 3 additional ports available for expansion with extra peripherals.

Designed to run Klipper firmware for seamless integration with 3D printing systems.
Designed with low cost in mind for accessible integration into projects.
