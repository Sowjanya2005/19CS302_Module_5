# EX 21 C program to calculate the area of a triangle using pointer.
## DATE: 03/04/2025
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
   
1. Start. 
2. Declare three variable value of type float. 
3. Prompt the user to enter  values. 
4. Read the values using scanf. 
5. Find the area of triangle using formula 
6. End.
   
## Program:
```

/*
C program to calculate the area of a triangle using pointer.
Developed by: Sowjanya A
RegisterNumber:  212222060250
*/
#include <stdio.h> 
int main() { 
    float base, height, area; 
    float *pBase = &base, *pHeight = &height; 
    scanf("%f", pBase); 
    scanf("%f", pHeight); 
    area = 0.5 * (*pBase) * (*pHeight); 
    printf("%.2f\n", area); 
}
```

## Output:

![image](https://github.com/user-attachments/assets/b8ed7636-b8b1-407a-8737-0fc70ccf01b5)

## Result:
Thus the program was executed and the output was verified successfully.
