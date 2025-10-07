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

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**

**Output Timing Waveform**

**Result:**
Logic Gate for full adder
<img width="1920" height="1080" alt="Full adder Logic Diagram" src="https://github.com/user-attachments/assets/08a2693f-0c88-4dee-9d85-89692222bb95" />
Clock Pulse for Full Adder
<img width="1920" height="1080" alt="Full adder Clock Pulse" src="https://github.com/user-attachments/assets/a8479fe1-ec3d-4a1a-9dca-2357c89b4cb5" />
Logic gate for Full Subractor
<img width="1920" height="1080" alt="Full Subractor Logic gate" src="https://github.com/user-attachments/assets/494311f6-1b86-4d77-85fc-159288cb92cc" />
Clock Pulse for Full subractor
<img width="1920" height="1080" alt="Full subractor Clock Pulse" src="https://github.com/user-attachments/assets/b5038b84-7ec1-484f-9ffe-7bcfd5fab767" />

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



