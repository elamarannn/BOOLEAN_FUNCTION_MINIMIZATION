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

Developed by:Elamaran S E 
RegisterNumber:212222230036*/
```
 module EX2(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 endmodule

module EX2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule
```

**RTL realization**
**Output:**
**RTL**

![image](https://github.com/user-attachments/assets/5966a37d-30a0-4fd1-97a8-41676df6c359)

![image](https://github.com/user-attachments/assets/094b4609-140a-4a39-9919-f66c15f6ee15)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/d81b9ec5-4366-4c38-a8d4-79bac069a475)

![image](https://github.com/user-attachments/assets/9103db77-e189-4632-a5d0-9e154fa797e5)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

