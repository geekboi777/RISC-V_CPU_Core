# RISC-V_Single_CPU_Core
This repository contains the  working developer code for a RISC-V_CPU_Core made using TL-Verilog , Makerchip IDE, Sandpiper tool and Verilator. This is the first project that i have made while exploring the open-source ISA RISC-V. 
The following core follows the traditional architecture design flow with the starting point at the Program Counter. The instruction is then "fetched" from the IMem or the Instruction Memory. After fetching the instructionn the RISC-V ISA is decoded into types, fields and immediate. The RISC-V ISA has six different instruction fields namely R,I,S,B,U,J types respectively. The instructions after being decoded are transferred to the RF (Register File) where the read and write operation takes place, source value calculated and result obtained.

The following figure shows the general operation and architecture of the RISC-V CPU core.

![risc](https://user-images.githubusercontent.com/85869106/149224598-85653c5b-d0be-44b8-8c85-0c21b856141f.jpg)

# About RISC-V
RISC-V is an open standard instruction set architecture (ISA) that began in 2010 and is based on established reduced instruction set computer (RISC) principles. Unlike most other ISA designs, RISC-V is provided under open source licenses that do not require fees to use. There are many other ISA such as MIPS32, x86, etc.
It is a simple, stable, small standard base ISA with extensible ISA support, that has been redefining the flexibility, scalability, extensibility, and modularity of chip designs. Since it is freely available, it provides it a higher edge compared to other ISA's.

# The CPU Core

The following figure shows the RISC-V CPU Core that I developed.

![Image 13-01-22 at 3 11 AM](https://user-images.githubusercontent.com/85869106/149225748-e6fad9c9-7417-4093-9179-8451522d702c.jpg)

