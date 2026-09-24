<img width="868" height="643" alt="image" src="https://github.com/user-attachments/assets/d804f7b1-d8cb-4e84-916f-e422748146c0" /># Square-Cube-of-a-number-using-8051
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
ORG 0000H
MOV R0, #30H     
MOV A, @R0      
MOV R1, A         
MOV A, #01H     
FACT:
MOV B, R1        
MUL AB           
DJNZ R1, FACT    
MOV 31H, A       
END









```

## OUTPUT
<img width="868" height="643" alt="image" src="https://github.com/user-attachments/assets/26ba2ae4-5465-403c-8b70-83fc83a67032" />


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
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END








```


## OUTPUT
<img width="1562" height="1236" alt="image" src="https://github.com/user-attachments/assets/0b8d0ce9-0902-4140-9200-dc0d2c277db1" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


