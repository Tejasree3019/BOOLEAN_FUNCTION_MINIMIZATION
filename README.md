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
![Screenshot 2025-04-21 142016](https://github.com/user-attachments/assets/4b62da7c-5f3a-4c86-992b-765cdb9856dd)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module exp2a(a,b,c,d,F1);
intput a,b,c,d;
output F1;
assign F1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule



module exp2b(w,x,y,z,F2)
intput w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: Tejasree.K
```
RegisterNumber: 212224240168
```


**RTL realization**

![Screenshot 2025-04-21 142522](https://github.com/user-attachments/assets/cfe909ca-8386-409b-b2f1-3d278806de48)
![Screenshot 2025-04-21 142739](https://github.com/user-attachments/assets/c831245f-1c1e-4930-88a6-65f31e5b55c3)





**Timing Diagram**

![Screenshot 2025-04-21 143016](https://github.com/user-attachments/assets/b16328bb-ba45-40b1-bc4a-e4cfa012fadc)
![Screenshot 2025-04-21 143106](https://github.com/user-attachments/assets/e93ba541-5d9a-4ad9-9336-993243fb1b09)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

