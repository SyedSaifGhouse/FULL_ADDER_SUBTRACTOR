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

1.FULL ADDER

![Screenshot 2024-12-09 215938](https://github.com/user-attachments/assets/3e7cc34f-ff41-45c9-a803-b77fc2e21628)

2.FULL SUBTRACTOR

![Screenshot 2024-12-09 215953](https://github.com/user-attachments/assets/76b95b01-2cfa-446e-a937-21222a9b02eb)


**Procedure**

**Full Adder:**

1.Open Quartus II and create a new project.

2.Use schematic design entry to draw the full adder circuit.

3.The circuit consists of XOR, AND, and OR gates.

4.Compile the design, verify its functionality through simulation.

5.Implement the design on the target device and program it.

**Full Subtractor:**

1.Follow the same steps as for the full adder.

2.Draw the full subtractor circuit using schematic design.

3.The circuit includes XOR, AND, OR gates to perform subtraction.

4.Compile, simulate, implement, and program the design similarly to the full adder.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by: SYED SAIF SYED GHOUSE
RegisterNumber: 24009014
*/

1.FULL ADDER

![Screenshot 2024-12-09 220654](https://github.com/user-attachments/assets/5db6f654-aa20-4860-8063-8a21cea4f61e)

2.HALF ADDER

![Screenshot 2024-12-09 220708](https://github.com/user-attachments/assets/bdca5265-2a6d-46dc-a85f-45d0fbf1e801)


**RTL Schematic**

1.FULL ADDER

![Screenshot 2024-12-09 220101](https://github.com/user-attachments/assets/0f9e8b01-908d-4690-8830-74234cb2e16d)

2.HALF ADDER

![Screenshot 2024-12-09 220120](https://github.com/user-attachments/assets/e8515533-dced-450e-b661-242fc08bba02)


**Output Timing Waveform**

1.FULL ADDER

![Screenshot 2024-12-09 220131](https://github.com/user-attachments/assets/46e43598-ce96-4df0-a005-b148f8a32aec)


2.HALF ADDER

![Screenshot 2024-12-09 220142](https://github.com/user-attachments/assets/2e519a24-6a2f-4b8f-a679-a59145ddf0f2)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



