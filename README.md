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

### To Compile and Run:
For MASM:
```bash
masm palindrome.asm;
link palindrome.obj;
palindrome.exe
