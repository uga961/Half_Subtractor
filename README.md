# CMOS Half Subtractor Project

## Overview

This project involves designing, simulating, and analyzing a **CMOS Half Subtractor** using **Cadence Virtuoso**. The Half Subtractor is a fundamental combinational circuit used for binary subtraction, generating a **difference (D)** and a **borrow (B)** output.

## Software & Tools Used

- **Cadence Virtuoso** (for schematic capture, layout, and simulation)
- **Assura** (for DRC and LVS verification)
- **Analog Design Environment (ADE)** (for waveform analysis)

## Project Workflow

### Schematic Design

- Designed using **Virtuoso Schematic Editor**.
- Constructed using **AND, NOR, and NOT gates** from a custom-built library.
- Verified through **Transient analysis**.

### Layout Design

- Created using **Virtuoso Layout Editor**.
- Optimized for **area efficiency** and minimal parasitics.
- Design Rule Check (**DRC**) performed for layout validation.

## Technical Specifications

- **Technology Node**: 90nm (as per design constraints)
- **Supply Voltage (VDD)**: 1V
- **Logic Operation**: Half Subtractor (D = A ⊕ B, B = A'B)

## Results & Observations

- **Schematic Simulation**: Verified correct Half-Subtractor functionality.
- **Layout Optimization**: Ensured minimal area and **DRC compliance**.
- **Post-Layout Simulation**: Observed deviations due to parasitic capacitance and resistance.

## Reference Images

- **Half\_Subtractor\_Schematic**
  
  ![Half_Sub_Schematic](https://github.com/user-attachments/assets/6556a3d7-37b5-4659-a932-f8e7daadb436)

- **Half\_Subtractor\_Test**

  ![Half_Sub_Test](https://github.com/user-attachments/assets/c32b6984-cc4c-4396-972a-a9c9138f7fd7)

- **Half\_Subtractor\_ADE**
  
  ![Half_Sub_ADE](https://github.com/user-attachments/assets/9c513f03-507b-41fe-9529-e28acb2c6490)


## Caution

- This project is designed using **custom NAND, NOR, and NOT gates** from a self-built library.
- **Copying this file alone will not work**—users need to **add the NAND, NOR, and NOT gates** to their own library first to use it correctly.

---

*This project belongs to me and is intended for educational and research purposes only. It should not be used directly for other purposes without permission.*

