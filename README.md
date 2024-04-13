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

 Developed by:SACHIN M RegisterNumber: 212223040177
 **AND GATE:**
 **PROGRAM:**
 ![Screenshot 2024-04-13 110323](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/7e2dd036-b267-4d98-a009-ae37256808fb)

 **Logic symbol & Truthtable**
![Screenshot 2024-04-13 110521](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/c776a6fc-0ab0-4c06-9a65-d38f3ebec037)

**RTL realization Output:** 
![Screenshot 2024-04-13 110545](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/8eab1c56-1185-4ac1-9d3d-09deb336d70f)
**OUTPUT:**
![Screenshot 2024-04-13 110555](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/d2a58ae8-9e2c-479d-a00e-598817389d20)

**OR GATE:**
**PROGRAM:**
![Screenshot 2024-04-13 110736](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/0177208b-c123-4d7e-9265-1b7e8e9e8bc6)

 **Logic symbol & Truthtable**

![Screenshot 2024-04-13 110747](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/d2d1b710-ac68-4966-a087-46cf5b1cc020)

 **RTL realization Output:** 
![Screenshot 2024-04-13 110754](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/2bcfde96-f91f-4f76-9a2f-161aeb3a33fc)

 **OUTPUT:**
 ![Screenshot 2024-04-13 110803](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/9e341540-1cd0-4753-934a-8a5d04e3b84d)

**NOT GATE:**
**PROGRAM:**
![Screenshot 2024-04-13 111211](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/462bcd3e-2086-41fc-97c3-69f366bd25fa)

**Logic symbol & Truthtable**
![Screenshot 2024-04-13 111217](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/c61a3005-dcc6-442c-bdff-dba18534364a)

**RTL realization Output:** 
![Screenshot 2024-04-13 111225](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/2fec7069-aa3d-4dd1-ad0d-191f6ffef6bd)

**OUTPUT:**
![Screenshot 2024-04-13 111234](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/afc57fa1-9d62-494d-945c-83865783c105)


**NAND GATE:**
**PROGRAM:**
![Screenshot 2024-04-13 111747](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/0f461632-e09c-46e2-b639-0690bf43ec03)

**Logic symbol & Truthtable**
![Screenshot 2024-04-13 111754](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/b98f4e30-784b-4220-95b4-70c3b8dc3952)

**RTL realization Output:** 
![Screenshot 2024-04-13 111800](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/57bf01f2-87e7-4b35-9ab4-7ac0a7e251a5)

**OUTPUT:**
![Screenshot 2024-04-13 111808](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/9e904f02-d155-4755-a666-4005b52e4cd4)


**NOR GATE:**
**PROGRAM:**
![Screenshot 2024-04-13 111859](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/ccbc91af-ed1c-442a-b34a-db5b2e7cf7d2)

**Logic symbol & Truthtable**
![Screenshot 2024-04-13 111904](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/35b04018-58a4-4a9b-9db7-127b68b0a6d9)

**RTL realization Output:** 
![Screenshot 2024-04-13 111910](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/28f25738-d526-4925-9066-ceedf5f2a7cd)

**OUTPUT:**
![Screenshot 2024-04-13 111917](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/d1a6fb8c-ab9d-4350-8237-861769fb253a)


**EX-OR GATE:**
**PROGRAM:**
![Screenshot 2024-04-13 111923](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/fd7f119b-1abd-4ab3-a4de-1c5c6a376224)

**Logic symbol & Truthtable**
![Screenshot 2024-04-13 111929](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/f7a16c51-5c49-4bdb-b8b1-38b29fb4711d)

**RTL realization Output:** 
![Screenshot 2024-04-13 111935](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/4051bb31-9191-4063-80b5-e48f8c5756ec)

**OUTPUT:**

![Screenshot 2024-04-13 112005](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/1defbfe5-fc0a-4fd3-b3f0-dc1df2936c03)

**EX-NOR GATE:**
**PROGRAM:**
![Screenshot 2024-04-13 112011](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/69b5a406-f957-463b-82ba-7ba7e5b90ab3)

**Logic symbol & Truthtable**
![Screenshot 2024-04-13 112018](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/b4fd39d7-5d81-43d3-96c5-8a2166298ef0)

**RTL realization Output:** 
![Screenshot 2024-04-13 112025](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/24b41659-ab55-4b85-8d5c-3d26bb04f418)

**OUTPUT:**
![Screenshot 2024-04-13 112033](https://github.com/Sachin-0305/study-of-basic-gates/assets/149985717/653071be-1e84-4f25-af6d-17b284a1dbf8)


**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


