# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module exp2 (
	input wire A,
	input wire B,
	input wire C,
	input wire D,
	output wire F
);
assign F = (~A & B) | (C & D) | (A & ~D);
endmodule 

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:CALWIN SAM B RegisterNumber:*/ 25002056


**RTL realization**
<img width="1920" height="1080" alt="Screenshot 2025-10-08 134228" src="https://github.com/user-attachments/assets/a4ac7eec-4b6a-452b-bcc1-f8bd597357c0" />


**Output:**

**RTL**

**Timing Diagram**

**Result:**
<img width="1920" height="1079" alt="Screenshot 2025-10-08 135925" src="https://github.com/user-attachments/assets/e5fd9709-9a30-41e0-b132-5b590bb24ae7" />


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

