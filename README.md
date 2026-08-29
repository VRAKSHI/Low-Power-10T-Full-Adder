# Low-Power 10T Full Adder

## Project Overview

This project focuses on the design and power optimization of a 10-transistor (10T) full adder for low-power VLSI applications.

The circuit was implemented and analyzed using Cadence Virtuoso with a 45 nm CMOS process. The project investigates different techniques for reducing power dissipation while maintaining the functionality of the full adder.

## Tools and Technology

- Cadence Virtuoso
- 45 nm CMOS Technology
- ADE L
- CMOS
- Low-Power VLSI
- 10T Full Adder

## Methodology

The 10T full adder was implemented using CMOS inverters and evaluated through circuit-level simulations.

The following power-reduction techniques were investigated:

1. Supply voltage reduction from 2 V to 1 V
2. Process variation analysis using TT and SF model libraries
3. Increasing MOSFET channel length from 45 nm to 90 nm
4. Combining the above optimization techniques

## Simulation

Transient simulations were performed to verify the functionality of the 10T full adder and evaluate its power characteristics.

## Results

The base design operated at a supply voltage of 2 V.

The optimized design achieved a reduction in power from:

**29.58 µW → 7.099 µW**

This corresponds to approximately **76% reduction in power** compared with the base design.

## Conclusion

The project demonstrates that combining voltage scaling, process variation analysis, and device-level optimization can significantly reduce power dissipation in a 10T full adder.

## Project Report

The detailed project report is available in the `report` folder.
