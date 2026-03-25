
# EX 3 C program to find number of years based on principle,rate & simple interest.

## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1.Start the program.

2.Declare variables for principal, rate, simple interest, and years.

3.Read values of principal, rate, and simple interest.

4.Use formula Years = (Simple Interest) / (Principal × Rate / 100) to compute years.

5.Display the number of years. 

## Program:
```
/*
Program to find number of years based on principle,rate & simple interest.

*/

#include <stdio.h>

int main() {
    float principal, rate, si, years;
    
    printf("Enter Principal: ");
    scanf("%f", &principal);
    
    printf("Enter Rate: ");
    scanf("%f", &rate);
    
    printf("Enter Simple Interest: ");
    scanf("%f", &si);
    
    years = (si * 100) / (principal * rate);
    
    printf("Number of years = %.2f\n", years);
    
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/d0d9ecec-43cd-4319-90e7-7452676c0718)



## Result:
Thus the program was executed and the output was verified successfully.
