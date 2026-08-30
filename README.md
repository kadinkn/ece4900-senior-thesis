# ECE4900 Floating Photovoltaic Power System

Senior Thesis project focused on designing and testing a small-scale floating photovoltaic power system with:

- Custom synchronous buck converter
- MPPT control
- STM32G474 microcontroller
- PV and battery voltage/current sensing
- Temperature sensing
- Real-time UART telemetry
- Input and output protection
- Battery charging interface

## Project Status

Current work includes:

- Buck converter power stage
- Gate driver circuitry
- 12 V auxiliary supply
- 3.3 V MCU supply
- STM32 support circuitry
- SWD programming/debug interface
- PWM control connections
- PV voltage/current sensing
- Battery voltage/current sensing
- Temperature sensing
- UART telemetry
- PV input protection
- Battery output protection

PCB layout, design-rule checks, manufacturing files, firmware, and hardware testing are still in progress.

## Main Hardware

- MCU: STM32G474CBT6TR
- Gate Driver: TI UCC27301A
- Buck MOSFETs: TI CSD18540Q5B
- PV Panel: Renogy 100 W
- Battery: Renogy 12.8 V 20 Ah LiFePO4

## Repository Files

Open the `.kicad_pro` file in KiCad to load the project.

The repository will eventually contain:

- KiCad schematic
- PCB layout
- BOM
- Datasheets/reference documents
- Manufacturing files
- Firmware
- Testing documentation

## Notes

This is a Rev 0 prototype design and is still under active development and review.
