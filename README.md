# Smart Spray Automation System (BASCOM-AVR)

An automatic spray control system developed using AVR microcontroller and BASCOM programming language.

This project demonstrates low-level embedded system design without Arduino abstraction layer.

---

## Overview

The Smart Spray system is designed to automate spraying operations using direct AVR microcontroller programming.

Unlike Arduino-based implementations, this version is developed using BASCOM-AVR, providing deeper control over hardware resources.

Applications include:

- Agricultural automation
- Disinfection systems
- Industrial fluid control
- Timed spray mechanisms

---

## Features

- Direct AVR microcontroller programming
- Sensor-triggered spray activation
- Relay or transistor-based pump control
- Adjustable timing logic
- Proteus simulation included
- HEX file available for deployment

---

## Hardware Components

- AVR Microcontroller (e.g., ATmega series)
- Relay module or transistor driver
- Spray pump / DC motor
- Trigger sensor
- Power supply

---

## Software

- BASCOM-AVR source file (.bas)
- Proteus simulation project
- Compiled HEX file

---

## Project Structure

```
Smart-Spray-BASCOM/
/
/// firmware/
/ /// smart_spray.bas
/
/// simulation/
/ /// proteus-project.pdsprj
/
/// images/
    /// simulation.png
```

---

## Working Principle

1. The sensor detects trigger condition.
2. AVR processes input directly through configured I/O registers.
3. Output pin activates relay or transistor.
4. Pump runs for predefined duration.
5. System returns to monitoring state.

---

## Engineering Note

This project demonstrates:

- Low-level I/O configuration
- Direct register manipulation
- Timer-based control logic
- Embedded automation without Arduino framework

---

## Future Improvements

- Interrupt-based sensor handling
- Power optimization mode
- LCD user interface
- IoT module integration
- PCB layout design

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by Soheil Ahmadi  
Embedded systems and automation project.
