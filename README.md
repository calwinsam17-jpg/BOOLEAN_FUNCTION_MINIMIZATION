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

Developed by:CALWIN SAM B RegisterNumber:*/25002056


**RTL realization**
<img width="1920" height="1080" alt="Screenshot 2025-10-08 134228" src="https://github.com/user-attachments/assets/54f98019-8313-4e17-8614-d86ff9e96275" />


**Output:**

**RTL**

**Timing Diagram**

**Result:**
<img width="1920" height="1079" alt="Screenshot 2025-10-08 135925" src="https://github.com/user-attachments/assets/8dda0318-fede-4457-97b5-aea55d24335e" />


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

