# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: Harish P RegisterNumber: 25015017*/
<img width="477" height="270" alt="image" src="https://github.com/user-attachments/assets/6ab8c433-5911-47e1-8ef6-fee52fe19127" />
<img width="586" height="252" alt="image" src="https://github.com/user-attachments/assets/153bb357-de99-4f4c-98d8-c56465b0d047" />
**RTL Schematic**

<img width="1024" height="579" alt="image" src="https://github.com/user-attachments/assets/5618ed26-d5a3-4adb-bc44-ae902b5e29be" />
<img width="1021" height="485" alt="image" src="https://github.com/user-attachments/assets/63852502-ed03-412a-8002-551d58581a40" />

**Output/TIMING Waveform**
<img width="1267" height="307" alt="image" src="https://github.com/user-attachments/assets/de9c99d4-2f61-4450-bbd8-d64699d9072e" />
<img width="1029" height="270" alt="image" src="https://github.com/user-attachments/assets/b50d0411-e40a-47a2-8d35-419cf730bc0a" />

**Result:**
Thus a half adder and half subtractor circuit and its truth tables are studied and verified successfully in Quartus using Verilog programming 
