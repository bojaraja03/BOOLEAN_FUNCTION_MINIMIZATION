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
Developed by: BOJA RAJA G 
RegisterNumber:212225230036
```
module boolean(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 
```







**Output:**

**RTL**
<img width="1920" height="1020" alt="{8617F8F7-4A94-4D16-8996-F7EB261013F0}" src="https://github.com/user-attachments/assets/54621c4f-3f43-4b15-b5c4-e4ebd0889dfd" />


**Timing Diagram**
<img width="1921" height="1201" alt="image" src="https://github.com/user-attachments/assets/f9e529f2-a5bd-4698-a884-b7c907087cbb" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

