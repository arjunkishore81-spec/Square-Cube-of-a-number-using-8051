
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
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
INC R0
MOV @R0,A
END

CALCULATION
<img width="1556" height="1146" alt="image" src="https://github.com/user-attachments/assets/9c8c4fc1-5a9c-4eef-974a-303c2b35e914" />











```

## OUTPUT
<img width="984" height="592" alt="image" src="https://github.com/user-attachments/assets/6a901278-b07e-47e6-8361-b27f45d403a3" />




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
MOV @R0,A
END

CALCULATION
<img width="1568" height="1234" alt="image" src="https://github.com/user-attachments/assets/87ac4110-2cd7-4da8-8cce-965708412d66" />









```


## OUTPUT
<img width="993" height="719" alt="image" src="https://github.com/user-attachments/assets/b6f7caf0-a68f-470a-9aaa-16484dc2842a" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


