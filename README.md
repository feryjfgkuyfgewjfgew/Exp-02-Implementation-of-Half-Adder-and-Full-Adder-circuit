# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
```/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: NARESH.R
RegisterNumber: 230005559 
*/```
Logic symbol & Truthtable
RTL realization

HALF ADDER

![Screenshot 2023-12-14 085759](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/2aef20cc-a05c-471d-b460-17438598c692)

FULL ADDER

![Screenshot 2023-12-14 085809](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/d4b96ccd-1b96-4cb6-a737-a3af40c37981)

#### RTL VIEWER:
HALF ADDER

![Screenshot 2023-12-14 085824](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/7d1d947e-6ae8-4c0e-9ba9-36c2445e4bcd)

FULL ADDER

![Screenshot 2023-12-14 085845](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/41aac134-9eab-4220-acc0-fbce6c9e477e)

### TIMING DIAGRAM
HALF ADDER

![Screenshot 2023-12-14 085932](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/7f0de886-78ee-4e2a-9602-50e9ddb81340)

FULL ADDER

![Screenshot 2023-12-14 085944](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/6028583a-2208-4d25-b8ff-65f539906576)


### TRUTH TABLE 
HALF ADDER

![Screenshot 2023-12-14 085907](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/680a77d0-3b5b-43c6-a4c8-4ea91ab01b9d)

FULL ADDER

![Screenshot 2023-12-14 085923](https://github.com/feryjfgkuyfgewjfgew/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319377/77ff26c6-645a-40b3-85ad-a25cfc078270)


### Result:
