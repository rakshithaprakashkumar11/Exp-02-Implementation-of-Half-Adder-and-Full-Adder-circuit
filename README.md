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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: RAKSHITHA P

RegisterNumber:  23003502


Code:

Full Adder:

![Exp3 fa code](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/777d51bb-ffa8-46f1-a088-f553a52752ac)

Half Adder:

![Exp3 ha code](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/90516393-e2a1-46a4-81f7-3be02183e7c9)

RTL diagram

Full Adder:

![Exp3 fa RTL diagram](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/8c1687a5-d509-40fb-a637-629e5952dd5e)

Half Adder:

![Exp3 ha RTL diagram](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/e38331fe-5671-48e6-afc4-1b93d8886f55)

Truth Table :

Full Adder:

![Exp3 truthtable (fa)](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/4c7165dd-f5f1-43d1-9c3a-fce223b0761b)

Half Adder:

![Exp3 truthtable (ha)](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/c79163c1-efa8-4f85-92a9-1f8ee6dccee6)

Output:

Full Adder:

![Exp3 fa wave](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/d828e65e-9257-478a-b997-b500aa024f36)

Half Adder:

![halfadder-wave](https://github.com/rakshithaprakashkumar11/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150994181/dee7a5f5-d90d-4192-a281-fb0688b313af)





### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
