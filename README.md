8-Bit CPU Design & Implementation

A fully functional 8-bit CPU architecture designed and simulated from the ground up using Logisim. 
This project demonstrates fundamental computer architecture concepts, including datapath management, instruction decoding, and arithmetic-logic synchronization.


Architectural Overview
<img width="315" height="384" alt="image" src="https://github.com/user-attachments/assets/d15aef08-8568-493c-8ec6-e6c223ecd260" />


Key Components
The processor is built with a modular approach, featuring the following custom-designed units:
8-Bit ALU: Supports addition (fullAdder8), multiplication (multipler), and comparison (equalcomparator, lessthancomparator).
Control Unit: Decodes operational codes and manages the flow of data across the system.
Register File: Fast-access internal storage for instruction execution.
Memory Units: Implementation of dedicated Instruction Memory and Data Memory (Harvard Architecture).
Logical Operations: Includes twosComplement, leftshifter, and rightshifter modules for complex data manipulation.

Technical Specifications
Architecture: 8-bit Custom Datapath.
Arithmetic: Two's Complement support for signed operations.
Simulation Tool: Logisim Evolution / Classic.

How to Run
1) Download and install Logisim.ü
2) Clone this repository: git clone https://github.com/dunklesteos/8bit_Cpu.git
3) Open the .circ file in Logisim to view the circuits and run simulations.
