# BOOLEAN_FUNCTION_MINIMIZATION
NAME : B.BARKAVI

REFERENCE NUMBER : 24901000

**EXPERIMENT NO : 2 BOOLEAN FUNCTION MINIMIZATION**

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
Boolean function minimization is a process used in digital logic design to simplify Boolean
expressions while maintaining their functional equivalence. Simplification reduces the number of
logical operations and gates required in a circuit, thereby optimizing the hardware implementation
in terms of cost, speed, and power consumption.
Objective of Minimization The goal of Boolean function minimization is to find the simplest
possible representation of a Boolean function that produces the same truth table. This process is
critical in the design of combinational circuits.
Key Concepts Boolean Function Representation:
Truth Table: A tabular representation of a Boolean function showing all possible input combinations
and corresponding outputs. Sum of Products (SOP): A Boolean expression represented as a sum
(OR) of product terms (ANDs of literals). Product of Sums (POS): A Boolean expression represented
as a product (AND) of sum terms (ORs of literals). Simplified Forms:
Canonical Forms: Minterms: An SOP form where each term is a product of all input variables in
either complemented or uncomplemented form. Maxterms: A POS form where each term is a sum
of all input variables in either complemented or uncomplemented form. Non-Canonical Forms:
Simplified SOP or POS forms that use fewer terms or literals.
Share
You said: THEORY ON BOOLEAN FUNCTION MINIMIZATION ChatGPT said: ChatGPT Theory on
Boolean Function Minimization
Boolean function minimization is a process used in digital logic design to simplify Boolean
expressions while maintaining their functional equivalence. Simplification reduces the number of
logical operations and gates required in a circuit, thereby optimizing the hardware implementation
in terms of cost, speed, and power consumption.
Objective of Minimization The goal of Boolean function minimization is to find the simplest
possible representation of a Boolean function that produces the same truth table. This process is
critical in the design of combinational circuits.
Key Concepts Boolean Function Representation:
Truth Table: A tabular representation of a Boolean function showing all possible input combinations
and corresponding outputs. Sum of Products (SOP): A Boolean expression represented as a sum
(OR) of product terms (ANDs of literals). Product of Sums (POS): A Boolean expression represented
as a product (AND) of sum terms (ORs of literals). Simplified Forms:
Canonical Forms: Minterms: An SOP form where each term is a product of all input variables in
either complemented or uncomplemented form. Maxterms: A POS form where each term is a sum
of all input variables in either complemented or uncomplemented form. Non-Canonical Forms:
Simplified SOP or POS forms that use fewer terms or literals. Methods for Minimization Algebraic
Simplification:
Use Boolean algebra laws (e.g., distributive, associative, De Morgan's theorems) to manually
simplify the function. Karnaugh Maps (K-Maps):
26/12/2024, 09:12 Editing BOOLEAN_FUNCTION_MINIMIZATION/README.md at main · 24901000/BOOLEAN_FUNCTION_MINIMIZATION
https://github.com/24901000/BOOLEAN_FUNCTION_MINIMIZATION/edit/main/README.md 1/3
A graphical technique to simplify Boolean functions for up to 6 variables. Involves grouping
adjacent 1s (SOP) or 0s (POS) into rectangles to find simplified expressions. Quine-McCluskey
Method:
A tabular algorithmic approach for minimization, suitable for functions with many variables. It
systematically identifies prime implicants and selects an optimal cover for the function. Espresso
Algorithm:
A heuristic approach used in computer-aided design (CAD) tools for minimizing complex Boolean
functions. Produces a near-optimal solution with reduced computational cost compared to
exhaustive methods.


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

  program to implement the given logic function and to verify its operations in quartus using Verilog programming. 


![Screenshot (100)](https://github.com/user-attachments/assets/2f43d5ec-23a8-407f-a8f7-e088bb93f137)


**RTL realization**
![Screenshot (101)](https://github.com/user-attachments/assets/1daad59b-c532-45ff-a9e0-6db51f565903)



**Timing Diagram**
![Screenshot (102)](https://github.com/user-attachments/assets/c3a86d0c-7252-4836-bc6f-413b0a568198)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

