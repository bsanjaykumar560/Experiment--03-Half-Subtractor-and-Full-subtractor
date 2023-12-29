# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:


half subtractor:



![Exp4 hs code](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/ad7e5b94-462d-4cb5-adf0-05c7473c311c)


full substarctor:



![Exp4 fs code](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/be445d86-b4dc-4d98-9e1e-80603251f4ce)

/*
OUTPUT:
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: SANJAY KUMAR.B
RegisterNumber:  23004077
*/



## Truthtable

half substractor:


![Exp4 truthtable hs](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/da98851f-bde0-4d85-af89-17768c7e3c49)



full substactor:


![Exp4 truthtable hs](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/9de40d4d-e404-4622-91a3-5a2b44af4b10)




##  RTL realization
half substactor:




![Exp4 hs RTL diagram](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/ad435f93-6bca-4edc-b449-6a45aa7c5b2d)


full stustactor:




![Exp4 fs RTL diagram](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/8f9855ec-9e33-41de-96d7-a84ee04d38d8)







## Timing diagram 

half substactor:




![hs wave](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/0d30b46e-69ae-43be-b2cb-ad105d919149)

full substactor:




![fs wave](https://github.com/bsanjaykumar560/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145954153/ceba27b9-fb3c-44ee-b565-1b3e22b957e7)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
