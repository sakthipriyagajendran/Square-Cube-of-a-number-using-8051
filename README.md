# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 0000H
MOV R0,#50H
MOV A,@R0 
MOV B,@R0 
MUL AB
INC R0 
MOV @R0,A
END
```
<img width="962" height="442" alt="image" src="https://github.com/user-attachments/assets/b4277930-a6d0-47fb-88d1-7528757571ee" />

## OUTPUT
<img width="1908" height="1075" alt="square" src="https://github.com/user-attachments/assets/27c7d950-9435-4112-b2f9-cfe6cf8d3bdd" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END

```
<img width="1080" height="488" alt="image" src="https://github.com/user-attachments/assets/793c37c8-005a-4538-b26d-fc81860b045d" />


## OUTPUT
<img width="1912" height="1078" alt="cube" src="https://github.com/user-attachments/assets/35145e8d-ef85-4ccb-937a-2d53c123b82f" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


