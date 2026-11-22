# Arduino Frequency Meter

## 1. Project Overview
This project aims to design and build a frequency meter using Arduino Uno.

The system is intended to measure electrical signal frequency and display the result on a 16x2 I2C LCD.

## 2. Project Objectives
- Measure digital and analog signals.
- Display frequency readings on an LCD.
- Develop multiple measurement ranges.
- Investigate a prescaler path for high-frequency signals.
- Test and calibrate the measurement system.

## 3. Current Hardware
- Arduino Uno R3
- 74HC14 Schmitt Trigger IC
- 16x2 I2C LCD
- External Function Generator
- Breadboard and connecting wires

## 4. Current Measurement Design
The current prototype uses:
- D2 for period measurement using an external interrupt.
- D5 / Timer1 external clock input for pulse counting.
- 74HC14 for signal conditioning.

## 5. Project Sections

| Folder | Description |
|---|---|
| 01_Code_Design | Arduino source code and code explanation |
| 02_Hardware | Components and circuit connections |
| 03_PCB_Design | Schematic, PCB layout and Gerber files |
| 04_Simulation | Simulation setup and results |
| 05_Testing_and_Calibration | Testing and calibration records |
| 06_Presentation | Presentation files and images |
| 07_Documentation | Project report, references and user guide |
| 08_Team_Guide | Instructions for team members |

## 6. Project Status
The prototype is under development.

A reading around 80 kHz has been observed in preliminary testing, but its accuracy has not yet been independently verified.

The 1 MHz and 100 MHz ranges are development targets, not confirmed performance specifications.

The high-frequency prescaler path is still under development.

## 7. Testing
All measured results should be recorded with:
- Function generator setting
- Measured frequency
- Signal waveform
- Measurement error
- Test notes

## 8. Team Collaboration
All team members should follow the instructions in:
`08_Team_Guide/HOW_TO_USE_GITHUB.md`

## 9. Repository
https://github.com/menamielad/Frequency-Meter
