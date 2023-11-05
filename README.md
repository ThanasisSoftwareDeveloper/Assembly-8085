# Assembly-8085
3rd GE/ 3rd Topic/A
--------------------

Given a table containing text in ASCII code, using only the lowercase characters of the Roman alphabet and space. The number of characters in the table (≤ 255) is stored in memory location 4203H, and the character table is stored from the next memory location onwards, in consecutive memory locations. Develop a program in 8085 assembly language that compresses this text by removing the blank character (space) from any point in the text found. In place of each blank character, place the next character of the text, after it has been converted to upper case. At the end of the table, place the value FFH in as many positions as the number of substitutions of the blank character made.  

Example: In the table the text is stored:

"this is a sample text"

After compression, the table will have the following contents (changes are highlighted in yellow):

"thisIsASampleTextFFFFFFFFFFFFFF"

4th GE/ 4th Topic/A
--------------------
Write the microinstruction subroutines for each of the following instructions:
1. XOR (R1), (R2), (R3) ; Mem[R1] XOR Mem[R2]  Mem[R3]
2. ADD R1, (R2, R3), 3FA5h ; R1 + Mem[R2+R3]  Mem[3FA5h]
3. MOV R1(A0B0h), R2 ; R2  Mem[R1+Mem[A0B0h]]
4. JMP ((F00Ah, R3)) ; PC  Mem[Mem[F00Ah+R3]]
