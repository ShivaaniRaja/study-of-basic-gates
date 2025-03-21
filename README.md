### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:R.SHIVAANI
 RegisterNumber: 212224220097

 module exp__1(a, b, y1, y2,y3,y4, y5, y6, y7);

input a,b;

output y1,y2,y3,y4, y5, y6, y7;

and g1(y1,a,b);

or g2(y2,a,b);

not g3(y3,a);

nand g4 (y4,a,b);

nor g5(y5,a,b);

xor g6(y6,a,b);

xnor g7(y7,a,b);

endmodule 
 
**Logic symbol & Truthtable**

![Screenshot 2025-03-21 093245](https://github.com/user-attachments/assets/4610d957-1987-456c-9db5-ee0cc6c27a5a)


**RTL realization Output:** 
![Screenshot 2025-03-21 140413](https://github.com/user-attachments/assets/58006014-d27c-469a-94f9-e7b06559eb1d)

**RTL**
![Screenshot 2025-03-21 140817](https://github.com/user-attachments/assets/2a9d6c06-b9b4-416a-b19c-a71891dbce76)

**Result:**
Thus the Basic Digital ICs and the verification of truth table for different logic gates were studied and successfully realized using verilog

