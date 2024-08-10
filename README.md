# RoCoCo Generator

## Overview

The RoCoCo Generator is a Perl script (`PCSTmult.pl`) designed to perform different arithmetic operations and generate compression trees based on user-provided arguments.

## Supported Operations

1. **KbxLb Multiplier**:
   - Multiplies a K-bit number by an L-bit number.

2. **KxLb Adder**:
   - Adds K (constant) L-bit numbers.

3. **N:2 Compressor Generator**:
   - Generates a reduction tree based on the input sequence.
   - Example Input: `"1 2 3 4 5 2 1"`
   - The sequence represents the number of rows in each column that should be compressed.

## Usage

To run the script, use the following command:

```bash
perl PCSTmult.pl <args>
```
### How to Cite

Please use the following paper as a general citation for the RoCoCo Generator:

Ugurdag HF, Keskin O, Tunc C, Temizkan F, Fici G, Dedeoglu S (2011) RoCoCo: row and column compression for highperformance multiplication on FPGAs. In: Proceedings of design & test symposium (EWDTS), Sevastopol, pp 98–101
