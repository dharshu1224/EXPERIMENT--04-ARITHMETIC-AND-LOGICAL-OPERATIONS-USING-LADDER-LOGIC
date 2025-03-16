# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME:Dharshini.S
# REGISTER NUMBER:212224230061
# DEPARTMENT:AI&DS
# YEAR:1ST YEAR
## Aim:1ST YEAR
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots:
ADDITION:
![EXP4 IIOT SS1](https://github.com/user-attachments/assets/595dba57-9b1d-426c-a946-e389e2313fbf)
![EXP4 IIOT SS2](https://github.com/user-attachments/assets/e1141efa-f2fb-4f59-88a4-cf5f4412db7d)
![EXP4 IIOT SS3](https://github.com/user-attachments/assets/8d1c2623-9fb6-4fe1-b311-8155c7aab2ef)
![EXP4 IIOT SS4](https://github.com/user-attachments/assets/8b84c46c-a2fa-46ce-9e33-49be5e635022)
![EXP IIOT SS5](https://github.com/user-attachments/assets/7d646cf9-6f77-4e81-b9be-e8f2a4da21f6)
![EXP IIOT SS6](https://github.com/user-attachments/assets/32fed10c-62b6-4904-9817-8ab89be86eae)

SUBTRACTION:
![SUB1](https://github.com/user-attachments/assets/0359b3a6-28bb-4127-822f-d1f6f7910a84)
![SUB2](https://github.com/user-attachments/assets/74b7072c-4083-4300-81f9-fe6122d27cee)
![SUB3](https://github.com/user-attachments/assets/c435c0b2-6bd6-4730-bf77-c4edebaee2ce)
![SUB4](https://github.com/user-attachments/assets/14f8204c-860b-4ae9-87d3-fb7aadd3a3db)
![SUB5](https://github.com/user-attachments/assets/e73d94b0-7633-4b11-9a03-77fd6e175df6)
![SUB6](https://github.com/user-attachments/assets/b5a50217-59e7-4757-b05d-aceaaf1311bd)

MULTIPLIACTION:
![MUL1](https://github.com/user-attachments/assets/6e3b499b-e242-4561-bec2-f768b279ca05)
![MUL2](https://github.com/user-attachments/assets/202af54f-f80b-44f7-9a3d-13c4431153cb)
![MUL3](https://github.com/user-attachments/assets/00483add-16c6-417f-8a05-50793a26b463)
![MUL4](https://github.com/user-attachments/assets/97aa8f86-cc13-4e3d-8a2c-43091270e46e)
![MUL5](https://github.com/user-attachments/assets/ed2ec52d-9053-40bf-a9ef-31af6042174a)
![MUL6](https://github.com/user-attachments/assets/561e3177-7162-49f4-a160-ed88d2354a5d)

DIVISION:
![DIV1](https://github.com/user-attachments/assets/3ed44b69-1561-4e22-8b03-ab1e8ad1e75c)
![DIV2](https://github.com/user-attachments/assets/cf24c9fd-b6d6-435d-965b-2c1424c1a51e)
![DIV3](https://github.com/user-attachments/assets/a0d7da8f-37cc-4842-92d3-e3b827a6e440)
![DIV4](https://github.com/user-attachments/assets/f7d54016-7bab-44c8-ad8d-a25104a8a478)
![DIV5](https://github.com/user-attachments/assets/a50ccea1-2d65-4f1b-b483-22a93e51c129)
![DIV6](https://github.com/user-attachments/assets/49bebb75-fa88-4d61-8fe3-643107c205ea)




## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
