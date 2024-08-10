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
