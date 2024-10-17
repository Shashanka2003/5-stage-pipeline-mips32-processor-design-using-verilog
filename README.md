# 5-stage-pipelined-mips32-processor-design-using-verilog

This repository contains the Verilog implementation of a 5-stage pipeline for a subset of the MIPS32 architecture. The pipeline stages include:
- Instruction Fetch (IF)
- Instruction Decode (ID)
- Execution (EX)
- Memory Access (MEM)
- Write Back (WB)

## Features
- **Instruction Subset**: The implementation supports basic arithmetic and logic instructions (`ADD`, `SUB`, `AND`, `OR`), immediate operations (`ADDI`, `SUBI`), load/store instructions (`LW`, `SW`), and basic branching (`BEQZ`, `BNEQZ`).
- **Hazard Handling**: Dummy instructions are inserted to avoid data hazards in pipeline stages.
- **Behavioral Modeling**: The design uses behavioral Verilog, focusing on simulating the processor's behavior.

## Files Included
- **Verilog Source Code**: Contains the pipeline implementation and test benches for verifying the functionality.
- **Test Bench Examples**: Includes test programs to demonstrate operations such as addition, memory load/store, and factorial computation.

## How to Run
1. Clone the repository and navigate to the project directory.
2. Compile the Verilog files using your preferred simulator.
3. Run the test benches to simulate the pipeline behavior and verify the outputs.

## Future Work
- **Hazard Avoidance**: Implement structural design techniques for data forwarding and pipeline hazard resolution.
- **Extended Instruction Set**: Expand the instruction set to cover additional operations.
- **Synthesis**: Integrate synthesis tools for FPGA/ASIC implementation.
