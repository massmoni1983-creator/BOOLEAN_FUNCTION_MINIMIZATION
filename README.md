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
Developed by:muruga S
RegisterNumber:25010785
```


**RTL realization**
<img width="613" height="564" alt="Screenshot 2025-11-27 104136" src="https://github.com/user-attachments/assets/77f6858d-5584-4037-9a13-4497b25f5ff0" />

**Output:**

**RTL**
<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/c9ede149-93c2-417d-b49c-8f2d91d5bda0" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

