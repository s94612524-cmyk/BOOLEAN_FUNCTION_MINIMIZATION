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
EXPERIMENT 2:
MINIMIZATION OF BOOLEAN FUNCTION
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**

<img width="506" height="358" alt="Screenshot 2025-10-07 193648" src="https://github.com/user-attachments/assets/71536d48-26ee-4960-abaa-90ad6e8c9f49" />
<img width="440" height="237" alt="Screenshot 2025-10-07 195301" src="https://github.com/user-attachments/assets/84dfd5d4-64a9-448d-ac9b-83574329e7b7" />

**Output:**

**RTL**

**Timing Diagram**
![EX2](https://github.com/user-attachments/assets/79a8a245-0c24-4282-acc7-8a1f296c6061)
![EX2 1](https://github.com/user-attachments/assets/4bae4b91-4c31-4b03-9488-0cf4418c77bb)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

