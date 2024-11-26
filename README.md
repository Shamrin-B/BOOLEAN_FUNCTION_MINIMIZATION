# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![Screenshot (25)](https://github.com/user-attachments/assets/5152b9ee-782a-45de-af65-bfe047a672c5)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
Developed by:shamrin.B
RegisterNumber:24900144
```
```
module ex_2(a,b,c,d,w,x,y,z,f1,f2)
intput a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
**RTL realization output**

![Screenshot (26)](https://github.com/user-attachments/assets/78d6640c-7dc8-4587-9831-6f0153b8344f)

**Timing Diagram**
![Screenshot (5)](https://github.com/user-attachments/assets/fcfc72d5-1f9e-4ab0-a100-33b89b0a4755)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

