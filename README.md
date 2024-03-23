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

## Truthtable:

**HALF ADDER:**

![truth_table_halfadder](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/a61ed470-ca6a-4a42-99f0-7fade5978d74)

**HALF SUBTRACTOR**

![truthtable_half_subtractor](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/d6907e51-6859-4b69-a08d-03890c531329)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:ROHITH PREM S RegisterNumber: 212223040172
```
**CODE:**

**HALF ADDER:**

![Screenshot (33)](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/fe119800-ca3f-44a2-87cc-98b50daedcde)
**HALF SUBTRACTOR:**

![Screenshot (36)](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/82d5fcfa-3764-48f5-b21a-535241c852a0)

**RTL Schematic**

**HALF ADDER:**

![Screenshot (31)](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/9022f605-dc29-4cd8-a260-d97df3e2f072)
**HALF SUBTRACTOR:**

![Screenshot (34)](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/3a2d6fa3-497b-4a51-88c6-4b6cfedf6681)

**Output/TIMING Waveform**

**HALF ADDER:**
![Screenshot (32)](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/8decea87-74cb-4c6e-89d5-cc4946ba3505)
**HALF SUBTRACTOR**
![Screenshot (35)](https://github.com/rohithprem18/HALF_ADDER_SUBTRACTOR/assets/146315115/c10e3183-25e3-47c8-ac46-3a0c2e11848d)


**Result:**

Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
