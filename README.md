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

**Procedure**

Write the detailed procedure here

Full Adder:

1.Open Quartus II and create a new project.

2.Use schematic design entry to draw the full adder circuit.

3.The circuit consists of XOR, AND, and OR gates.

4.Compile the design, verify its functionality through simulation.

5.Implement the design on the target device and program it.

Full Subtractor:

1.Follow the same steps as for the full adder.

2.Draw the full subtractor circuit using schematic design.

3.The circuit includes XOR, AND, OR gates to perform subtraction.

4.Compile, simulate, implement, and program the design similarly to the full adder.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
FULL_ADDER_
<img width="779" height="200" alt="image" src="https://github.com/user-attachments/assets/4093af1d-45b7-4cae-9a04-5f9bdbad67eb" />
FULL_SUBTRACTOR_
<img width="733" height="220" alt="image" src="https://github.com/user-attachments/assets/9a467891-a59c-42ed-92eb-5b2fc787173d" />



Developed by: RegisterNumber:25015046
*/

**RTL Schematic**
FULLADDER_
<img width="1090" height="460" alt="{57690930-1BD0-40EA-809B-D0F11F186FEF}" src="https://github.com/user-attachments/assets/df4acd36-9375-417d-bf36-e12e15da5fd6" />
FULLSUBTRACTOR_
<img width="1205" height="339" alt="image" src="https://github.com/user-attachments/assets/389e0c65-d692-4989-868e-5f0107d4e797" />


**Output Timing Waveform**

FULLADDER_
<img width="1199" height="141" alt="image" src="https://github.com/user-attachments/assets/6bcef759-d534-424b-9e3e-d7f278c9beae" />
FULLSUBTRACTOR_
<img width="1204" height="160" alt="image" src="https://github.com/user-attachments/assets/5bec5ad1-2542-42b7-9bfc-83ad2e6e88c3" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



