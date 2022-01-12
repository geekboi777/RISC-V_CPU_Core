# RISC-V_CPU_Core
This repository contains the  working developer code for a RISC-V_CPU_Core made using TL-Verilog , Makerchip IDE, Sandpiper and Verilator. This is the first project that i have made while exploring the open-source ISA RISC-V. 
The following core follows the traditional architecture design flow with the starting point at the Program Counter. The instruction is then "fetched" from the IMem or the Instruction Memory. After fetching the instruction the RISC-V ISA is decoded into types, fields and immediate. The RISC-V ISA has six different instruction fields namely R,I,S,B,U,J types respectively. The instructions after being decoded are transferred to the RF (Register File) where the read and write operation takes place, source value calculated and result obtained.

# About RISC-V
RISC-V is an open standard instruction set architecture (ISA) that began in 2010 and is based on established reduced instruction set computer (RISC) principles. Unlike most other ISA designs, RISC-V is provided under open source licenses that do not require fees to use. There are many other ISA such as MIPS32, x86, etc.

