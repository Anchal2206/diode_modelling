# Diode Modelling with Reverse Recovery and Analysis of Breakdown Voltage and Transit Time

## Overview:
The p-i-n diode is widely used in high-frequency and power electronic circuits due to its fast switching characteristics. Structurally, it consists of a lightly doped intrinsic region sandwiched between highly doped p⁺ and n⁺ regions.

In an ideal diode, the current instantly switches direction when the applied voltage polarity changes. However, in a practical p-i-n diode, charge carriers accumulate in the intrinsic region during forward bias. When the diode is suddenly reverse-biased, this stored charge must first recombine or be swept out before the diode can fully block the reverse voltage. This phenomenon gives rise to the reverse recovery current, a key aspect in switching behavior.

This project presents a compact Verilog-A model of a p-i-n diode, capturing the reverse recovery behavior accurately. The model incorporates the dependence of reverse recovery time and breakdown voltage on key physical parameters such as intrinsic region width and doping concentration. It is suitable for time-domain circuit simulation and can aid in the design and analysis of fast-switching power devices.

## File
- **p_diode.va** file contains Verilog-A code incorporating reverse recovery in an ideal diode.
## Simulation
- **simulation.txt** file gives step-by-step instructions for setting up and running DC and transient simulations. It details how to build the testbench, apply different voltage sweeps, and generate plots.
- **inference.txt** is a guide to interpreting the simulation plots. It explains how to extract key physical insights from the graphs, such as the transition from forward conduction to reverse recovery, and how various parameters influence the behavior.
## Results
- results file has the graphs as obtained with the simulations.

