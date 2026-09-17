# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 21.08.2026
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
```python
#include <stdio.h>

int main() {
    int number = 10;
    float price = 25.5;
    char letter = 'C';
    char text[] = "Welcome to C";
    printf("Integer value: %d\n", number);
    printf("Float value: %.1f\n", price);
    printf("Character value: %c\n", letter);
    printf("String value: %s\n", text);

    return 0;
}
```
# Output:
<img width="496" height="417" alt="image" src="https://github.com/user-attachments/assets/98e32a63-b100-475f-9c4c-2102d5995f73" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.





