# Two-Stage Single-Ended Miller Compensated Operational Amplifier

## Project Overview

This project involves the design and simulation of a **Two-Stage Single-Ended Miller Compensated Operational Amplifier** using **Cadence Virtuoso** with the **gpdk 180nm process technology**. The operational amplifier is optimized for high performance, targeting specific gain, phase margin, and bandwidth specifications, with enhancements to stability using a resistor in series with the compensating capacitor.

## Specifications

- **Differential Gain**: 60 dB  
- **Phase Margin**: 60°  
- **Unity Gain Bandwidth (GBW)**: 30 MHz  
- **Operating Voltage**: 1.8 V (peak-to-peak)  
- **Output Voltage Swing**: 0.8 V to 1.6 V  
- **Slew Rate**: ≥ 20 V/µs  

## Design Highlights

1. **Miller Compensation**:  
   The amplifier uses Miller compensation to enhance stability and bandwidth. A resistor is introduced in series with the compensating capacitor to improve the phase margin, ensuring a robust design.

2. **Technology**:  
   Designed and simulated using the **gpdk 180nm CMOS process** in Cadence Virtuoso.

3. **Optimization for Performance**:  
   The design meets stringent requirements for gain, bandwidth, and slew rate while maintaining a wide voltage swing and phase margin.

4. **Applications**:  
   - Analog signal processing
   - Data acquisition systems
   - General-purpose amplification circuits

## Simulation and Results

The following simulations were conducted using **Cadence Virtuoso**:

1. **AC Analysis**:  
   - Verification of differential gain and unity gain bandwidth.  
   - Phase margin measurement to confirm stability.

2. **Transient Analysis**:  
   - Slew rate validation under large signal conditions.  
   - Output voltage swing assessment.  

3. **Monte Carlo Analysis** (optional):  
   - To evaluate the robustness of the design against process variations.

## Tools and Environment

- **EDA Tool**: Cadence Virtuoso  
- **Technology**: gpdk 180nm CMOS process  
- **Operating System**: Linux/Unix environment

