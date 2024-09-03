# Design of Hamming Type Code using FPGA in Verilog

## Overview
This project demonstrates the design and implementation of Hamming Code encoder and decoder systems using FPGA. 

The code is written in Verilog and executed on an FPGA, with the primary use case being error detection and correction in wireless communication systems.

## Project Structure
- `hamming_encoder.v`: Verilog module for Hamming Code encoding.
- `hamming_decoder.v`: Verilog module for Hamming Code decoding.
- `hamming_top.v`: Verilog module for integrating the encoder and decoder.
- `hamming_top_tb.v`: Testbench for verifying the functionality of the encoder and decoder.
- `README.md`: Project documentation.
- `.gitignore`: File specifying untracked files to ignore.

  ## Features
- **FPGA Implementation**: The design is implemented on an FPGA using Xilinx tools.
- **Error Detection and Correction**: Implements Hamming Code to detect and correct single-bit errors in wireless communication.
- **Modular Design**: Separate modules for encoding and decoding, with a testbench for simulation.

## Requirements
- Xilinx ISE or Vivado
- FPGA Development Board (e.g., Xilinx Spartan, Artix)

## Simulation
To simulate the project:
1. Open the project in your preferred Verilog simulation tool (e.g., ModelSim, Vivado).
2. Compile the Verilog files.
3. Run the simulation using the provided testbench (`hamming_tb.v`).

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Hamming_Code_FPGA_Verilog.git
