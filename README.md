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


#### Figure -01 HALF ADDER 
![Screenshot 2023-11-26 141707](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/8d265565-5b4a-438e-8c94-bf7964d5364b)



#### Figure -02 FULL ADDER 
![Screenshot 2023-11-26 142950](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/e8316d48-6d69-4f92-bddb-9f72c4c2c06b)

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
![Screenshot 2023-11-26 144724](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/92451346-19bd-4938-b808-7ac49c95b590)
![Screenshot 2023-11-26 144724](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/df19940e-be19-435f-8cb4-55751fc14fbd)



Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
### TIMING DIAGRAM
![Screenshot 2023-11-26 142029](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/eeba215b-1af2-4e6f-8ee5-1f52b1f1ade4)
![Screenshot 2023-11-26 142848](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/ea3295ca-0634-4404-83fd-04548e8bb20b)


### TRUTH TABLE 
![download](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/54c2f0b5-b6c0-403a-9be2-35a7b74baf2d)

![download](https://github.com/TimmapuramYogeeswar/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/154494746/03f0bf20-2dd1-441a-80bb-8c053d22a428)

### Result:
Implementation-of-Half-Adder-and-Full-Adder-circuit
Implementation-of-Half-Adder-and-Full-Adder-circuit
