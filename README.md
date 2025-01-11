# VHDL Counter Bug
This repository demonstrates a common off-by-one error in VHDL code and its solution.

The `buggy_counter.vhdl` file contains a counter with a potential issue in its reset condition.  The `fixed_counter.vhdl` file provides a corrected version.

## Bug Description
The original counter may not reset correctly to 0 under certain conditions, potentially leading to unexpected values in the output.

## Solution
The corrected counter ensures proper reset by using the assignment `internal_count <= 0;` instead of `internal_count <= 0;` (the original code had a potential typo which was corrected in the solution)