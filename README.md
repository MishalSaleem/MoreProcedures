# MoreProcedures
# Palindrome Checker in Assembly (MASM/TASM Compatible)

This project is a simple *Palindrome Checker* written in *8086 Assembly Language* using *MASM syntax*, compatible with MASM, TASM, or EMU8086.

It allows the user to enter a string (max 30 characters), displays the string length, and checks whether the string is a palindrome (reads the same forward and backward).

## How It Works

### Flow:
1. Prompts user to *"ENTER A STRING:"*
2. Accepts user input until *Enter* key (ASCII 13).
3. Displays the *length* of the string.
4. Checks if the string is a *palindrome*.
5. Displays either *"PALINDROME"* or *"NOT A PALINDROME"*.

---

## Code Structure

- *DATA Segment:*
  - Prompt messages
  - Input buffer (ST)
  - Newline sequence
  - Length variable

- *CODE Segment:*
  - INPUT — takes string input
  - NEW — prints newline
  - LENGTH — calculates and prints string length
  - PALIN_CHECK — checks if the string is a palindrome
  - MAIN — the main procedure calling all others in sequence

---

## Usage

### Requirements:
- MASM / TASM / EMU8086

## Sample Output
![image](https://github.com/user-attachments/assets/97a6c6bd-6009-4c56-b89a-9ece20460a04)
![image](https://github.com/user-attachments/assets/cc75ac8c-60c3-488d-821d-022f34e291f2)

# Character Sorting Program in MASM  

This is a simple x86 assembly language program written in MASM syntax. The program prompts the user to enter three characters, sorts them in ascending order, and then displays the sorted characters on separate lines.  

## Features  

- Prompts the user for three characters  
- Stores the input characters  
- Sorts the characters in ascending ASCII order  
- Displays the sorted characters each on a new line  

---  

## How to Assemble and Run  

### Prerequisites:  
- MASM (Microsoft Macro Assembler)  
- DOSBox or a DOS-compatible environment (since it uses DOS system calls)  

### Steps:  

1. Save the source code to a file, e.g., `char_sort.asm`.  

2. Assemble the code:   
ml /c /coff char_sort.asm

# Character Sorting Program in MASM  

This is a simple x86 assembly language program written in MASM syntax. The program prompts the user to enter three characters, sorts them in ascending order, and then displays the sorted characters on separate lines.  

---  

## Features  

- Prompts the user for three characters  
- Stores the input characters  
- Sorts the characters in ascending ASCII order  
- Displays the sorted characters each on a new line  

---  

## How to Assemble and Run  

### Prerequisites:  
- MASM (Microsoft Macro Assembler)  
- DOSBox or a DOS-compatible environment (since it uses DOS system calls)  

### Steps:  

1. Save the source code to a file, e.g., `char_sort.asm`.  

2. Assemble the code:  
```bash  
ml /c /coff char_sort.asm  
