# Four_Bit_Signed_Calculator_Hardware_Design

In this project, I've made the schematic design of 4 bit signed calculator using the XILINX ISE 14.7. 
It can perform Addition(A+B), Subtraction(A-B), Multiplication(A x B), and Division(B/A) of four-bit signed binary numbers and gives 9-bit output in signed binary number format.

It takes the following Inputs:

1. Binary numbers A(3:0) & B(3:0)

2. Sign of numbers A & B using Input Pins Sa and Sb respectively, 1 signifies a negative number and 0 signifies a positive number

3. Mode of Operation M(1:0) where,
    00 = Adition
    01 = Subtraction
    10 = Multiplication
    11 = Division

4. There's a RESET pin too to set all Outputs equal to 0

