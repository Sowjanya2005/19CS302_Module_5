# EX 25 C program to check whether a given character is a vowel or consonant using pointer
## DATE: 03/04/2025
## AIM:
To write a C program to check whether a given character is a vowel or consonant using pointer

## Algorithm

1. Start.
2. Declare a variable value of type char.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Find vowel and consonants
6. End.
7. 
## Program:
```
/*
C program to check whether a given character is a vowel or consonant using pointer
Developed by: Sowjanya A
RegisterNumber:  212222060250
*/
#include <stdio.h>
int main() {
 char str[100];
 char *p;
 int vowels = 0, consonants = 0;
 scanf(" %[^\n]", str); 
 p = str; 
 while (*p != '\0') {
 if ((*p >= 'A' && *p <= 'Z') || (*p >= 'a' && *p <= 'z')) {
 char ch = (*p >= 'A' && *p <= 'Z') ? *p + 32 : *p;
 if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {
 vowels++;
 } else {
 consonants++;
 }
 }
 p++;
 }
 printf("Vowels: %d\n", vowels);
 printf("Consonants: %d\n", consonants);
 return 0;
}

```

## Output:

![image](https://github.com/user-attachments/assets/5967cd34-fa8f-4d5b-9db8-bde681620cdc)

## Result:
Thus the program was executed and the output was verified successfully.
