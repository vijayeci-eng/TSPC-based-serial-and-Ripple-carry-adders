# TSPC-Based-Serial-Adder-and-Ripple-Carry-Adder-Using-Microwind
Design and simulation of TSPC-based serial adder and ripple carry adder using dynamic logic in Microwind 3.0 for high-speed, low-power VLSI arithmetic circuits.

# TSPC-Based Serial Adder and Ripple Carry Adder Using Microwind

## Project Overview
This repository contains the design and simulation of **TSPC-based arithmetic circuits** implemented using **Microwind 3.0**.  
The project demonstrates high-speed and area-efficient arithmetic units using **True Single Phase Clock (TSPC)** dynamic logic.

### Designed Circuits
- TSPC Full Adder  
- TSPC D Flip-Flop  
- 4-bit TSPC Shift Register  
- TSPC Serial Adder  
- TSPC 2-bit Ripple Carry Adder  

---

## Tools & Technology
- **EDA Tool:** Microwind 3.0  
- **Logic Style:** Dynamic TSPC Logic  
- **Clocking:** Single-phase clock  
- **Technology:** CMOS  

---

## Theory
TSPC logic operates using a single clock phase for both precharge and evaluation:
- **Precharge Phase (CLK = 0):** Dynamic nodes are precharged to logic ‘1’
- **Evaluation Phase (CLK = 1):** Logic evaluation occurs based on input combinations

This approach enables:
- High-speed operation  
- Reduced transistor count  
- Compact layout and low power consumption  

---

## Circuit Description

### 1. TSPC Full Adder
Performs binary addition of inputs A, B, and Carry-in using dynamic precharge and evaluation phases.

### 2. TSPC D Flip-Flop
Acts as a dynamic memory element for storing carry and sum values with high speed and reduced area.

### 3. TSPC Shift Register
A 4-bit shift register constructed using TSPC D flip-flops for serial data movement.

### 4. TSPC Serial Adder
Uses:
- One TSPC Full Adder  
- One D Flip-Flop for carry storage  
- Shift registers for operands and sum  

Performs bit-by-bit addition across clock cycles.

### 5. TSPC Ripple Carry Adder
A parallel adder constructed by cascading multiple TSPC Full Adders.

---

## Results
- Correct SUM and CARRY outputs verified through simulation  
- Minimal propagation delay  
- Reduced power dissipation  
- Compact layout area  

---

## Contributors
- **Bakki Sylvester Mohan Raj** 

---

