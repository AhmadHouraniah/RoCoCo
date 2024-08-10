# RoCoCo Generator

## Overview

The RoCoCo Generator is a Perl script (`PCSTmult.pl`) designed to perform various arithmetic operations and generate reduction trees based on user-provided arguments.

## Features

1. **KbxLb Multiplier**:
   - Multiplies a K-bit number by an L-bit number.

2. **KxLb Adder**:
   - Adds K (constant) L-bit numbers.

3. **Reduction Tree Generator**:
   - Generates a reduction tree based on the input sequence.
   - Example Input: `"1 2 3 4 5 2 1"`
   - The sequence represents the number of rows in each column that should be reduced.

## Usage

To run the script, use the following command:

```bash
perl PCSTmult.pl <args>
