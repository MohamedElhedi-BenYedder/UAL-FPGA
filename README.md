# UAL
The project consists of an Arithmetic and Logic Unit implemented on the FPGA board
5CGXFC5C6F27C7.
This arithmetic and logic unit performs the following 8 operations:
* Arithmetic operations
**the addition
**The subtraction
**The multiplication
* Logic operations:
** XOR 
** OR 
** AND 
** Right shift
** Left shift

The unit takes as inputs two binary words each of which has 4 bits and returns the
results of these operations on 8bits
The display will be at the same time on the LEDs (red and green diodes) and also on the 4 displays 7-
segments.
This project is broken down into a sub-part or sub-block that each is responsible for a
operation or a feature:
* XOR block
* OR block
* AND block
* ADDITION block
* SUBTRACTION block (subtraction and rectification of the binary word if it is negative before
display it on 7-segment)
* Multiplication block
* Shift block (performs the shift to the right and to the left) 
* Selection part:
-select the operation (through 8 MUX8 vers1)
-separate the selection and the calculation (use the bits of binary words B as bits of
selection or for calculation)
-display the letter C on 7-segment in selection mode and use the same display
for calculation in calculation mode, it should be noted that the results for the arithmetic operations will be
displayed under the hexadecimal base.
* Display part  
