# Stepper Motor Control Using NodeMCU (ESP8266) and ULN2003A Driver

This project demonstrates how to control a **unipolar stepper motor** using a **NodeMCU V3 (ESP8266)** and a **ULN2003A motor driver**. The simulation is built and tested using **Proteus 8 Professional**.

## Components Used

- NodeMCU V3 (ESP8266)
- ULN2003A Motor Driver
- Unipolar Stepper Motor (e.g., 28BYJ-48)
- External Power Supply (for motor)
- Proteus 8 Professional (for simulation)

## Circuit Overview

- NodeMCU controls the stepper motor by sending digital signals to the ULN2003A.
- ULN2003A amplifies the current needed by the stepper motor.
- External power is used to prevent overloading the NodeMCU.

### Connections:

| NodeMCU Pin | ULN2003A Pin | Description |
|:-----------:|:------------:|:-----------:|
| D2          | IN1 (1B)      | Stepper motor coil A |
| D3          | IN2 (2B)      | Stepper motor coil B |
| D4          | IN3 (3B)      | Stepper motor coil C |
| D5          | IN4 (4B)      | Stepper motor coil D |
| GND         | GND           | Common ground |

The motor coils are connected to outputs 16, 15, 14, and 13 of the ULN2003A.

---

## Wiring
![Circuit](https://github.com/user-attachments/assets/aca2df42-d82d-4893-b7ac-9edc498566b0)



---

