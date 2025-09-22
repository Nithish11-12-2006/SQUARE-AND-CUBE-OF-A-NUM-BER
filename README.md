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
<img width="1920" height="1200" alt="NITHISH(SQUARE)" src="https://github.com/user-attachments/assets/6074021f-7c80-4ff5-b472-d3c8c6f2e748" />
<img width="652" height="396" alt="NITHISH(SQUAREOP)" src="https://github.com/user-attachments/assets/95e4d52d-d14d-4e60-942e-3cbd2ad6e54b" />

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
<img width="1920" height="1200" alt="NITHISH(CUBE)" src="https://github.com/user-attachments/assets/2d6aeb64-4f5e-4f9f-b8bd-5599534ffd60" />
<img width="601" height="467" alt="NITHISH(CUBEOP)" src="https://github.com/user-attachments/assets/b1cc2733-5740-4b2d-a72d-4fcdd6a247b6" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
