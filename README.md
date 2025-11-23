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

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

##FULL ADDER
<img width="1019" height="275" alt="full add" src="https://github.com/user-attachments/assets/61bb264f-50c6-420c-8ad0-d27eb64a78e1" />
##FULL SUBTRACTOR

<img width="811" height="264" alt="full sub" src="https://github.com/user-attachments/assets/a58ce795-6721-49aa-8b0b-47e83d2d4e6c" />

Developed by:LAL RHIDHISHAN.R ,RegisterNumber:25015767
*/

**RTL Schematic**

##FULL ADDER
<img width="1589" height="892" alt="full add (2)" src="https://github.com/user-attachments/assets/884e4433-d7f1-4541-b1e0-2453051e2954" />

##FULL SUBTRACTOR
<img width="1587" height="893" alt="full sub (2)" src="https://github.com/user-attachments/assets/f4d474f0-6b10-4178-9a76-546045c8f92f" />

**Output Timing Waveform**

##FULL ADDER
<img width="1232" height="908" alt="full add (3)" src="https://github.com/user-attachments/assets/ccb44973-bd94-4faf-9635-9ee3a62a60b4" />

##FULL SUBTRACTOR
<img width="1237" height="914" alt="full sub (3)" src="https://github.com/user-attachments/assets/c6d481db-5eab-45bb-9840-474369dfd0e6" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



