# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**


![full adder tt](https://github.com/user-attachments/assets/7a6f73ce-e974-4c2a-a59a-57d86f5d42e1)

![full subtractor](https://github.com/user-attachments/assets/296eb827-8d8a-46f3-88ff-5d52dd83c35d)


**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by: L.Baradhan  
RegisterNumber:24005473

![full adder](https://github.com/user-attachments/assets/d006731b-af84-4f8c-9dd4-e8287df70cc2)


![full subtractor program](https://github.com/user-attachments/assets/4031b573-438d-4f14-8c04-7d51e87a881c)


**RTL Schematic**


![full adder gate](https://github.com/user-attachments/assets/0128c10a-b27c-40bd-b6b8-3fe68c0fc3cf)



![full subtractor gate](https://github.com/user-attachments/assets/863aaeb3-c74b-4c88-864e-9f14ba4cc735)


**Output Timing Waveform**

![full adder wf](https://github.com/user-attachments/assets/f47890af-8708-4263-8f48-edc4ab33e607)


![full subtractor wf](https://github.com/user-attachments/assets/dbecdf8f-f26c-48cc-8d52-0ba9cfa06024)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



