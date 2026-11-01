# STM32 – AMD Kria KV260 Interface PCB

**A Four-Layer PCB Design for STM32F103C8T6 and AMD Kria KV260 Interfacing**

## Project Overview

This project focuses on designing a four-layer PCB interface between an STM32F103C8T6 microcontroller and the AMD Kria KV260 development platform.

The board is designed to provide communication and GPIO interfacing through SPI, UART and general-purpose digital signals using a Pmod-style connector.

The PCB schematic, component footprints, routing, copper layers and manufacturing output files were developed using KiCad 10.0.

## Key Features

- STM32F103C8T6 microcontroller interface
- Four-layer PCB architecture
- SPI communication interface
- UART debugging interface
- GPIO signal interfacing
- SWD programming and debugging connector
- External regulated 3.3V power input
- Dedicated ground plane
- PCB layout and 3D visualization
- Gerber and drill file generation

## Hardware Architecture

**Main Controller:** STM32F103C8T6

**Target Platform:** AMD Kria KV260

**Communication Interfaces:**
- SPI – SCK, MOSI, MISO and CS
- UART – TX and RX
- GPIO – FPGA_GPIO1, FPGA_GPIO2, FPGA_INT and FPGA_RESET
- SWD – Programming and debugging

## PCB Design Specifications

| Parameter | Specification |
|---|---|
| Design Tool | KiCad 10.0 |
| Microcontroller | STM32F103C8T6 |
| PCB Layers | 4 |
| Board Material | FR4 |
| Board Thickness | 1.6 mm |
| Copper Layers | F.Cu, In1.Cu, In2.Cu, B.Cu |
| Power Input | External regulated 3.3V |
| Ground Plane | In1.Cu |
| Main Communication | SPI and UART |

## Tools Used

- KiCad 10.0 – Schematic capture and PCB layout
- KiCad 3D Viewer – PCB visualization
- KiCad Design Rules Checker – PCB design verification
- Gerber Plot – Manufacturing file generation

## Repository Structure

```text
STM32-Kria-KV260-Interface-PCB/
│
├── README.md
├── Schematic/
├── PCB_Design/
│   ├── Gerber_Files/
│   └── PCB_Project/
├── Documentation/
└── Images/
```

## Project Status

**Work in Progress (WIP)**

- Schematic design completed.
- Four-layer PCB stackup configured.
- Component placement and initial routing completed.
- 3D PCB model generated.
- Gerber and drill files generated.
- Initial DRC completed with zero reported violations and zero unconnected items.
- Hardware validation and communication testing are pending.

The current design is intended for educational, portfolio and engineering documentation purposes. It has not been fabricated or hardware-validated.

## Future Improvements

- Verify KV260 Pmod pin assignments against official hardware documentation.
- Perform hardware testing after fabrication.
## Project Gallery

### PCB Layout
![PCB Layout](PCB%20layout.jpg)

### 3D PCB View
![3D PCB View](3D%20view.jpg)

### PCB Editor and DRC Output
![PCB Editor and DRC](PCB%20editor%20and%20DRC%20output.jpg)
