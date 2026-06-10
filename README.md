# DC-DC Buck Converter Simulation using LTspice

## Project Overview

This project demonstrates the design and simulation of a DC-DC Buck Converter using LTspice.

The converter steps down a 24V DC input voltage to approximately 12V DC using PWM switching control at 50 kHz.

## Circuit Specifications

| Parameter           | Value           |
| ------------------- | --------------- |
| Input Voltage       | 24V             |
| Output Voltage      | ~12V            |
| Switching Frequency | 50 kHz          |
| Duty Cycle          | 50%             |
| Inductor            | 220 µH          |
| Capacitor           | 470 µF          |
| Load Resistance     | 6 Ω             |
| Diode               | 1N5819 Schottky |

## Theory

For an ideal buck converter:

Vout = D × Vin

Where:

* D = Duty Cycle
* Vin = Input Voltage

For D = 0.5 and Vin = 24V:

Vout ≈ 12V

## Simulation Results

### Output Voltage

The converter successfully reduced the input voltage from 24V to approximately 12V.

### Inductor Current

The inductor current settled around 2A, matching theoretical calculations.

### Switching Node

The switching node waveform demonstrated proper PWM operation between ON and OFF states.

## Software Used

* LTspice 26.0.2
* GitHub

## Author

Md Shamsul Arefin Tanim

MSc Electronics Engineering
University of Hertfordshire


## Circuit Diagram

![Circuit Diagram](Full%20Circuit%20Diagram.jpg)

## Output Voltage Waveform

![Output Voltage](Vout%20Waveform.jpg)

## Inductor Current Waveform

![Inductor Current](Inductor%20Current%20Waveform.jpg)

## Switching Node Waveform

![Switching Node](SW%20Node%20Waveform.jpg)
