TSPC-Based Serial Adder and Ripple Carry Adder

Using Microwind

Overview

This project focuses on the design and simulation of TSPC-based arithmetic circuits using Microwind 3.0.
The aim is to build high-speed and area-efficient adders using True Single Phase Clock (TSPC) dynamic logic.
What I Designed

TSPC Full Adder

TSPC D Flip-Flop

4-bit Shift Register

TSPC Serial Adder

TSPC Ripple Carry Adder

Tools & Technology

Tool: Microwind 3.0

Logic Style: TSPC Dynamic Logic

Clock: Single Phase Clock

Technology: CMOS

Basic Idea of TSPC

TSPC uses only one clock for both precharge and evaluation.

When CLK = 0 → Nodes are precharged

When CLK = 1 → Logic evaluation happens

This gives:

High speed

Fewer transistors

Compact layout

Lower power

Circuit Description
TSPC Full Adder

Adds A, B, and Carry-in using dynamic logic.

TSPC D Flip-Flop

Stores data using TSPC logic with high speed and less area.

Shift Register

4-bit register made using TSPC D Flip-Flops for serial data shifting.

Serial Adder

Uses:

One TSPC Full Adder

One D Flip-Flop for carry

Shift registers for inputs and output

Performs bit-by-bit addition every clock cycle.

Ripple Carry Adder

Parallel adder built by cascading multiple TSPC Full Adders.

Results

Correct SUM and CARRY verified in simulation

Fast operation

Low power

Compact layout

Contributor

Vijay Teja Asagunda
