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

![Screenshot 2024-12-15 175318](https://github.com/user-attachments/assets/0a016cc9-c954-4656-a4bc-3b8a48884f3f)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![image](https://github.com/user-attachments/assets/51585daf-0f35-40ab-ad72-32598680b325)
![Screenshot 2024-12-15 175929](https://github.com/user-attachments/assets/d8bcf04e-8abb-4050-a90f-6491aff39c11)




Developed by: YOGESH D RegisterNumber: 24006488

**RTL Schematic**

![image](https://github.com/user-attachments/assets/99845e41-4a11-4567-a59e-7c908d572293)
![Screenshot 2024-12-15 174622](https://github.com/user-attachments/assets/a9130c7d-6d54-4113-a3c3-7682271ae139)





**Output/TIMING Waveform**
![Screenshot 2024-12-15 155940](https://github.com/user-attachments/assets/535458e0-3685-4619-bd10-6e2b45d6624e)
![Screenshot 2024-12-15 174811](https://github.com/user-attachments/assets/6465e734-e9f9-4c40-a64b-37d7fc9e347a)



**Result:**

Thus the half adder subtractor in quartus using verilog programming are studied , verified
and executed successfully
