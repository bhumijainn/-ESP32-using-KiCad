**Custom ESP32 Microcontroller Development Board**
**Project Overview**
This repository contains the complete KiCad project files (schematics, PCB layouts, and netlists) for a custom ESP32-WROOM-32 development board. Designed with flexibility and robustness in mind, this board is ideal for developers, hobbyists, and engineers working on embedded systems and Artificial Intelligence of Things (AIoT) applications.

This project is open-source. Anyone is free to use these schematics to develop custom PCBs for personal or commercial use.

 **Hardware Specifications & Features**
Microcontroller: Core processing powered by the ESP32-WROOM-32 module (Wi-Fi & Bluetooth integrated).

USB-to-Serial Bridge: Incorporates the Silicon Labs CP2102N (QFN-28) for reliable and fast USB-to-UART communication.

Auto-Programming Circuitry: Utilizes S8050 BJT transistors for handling DTR/RTS signals, enabling automatic flashing without manual BOOT/EN button presses.

Power Management: Integrated NCP1117-3.3 Linear Voltage Regulator (LDO) to step down USB or JST connector power to a stable 3.3V logic level.

Hardware Protection: Equipped with ESD05V88D-LC TVS diodes on data lines for electrostatic discharge (ESD) protection, and 1N5819 Schottky diodes to prevent reverse polarity issues.

Connectivity: Standard Micro-USB connector (Molex) for power/data and an onboard JST (EH series) connector for alternative power inputs.

 **Software & Tools Used**
KiCad EDA: Used for complete schematic capture and PCB layout routing.

Manufacturing Files: Standard Gerber outputs, drill files, BOM, and Netlist (.net) are structured for seamless integration with PCB fabricators (e.g., JLCPCB, PCBWay).
