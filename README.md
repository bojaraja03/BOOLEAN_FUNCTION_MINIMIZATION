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

/* module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


Developed by: BOJA RAJA G RegisterNumber:*/25015352


**RTL realization**

**Output:**

**RTL**
<img width="1920" height="1080" alt="Screenshot 2025-10-07 142828" src="https://github.com/user-attachments/assets/70f88e63-fcda-4ba5-9ecf-c2e6fb9ab0ba" />


**Timing Diagram**
<img width="1920" height="1020" alt="Screenshot 2025-10-07 213212" src="https://github.com/user-attachments/assets/9e165397-94ff-43e8-a29c-b7cbb04b616c" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

