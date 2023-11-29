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
### Program:
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
## Half Adder Circuit:
![Screenshot 2023-11-21 212625](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/3a04f293-2c92-4e47-b128-b0af2505cf79)

## Full Adder Circuit:
![Screenshot 2023-11-21 212632](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/bcc38eb8-633b-4479-bde4-ab6c9b7b861f)
### Output:
### TRUTH TABLE:
 ##  Half Adder Circuit:
![Screenshot 2023-11-21 212643](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/254679be-aaff-4ce5-bf82-6d790541ddee)

 ## Full Adder Circuit:
 ![Screenshot 2023-11-21 212650](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/ed58476a-7747-4bbd-8a74-4736c7a14b61)

### RTL:
##  Half Adder Circuit:
![Screenshot 2023-11-21 212659](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/dfb7115a-b766-46a1-8192-9df56a7bdbd5)
## Full Adder Circuit:
![Screenshot 2023-11-21 212706](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/1cf906b6-d260-4d96-8f0d-10d3188d528b)

### WAVEFORM:
##  Half Adder Circuit:
![Screenshot 2023-11-21 212722](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/8482a7f0-9d57-4441-a97d-bb5ed0072362)
## Full Adder Circuit:
![Screenshot 2023-11-21 212728](https://github.com/Narmadhasree48/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144979451/68c2e48a-ae51-494c-9025-dccc72f9e59a)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
