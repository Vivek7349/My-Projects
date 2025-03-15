# SR Flip-Flop

## Overview
This repository contains a Verilog implementation of an **SR (Set-Reset) Flip-Flop** with clock and reset functionality. The SR Flip-Flop is a fundamental sequential circuit used in digital systems for storing binary data and is controlled by **Set (S)** and **Reset (R)** inputs.

## Features
- **Clock-Synchronized**: The state changes occur on the **positive edge** of the clock.
- **Asynchronous Reset**: The reset input forces the output to `0` regardless of other inputs.
- **Valid and Invalid States**:
  - `S = 0, R = 0` → No change in output.
  - `S = 0, R = 1` → Output **reset** to `0`.
  - `S = 1, R = 0` → Output **set** to `1`.
  - `S = 1, R = 1` → **Invalid state** (`X` output).

