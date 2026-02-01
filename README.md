# ti-mspm0-development-board

## Overviwe
Custom development board designed around a Texas Instruments MSPM0 microcontroller.
The project covers the complete hardware design process, from component selection and
datasheet analysis to schematic capture and PCB layout on KiCad.

## Objectives
- Design a minimal yet expandable development platform for the MSPM0 family
- Follow TI hardware design guidelines
- Use I2C and UART communication protocols

## Microcontroller
- Texas Instruments MSPM0G3507SPTR
- 80MHz Arm® Cortex®-M0+ MCU

## Hardware Design
- Power supply design based on TI recommendations using a USB-C Connector
- External 8MHz Crystal implementated
- Reset (NRST) and boot configuration
- Programming and debugging interface with Tag-Connect ARM Cortex SWD JTAG connector
- Decoupling and filtering strategy according to component datasheet

## Design Decisions
Key design decisions were made based on datasheet specifications and TI application notes.
