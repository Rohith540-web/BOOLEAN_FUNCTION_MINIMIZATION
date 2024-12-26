# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= b'd'+a'bd+abc'

F2= y'z+wy+xy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**


i)

![Screenshot 2024-12-01 180608](https://github.com/user-attachments/assets/a620d906-0524-42f2-ae0e-a6d864265b8f)
ii)

![Screenshot 2024-12-01 182415](https://github.com/user-attachments/assets/35d2d1ce-6325-4180-9d6c-85f109603ec1)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
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

```

Developed by:Rohith V RegisterNumber:24900447*/


**RTL realization**

**Output:**

**RTL**

**Timing Diagram**

i)
![Screenshot (50)](https://github.com/user-attachments/assets/424dbf8d-2247-4468-9c31-3eb35b4038d8)

ii)

![Screenshot (51)](https://github.com/user-attachments/assets/f40b71f3-55ad-4f39-b740-0421bbdac898)



**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

