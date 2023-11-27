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

1. Connect the supply (+5V) to the circuit
2. Switch ON the main switch
3. If the output is 1, then the led glows.

### Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by : MOHAMMED PARVEZ S

Register Number : 23010483

Code : 

Half Adder :

![Exp3 ha code](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/718ab11f-a92b-4147-b5a4-632d83c24a65)

Full Adder :

![Exp3 fa code](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/37a793e2-a3ec-4f34-8424-99def72d98db)

Truth Table :

Half Adder :

![Exp3 truthtable (ha)](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/9bb6de56-7b3c-47e4-a3e7-f10dd6e7f255)

Full Adder :

![Exp3 truthtable (fa)](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/f59ff78f-9a3d-4572-be21-94f4059b216f)

RTL realization

Half Adder :

![Exp3 ha RTL diagram](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/2964f1fd-fc3a-4e02-9c2d-0c3988bf471e)

Full Adder :

![Exp3 fa RTL diagram](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/d8fe47a7-9391-4ae8-b7d4-f89a32cc20c3)

### Output :

Half Adder :

![265629888-a204ccf6-66f1-43d4-ae24-b980509a1acc](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/662f293b-5f84-46aa-a1d8-51f76b5bd072)

Full Adder :

![265629963-b5c9748a-da88-428a-9fda-90b04a98d9d0](https://github.com/MohammedParvez129/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/143175737/d2691f0c-2949-4004-bdd2-738891955f51)

### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
