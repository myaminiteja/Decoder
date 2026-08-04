# 2-to-4 Decoder using Verilog

## Overview

A decoder is a combinational logic circuit that converts binary input data into one of several outputs. This project implements a 2-to-4 decoder using Verilog HDL.

## Features

- Verilog HDL implementation
- Testbench included
- Simple combinational logic
- Easy to simulate using ModelSim, Vivado, or Icarus Verilog

## Truth Table

| A | B | Y0 | Y1 | Y2 | Y3 |
|---|---|----|----|----|----|
|0|0|1|0|0|0|
|0|1|0|1|0|0|
|1|0|0|0|1|0|
|1|1|0|0|0|1|

## Files

- `decoder.v` – Decoder module
- `decoder_tb.v` – Testbench
- `README.md` – Documentation

## Simulation Output

```text
A B | Y0 Y1 Y2 Y3
0 0 | 1  0  0  0
0 1 | 0  1  0  0
1 0 | 0  0  1  0
1 1 | 0  0  0  1
```

## Applications

- Memory address decoding
- Data routing
- Digital communication systems
- Processor control units

## Author

Your Name