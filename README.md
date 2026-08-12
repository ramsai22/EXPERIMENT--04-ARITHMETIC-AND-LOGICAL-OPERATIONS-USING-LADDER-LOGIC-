# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: PAIDA RAM SAI
# REGISTER NUMBER: 212223110034
# DEPARTMENT: B.E.CSE-IOT
# DATE: 24/08/2026
## Aim:
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



##  Simulation Screenshots:

###1:
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/86a4955d-77b9-420e-8950-a7a3c392f12e" />
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/0c4af49c-2f1e-4d35-af79-830470867ef5" />

###2:
<img width="958" height="535" alt="image" src="https://github.com/user-attachments/assets/d34d108a-4fcb-4a8d-8be1-b06b2da3187b" />

<img width="950" height="533" alt="image" src="https://github.com/user-attachments/assets/702db84c-66cf-4064-a79c-befba3d3ec95" />

###3:
<img width="956" height="539" alt="image" src="https://github.com/user-attachments/assets/536be433-9dd6-4018-9ae8-5da9404f750c" />

<img width="959" height="538" alt="image" src="https://github.com/user-attachments/assets/2f9e7a54-597d-43d5-8956-f02c8069b8c7" />

###4:
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/be4fa519-e9d1-4b2c-8ead-fea4bd2dd2be" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/38537c11-7299-4f0e-ba33-79834673f973" />
###5:
<img width="959" height="535" alt="image" src="https://github.com/user-attachments/assets/bc95f291-9677-4558-861e-53e4ddd9b773" />

<img width="955" height="531" alt="image" src="https://github.com/user-attachments/assets/2cbf3621-6039-47d2-8cc6-2fbf921d7e64" />


###6:
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/bddb3c6c-a9d0-41cf-a945-f63ab6d62d79" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/9d674430-f6cf-4fd8-99aa-c01bbf7ee7d5" />


###7:
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/af9e4a6d-e625-421f-84a7-1db934c26e66" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/5ba9aa33-25e7-41fb-b3e1-27c610c7cf4f" />

###8:
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/d7e9c43b-084e-436c-b91c-b2eb991d3794" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/1c5f6cea-f808-44f8-9a46-44a4dc49ddcd" />

###9:
<img width="959" height="535" alt="image" src="https://github.com/user-attachments/assets/eb9e8d13-652c-492e-a590-dfd522920beb" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/e3494b3f-9f56-49f3-90b4-9bf989e5863a" />

###10:
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/ae3816fa-fc9a-4b74-8346-382b1bcfbae7" />

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/4a7310de-c047-44b4-9c52-c13428a083e4" />


## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
