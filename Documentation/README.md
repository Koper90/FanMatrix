This document outlines the common features of the board that you are likely to use.

## Main Features
![annotely_image (1)](https://github.com/user-attachments/assets/01c30727-514e-44ff-8f3a-99f13c0eb6f8)

The board operates on a 24V DC power supply and includes the following inputs and outputs (I/O):

- 5 PWM 4-pin fan outputs
- 4 ground-switched fan outputs with tacho feedback
- 9 thermistor inputs for temperature sensing

Each fan output is equipped with a voltage selector, allowing the user to choose between 5V, 12V, or 24V DC depending on the requirements of the connected fan.

The board also features a fuse slot, and it is recommended to use a 3 AMP automotive fuse to protect the circuit from overcurrent conditions.

## Voltage selector for fan outputs

To set the appropriate voltage for the fan output, use the jumper and place it in the correct position on the voltage pin selector. The board is marked with the available voltages. For example, in the image below, putting the jumper in the orientation shown within the red rectangle selects 24V for the fan output.

Ensure that the jumper is securely placed and matches the required voltage for your device before powering on the system.
![image](https://github.com/user-attachments/assets/ecf66eda-9971-4b7f-b88f-c0f8f3875c10)


## LED indicator

LED indicators for the 5V and 12V DC busbars, which are used to verify whether 5V and 12V power is available.

## Boot and reset keys

This boot button needs to be pressed to put the board in DFU mode to flash it with the klipper firmware. The board will show up as "Device in DFU Mode" to ```lsusb``` and then should show up in ```dfu-util --list```





