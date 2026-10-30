# Digital IC Design using Verilog

A growing collection of Verilog digital design exercises and projects, using AMD/Xilinx Vivado for behavioral simulation.

## Status

Repository initialized. The first exercise will be added next. No simulation or hardware validation results are claimed yet.

## Exercise contents

Each exercise will include:
- A specification with inputs, outputs, and expected behavior.
- Verilog RTL sources in `rtl/`.
- A testbench in `tb/`.
- A README with Vivado run instructions and actual test results.
- Relevant waveform images and learning references when available.

Exercises will be added under `exercises/<exercise-name>/` as they are completed.

## Vivado workflow

1. Create a local RTL project.
2. Add RTL files as Design Sources.
3. Add the testbench as Simulation Sources.
4. Set the design and simulation top modules specified in the exercise README.
5. Run Behavioral Simulation for the documented duration.
6. Review checks and waveforms, then record the Vivado version and actual results.

Behavioral simulation does not imply successful synthesis, timing closure, or FPGA hardware validation. These results will be documented separately if performed.

## Learning references

Course references and any extensions to course examples will be documented with each exercise.
