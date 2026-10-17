# Single-Cycle-RISC-V-Processor-in-Verilog

This project implements a single-cycle RISC-V processor using Verilog-2001 in Xilinx Vivado 2020.

The processor follows a five-stage datapath consisting of Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), Memory Access (MEM), and Write Back (WB). All five stages execute within a single clock cycle.

Supported Instructions

Arithmetic: ADD, SUB, ADDI

Logical: AND, OR

Comparison: SLT

Memory: LW, SW

Control Flow: BEQ, JAL

Files

riscv.v — Processor design

testbench.v — Testbench for behavioral simulation

memfile.dat — Instruction memory initialization file

The project uses Vivado behavioral simulation to test processor operation and verify the expected memory write.
