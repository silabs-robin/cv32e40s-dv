# cv32e40s-dv

CV32E40S Design-Verification environment


## Directories:

- **bsp**:   the "board support package" for test-programs compiled/assembled/linked for the CV32E40S.  This BSP is used by both the `core` testbench and the `uvmt` UVM verification environment.
- **env**:   the UVM environment class and its associated infrastrucutre.
- **sim**:   directory where you run the simulations.
- **fv**:    directory where you run formal verification.
- **tb**:    the Testbench module that instanitates the core.
- **tests**: this is where all the testcases are.

There are README files in each directory with additional information.
