### Fan and Thermistor Pin Assignments for FanMatrix Board

#### 4-Pin PWM Fan Pin Assignments
The following pins are used for controlling 4-pin PWM fans. Each fan has a designated PWM signal and a tachometer (TACHO) pin:

- **FAN 1**:  
  - PWM: `PB10`
  - TACHO: `PB11`

- **FAN 2**:  
  - PWM: `PB1`
  - TACHO: `PB2`

- **FAN 3**:  
  - PWM: `PB0`
  - TACHO: `PA7`

- **FAN 4**:  
  - PWM: `PA6`
  - TACHO: `PA5`

- **FAN 5**:  
  - PWM: `PA4`
  - TACHO: `PA3`

#### 3-Pin Fan Pin Assignments
These pins are used for 3-pin fans, where PWM is tied to GND, and a tachometer is provided for speed monitoring:

- **FAN 1**:  
  - PWM: `PA0`
  - TACHO: `PA1`

- **FAN 2**:  
  - PWM: `PB12`
  - TACHO: `PA2`

- **FAN 3**:  
  - PWM: `PB15`
  - TACHO: `PB14`

- **FAN 4**:  
  - PWM: `PA9`
  - TACHO: `PA8`

#### Thermistor Pin Assignments
The thermistor inputs are assigned to the following pins:

- **Therm0**: `PB9`
- **Therm1**: `PB8`
- **Therm2**: `PB7`
- **Therm3**: `PB6`
- **Therm4**: `PB5`
- **Therm5**: `PB4`
- **Therm6**: `PB3`
- **Therm7**: `PA15`
- **Therm8**: `PA14`

### Usage Notes
- Ensure that all connections are properly made according to the above pin assignments.
- The 4-pin fans use separate PWM and tachometer pins for precise speed control and monitoring.
- For 3-pin fans, PWM signals are tied to GND, so speed is controlled by manipulating GND, but tachometer readings are still available for monitoring.
- Thermistor inputs can be used to monitor temperature readings for various zones or components.

This pin documentation should serve as a reference for configuring and wiring the FanMatrix board.

