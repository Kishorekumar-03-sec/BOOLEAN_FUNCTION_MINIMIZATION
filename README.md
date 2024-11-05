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
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: RegisterNumber:*/24900228


**RTL realization**
THE LOGIC GATES ARE STUDIED AND THE RTL OUTPUT IS VERIFIED

**Output:**

**RTL**
![Screenshot (2)](https://github.com/user-attachments/assets/7a1a15ce-76e4-4b64-90dd-25cc081b4af1)



**Timing Diagram**

![Screenshot (4)](https://github.com/user-attachments/assets/81cf210a-11ab-4196-ad36-91377c1e6fd0)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

