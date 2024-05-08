# STUDY OF BASIC GATES
## AIM:

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

## Equipments Required:

Software – Quartus prime 

## Theory

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

## AND gate

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

## OR gate

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

## NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

## NAND gate

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

## NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

## Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

## Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

## Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## PROGRAM

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:Mano Karthick.S
 
 RegisterNumber: 212222230077
 
## Logic symbol & Truthtable
### AND GATE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/cb7bb724-8b45-40af-8405-9c563ccfbb45)

### LOGIC SYMBOL AND TRUTH TABLE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/dd2dcf2d-b50a-4d9a-bcff-4559c857f185)

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/0b7606a2-7958-46c4-8dce-5e33d3a67f13)



## RTL realization Output:

![DGexp-1](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/646e1b73-e358-414d-bd3d-af683b4fccc5)

### OR GATE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/04af8cbf-f7c1-47cb-91f4-7b22bb69d306)

### LOGIC SYMBOL AND TRUTH TABLE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/b91cf740-feeb-4fad-a526-fdcf0790e01f)

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/6a13234f-72c9-412f-8fe4-dec27258d9a8)

## RTL realization Output:
![orgate](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/f356d5ca-08f3-4a20-beb2-700636a675f3)

### NAND GATE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/e0e774a6-675a-4ae5-8c88-4dd038d2d2d9)

### LOGIC SYMBOL AND TRUTH TABLE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/96009bf3-ca80-4f9e-a78c-fdd8a24cfc1f)

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/cf17b691-fdc6-4c12-8e54-8f86144595a9)

## RTL realization Output:
![nandgate waveform](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/17c61d09-8683-4412-a849-4a42ea63ac13)

### NOT GATE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/79d2b7e8-2589-4ebd-a565-7e8ab093bd8a)

### LOGIC SYMBOL AND TRUTH TABLE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/117a8e9d-8560-45b5-8dfc-a60ab13e5c91)

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/85372843-11e7-4c72-9c72-f7d717880eb3)

## RTL realization Output:
![notgate wavefporm](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/e38ab851-d647-41b7-b7de-2997e27fcd35)

### NOR GATE

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/4715b206-b384-4531-98db-0d9d21c0a1e0)

### LOGIC SYMBOL AND TRUTH TABLE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/c2a6b7a1-77f5-4cdd-a1ae-ad71c2fd0805)

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/8f6f5031-5c48-47ba-8441-553f40c1fab0)


## RTL realization Output:
![nor gate](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/4d5c8295-caad-4a6f-ba36-591cc57c33e4)

### EX-OR GATE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/62794195-059b-4a3b-9770-016116dc8dcd)

### LOGIC SYMBOL AND TRUTH TABLE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/6fb964da-a49c-4c58-b44d-53ec5fffe766)

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/880d416c-56e1-49c5-be41-b97c5a0c7bfa)

## RTL realization Output:

![xorgate waveform](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/2dece152-fdd1-4827-8e8f-ba05a7f87a11)

### EX-NOR GATE
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/0f097a73-285a-4477-aca5-79ad9462a4ce)

### LOGIC SYMBOL AND TRUTH TABLE
![xnor gate diagram](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/7351e5b4-6475-402a-b7f0-ba8077ff6151)

![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/87155193-516b-49b8-a202-167578e943e8)

## RTL realization Output:
![image](https://github.com/ARCHANAT1305/study-of-basic-gates/assets/145975189/1e994fb0-6b75-4bdb-8636-2d7edc098582)

## Result:
Thus, the study of basic gates was executed successfullly.


