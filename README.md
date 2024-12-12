# VHDL Counter Overflow Bug

This repository demonstrates a common error in VHDL code: an integer counter that overflows without proper handling. The `counter` entity increments a value, but doesn't check for exceeding the defined range. This can lead to unexpected results or even simulation failures.

The `bug.vhdl` file contains the buggy code. The `bugSolution.vhdl` file shows the corrected version with overflow prevention.