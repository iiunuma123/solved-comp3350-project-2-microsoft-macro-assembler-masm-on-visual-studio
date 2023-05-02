Download Link: https://assignmentchef.com/product/solved-comp3350-project-2-microsoft-macro-assembler-masm-on-visual-studio
<br>
Goals:

<ul>

 <li>Get you familiar with Microsoft Macro Assembler (MASM) on Visual Studio.</li>

 <li>Setting up an assembly program.</li>

 <li>Defining and accessing Arrays.</li>

 <li>Dealing with Registers and instructions.</li>

 <li>Debugging and running your assembly code.</li>

</ul>

Design:

The objective of this assignment is to create a program that will read a value from an array, add another value to this, and save the sum of those two values into a specific register.

Create a BYTE array with the label ‘input’. ‘input’ should have eight elements. You should place values 1,2,3,4,5,6,7,8 in each of the elements of this array.

(20 points) Create a BYTE variable with the label ‘shift’. ‘shift’ should hold a single value 2. (20 points) Set the values of the EAX, EBX, ECX, and EDX to 0.

You then sum the value of this variable with each of the individual values in the array ‘input’.

The program should read each of the values from the array ‘input’ one at a time and add the value ‘shift’ to it.

The sum should be stored in the “correct” register:

The first sums should be in the high position of the AX register.

The second sum should be in the low position of the AX register.

The third sum should be in the high position of the BX register.

The fourth sum should be in the low position of the BX register.

The fifth sum should be in the high position of the CX register.

The sixth sum should be in the low position of the CX register.

The seventh sum should be in the high position of the DX register.

The eighth sum should be in the low position of the DX register.