# SQUARE AND CUBE OF A NUMBER
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
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR  
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```
## OUTPUT
<img width="1920" height="1200" alt="NITHISH(SQUARE)" src="https://github.com/user-attachments/assets/e27e0169-6ac4-4bb4-a0ec-34fa0865f381" />

<img width="652" height="396" alt="NITHISH(SQUAREOP)" src="https://github.com/user-attachments/assets/08118f09-d744-46a2-b874-5c3fe2202821" />

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
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```
## OUTPUT
<img width="1920" height="1200" alt="NITHISH(CUBE)" src="https://github.com/user-attachments/assets/d6b9904d-a381-46be-b3b7-1d4bf00f6864" />
<img width="601" height="467" alt="NITHISH(CUBEOP)" src="https://github.com/user-attachments/assets/3b07f7af-cd53-47e0-98e6-a6d18c0117d7" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
