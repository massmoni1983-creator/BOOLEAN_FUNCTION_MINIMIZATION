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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
```
module logic_function(
input a,b,c,d,
input w,x,y,z,
output f1,f2);
assign f1=(~b&~d)|(a&b&~c)|(~a&b&d);
assign f2=(~y&z)|(x&y)|(w&y);
endmodule 

```
```
Developed by: Muruga S
RegisterNumber: 25010785
```
<img width="664" height="554" alt="Screenshot 2025-12-13 092554" src="https://github.com/user-attachments/assets/ef3ccf32-159d-4fa0-ba5a-9d1146e76338" />
**RTL realization**

**Output:**

**RTL**
<img width="1039" height="551" alt="image" src="https://github.com/user-attachments/assets/88aef6ca-8a1d-42fd-a7c5-90a40a647955" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

