![Exp3 fa code](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/e5478558-c9c8-42c0-bb69-15a69b028647)# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder:
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder:
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure:

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

### Program:

Developed by: Dharshini k

RegisterNumber: 23010696

### Code:
### Half Addear:

![Exp3 ha code](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/7e0fac41-cdbd-43ac-ab77-07df7b938024)

### Full Adder:

![Exp3 fa code](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/982417d5-3cfe-42fd-a7da-a8391925c595)

### Output:

### RTL:

### Half Addear:

![Exp3 ha RTL diagram](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/1ab04bc5-0ff6-4e2e-b1e6-542d11a030fb)

### Full Adder:

![Exp3 fa RTL diagram](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/499dbf8d-fcfd-4a2e-a1d4-16440d3cf0d4)

### TRUTH TABLE:

### Half Addear:

![Exp3 truthtable (ha)](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/e232eb4e-98d7-4e71-b08f-5a488929a54f)

### Full Adder:

![Exp3 truthtable (fa)](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/b5afff5e-c59c-4e89-b239-fd94b1d72692)

### TIMING DIAGRAM:

### Half Addear:

![exp3 ha wave](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/3503f9e0-ff2e-49d6-bc33-304270571196)

### Full Adder:

![exp 3 fa wave](https://github.com/dharshini-29/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474632/88b9eb72-61cc-417f-a939-3b9ba80d2c9f)

 ### Result:
 Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming.
