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
Logic diagram for full addder:
<img width="869" height="434" alt="Screenshot 2025-10-14 222403" src="https://github.com/user-attachments/assets/e924111d-23b7-49ea-a633-f0c107a4575b" />

state diagram for full adder:
<img width="1035" height="142" alt="Screenshot 2025-10-14 222743" src="https://github.com/user-attachments/assets/3d2bd0c1-f7f4-4cc9-8b4f-929ef7eb9517" />

logic diagram for full subtractor:
<img width="925" height="403" alt="Screenshot 2025-10-14 223158" src="https://github.com/user-attachments/assets/a63e22bd-b273-4962-9430-b79d17e89ee4" />

state diagram for full subtractor:
<img width="1036" height="127" alt="Screenshot 2025-10-14 223324" src="https://github.com/user-attachments/assets/84a290bd-377b-4dcf-b81c-20e151973b68" />


Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



