# overview
This project 8 bit Ripple Carry Adder using Verilog and SystemVerilog with UVM for verification. 
The UVM testbench was developed and executed in EDA Playground. 
The physical design flow was completed using open-source EDA tools, including OpenROAD, Klayout, and Yosys.

## Implementation Details
1️⃣ 8 bit Ripple Carry Adder
Implemented a Moore Finite State Machine (FSM) for detection.
Simulated and verified using UVM (Universal Verification Methodology).<br>
2️⃣ Universal Verification Methodology (UVM)
Developed a UVM testbench in EDA Playground.
Testbench includes generator, driver, monitor, scoreboard, and agent.
Simulation performed in EDA Playground to validate the sequence detector.<br>
3️⃣ Physical Design
Logic synthesis performed using Yosys.
Floorplanning, placement, clock tree synthesis, and routing done using OpenROAD.
Final layout visualization in KLayout.
Design constraints specified in SDC (Synopsys Design Constraints) format.
