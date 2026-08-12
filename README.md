# 32×32 SRAM Design using TSMC 28nm

A complete 32 × 32-bit SRAM memory architecture designed and analyzed using the TSMC 28nm technology node.

## Project Overview

This project focuses on the design and analysis of a high-speed SRAM subsystem including:

- 6T SRAM Cell Design
- 32×32 SRAM Array
- 5-bit Address Adder
- 5-to-32 Decoder
- Differential Sense Amplifier
- Noise Margin Analysis
- Timing Optimization
- Bitline and Precharge Optimization

## Key Features

- TSMC 28nm Technology
- Static Noise Margin (SNM) Analysis
- Ripple Carry / Manchester Carry Optimization
- Differential Sensing
- Hierarchical Decoder Design
- Read Stability Verification
- Delay and Power Optimization

## Performance Summary

| Metric | Result |
|--------|--------|
| Total Read Latency | 216.456 ps |
| Adder Delay | 37 ps |
| Optimized Adder Delay | 29.5 ps |
| Sense Amplifier Delay | 19.6 ps |
| Max Frequency | ~4.6 GHz |

## SRAM Architecture

The SRAM system consists of:

1. 5-bit Address Adder  
2. 5-to-32 Decoder  
3. 32×32 SRAM Array  
4. Differential Sense Amplifier Array  

## Report

Full project report available here:

[SRAM Project Report](SRAM_Project_Report.pdf)

## Tools Used

- Cadence Virtuoso
- SPICE Simulation
- TSMC 28nm PDK

## Future Improvements

- CLA-based Adder
- Domino Logic Decoder
- ECC Integration
- Low Power Modes
