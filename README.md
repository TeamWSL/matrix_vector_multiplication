# Systolic Array Based Matrix-Vector Multiplication

This repository contains the SystemVerilog code and simulation results for a systolic array-based matrix-vector multiplication for signed 8 bit integers. 
The architecture is designed to perform the multiplication of a 16x16 matrix with a 16x1 vector in 16 clock cycles.

currently this architecture is implemented in Behavioural level for general purpose, which utilize LUT in FPGA.

You can replace the processing element with DSP blocks of FPGA depending on the requirement

## Architecture

![C5apture](https://github.com/user-attachments/assets/cced5cc8-c467-4831-9ec6-e0163f834575)


## Simulation Results

The simulation results demonstrate the performance and correctness of the systolic array-based multiplication.
which is done using - ModelSim for simulation.
  
![Simulation Result 1](https://github.com/user-attachments/assets/c61967de-47b1-4787-ab0b-be0206c7c260)
![Simulation Result 2](https://github.com/user-attachments/assets/20f043a3-7f87-4275-b3f8-0d5d1d8426de)



