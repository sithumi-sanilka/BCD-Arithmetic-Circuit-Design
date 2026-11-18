# BCD Arithmetic Circuit Design and Simulation

## Overview

This project was developed as part of the Digital Electronics (IE1044) module at the Sri Lanka Institute of Information Technology (SLIIT).

The project focuses on designing and simulating a digital arithmetic circuit capable of performing **addition, subtraction, and multiplication** on two Binary-Coded Decimal (BCD) inputs.

The entire circuit was developed using Proteus simulation software, utilizing fundamental digital electronic components without microcontroller-based processing.

## Key Features

- **BCD Addition:** Implemented using 7483 4-bit binary adder ICs with BCD correction logic.
- **BCD Subtraction:** Designed using two's complement arithmetic with conditional correction for negative results.
- **BCD Multiplication:** Developed using AND-gate partial product generation and addition circuits.
- **BCD Conversion:** Integrated conversion logic to represent arithmetic results in BCD format.
- **7-Segment Display:** Displays arithmetic results in decimal format.
- **Circuit Simulation:** Designed and tested the digital circuits using Proteus.

## Circuit Design

The project consists of three main arithmetic units.

### 1. BCD Adder

Uses two 4-bit binary adder ICs to perform addition. Correction logic adds binary 0110 when required to produce valid BCD output.

### 2. BCD Subtractor

Performs subtraction using the two's complement method. Additional logic handles negative results by conditionally applying another two's complement operation.

### 3. BCD Multiplier

Generates partial products using AND gates and combines them through addition circuits. The result is converted into the required BCD representation.

