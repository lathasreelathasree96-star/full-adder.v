# 1-Bit Full Adder using Verilog

## Overview
This project implements a 1-bit Full Adder using Verilog HDL.

A Full Adder adds three binary inputs:
- A
- B
- Cin (Carry Input)

It produces two outputs:
- Sum
- Cout (Carry Output)

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|

## Verilog Equation

Sum = A ^ B ^ Cin

Carry = (A & B) | (B & Cin) | (A & Cin)

## Files

- `full_adder.v` → Verilog design
- `full_adder_tb.v` → Testbench
- `simulation.png` → Simulation waveform

## Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
