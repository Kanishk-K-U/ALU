# Arithmetic Logic Unit
One of the essential digital logic components of CPUs is the Arithmetic Logic Unit (ALU). It usually performs 
- addition
- subtraction
- multiplication
- division 
as some of the logic and arithmetic operations.

### Objective
To design an Arithmetic Logic Unit (ALU). It usually performs logical and arithmetic operations. VHDL is used to design and implement an ALU.

### Block Diagram
![](https://github.com/Kanishk-K-U/ALU/blob/main/block.png)

### Implementation 
- A is forced to 8 Bit input _(A is set to = 0000001)_
- B is forced to 8 Bit input _(A is set to = 0000010)_
- alu_sel is forced to choose the arithematic operation 
- alu_result will be the output

### Operation
                    
 Operation    |    Input A    |   Input B   |   Output
------------- | ------------- | ----------- | ---------
Addition  | 0000001 | 0000010 | 00000011
Subraction  | 0000001 | 0000010 | 11111111
Multiplication  | 0000001 | 0000010 | 00000010
Division  | 0000001 | 0000010 | 00000000
Logical shift left  | 0000001 | 0000010 | 00000010
Logical shift right  | 0000001 | 0000010 | 00000000
Rotate left  | 0000001 | 0000010 | 00000010
Rotate right  | 0000001 | 0000010 | 10000000
AND   | 0000001 | 0000010 | 00000000
OR  |  0000001 | 0000010 | 00000000
XOR  |  0000001 | 0000010 | 00000011
NOR  |  0000001 | 0000010 | 11111100
NAND  |  0000001 | 0000010 | 11111111
XNOR  |  0000001 | 0000010 | 11111100
XNOR  |  0000001 | 0000010 | 11111100
A>B |  0000001 | 0000010 | 00000000
A<B |  0000001 | 0000010 | 11111111
A=B |  0000001 | 0000010 | 00000000

### OUTPUT
![](https://github.com/Kanishk-K-U/ALU/blob/main/OP.png)





