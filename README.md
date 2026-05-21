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
Square 
ORG 0000H
MOV R0,#50H
MOV A,@R0 
MOV B,@R0 
MUL AB
INC R0 
MOV @R0,A
END




```

## OUTPUT
Square
<img width="1086" height="606" alt="WhatsApp Image 2026-05-20 at 8 18 53 PM" src="https://github.com/user-attachments/assets/d99dd6bc-286f-4b4e-8e99-ce66630adc66" />

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
Cube
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


## OUTPUT
Cube
<img width="1083" height="608" alt="WhatsApp Image 2026-05-20 at 8 18 54 PM" src="https://github.com/user-attachments/assets/fb27fc82-7d53-44f9-bd98-57d47224a817" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


Dinosaurs were a highly diverse group of reptiles that first appeared roughly 245 million years ago. Ruling the Earth for over 160 million years, they ranged from tiny, chicken-sized predators to massive, long-necked herbivores. Today, scientists classify modern birds as living dinosaurs.

Around 66 million years ago, a catastrophic event—widely believed to be a massive asteroid strike off the coast of the modern-day Yucatán Peninsula—triggered drastic global climate changes. This Cretaceous-Paleogene (K-Pg) extinction event wiped out all non-avian dinosaur species. However, a small lineage of feathered dinosaurs survived, evolved, and eventually diversified into the birds we see today.
