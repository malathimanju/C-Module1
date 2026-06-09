## Conditional Statements-Compare Two Numbers
## Aim
Write a C program to read values of x and y and print whether x == y or x != y using an if-else statement.

## Algorithm
Declare variables x and y.

Read two integers x and y from the user.

Check if x is equal to y using the if statement.

If x is equal to y, print "X is equal to Y".

If x is not equal to y, print "X is NOT equal to Y".

## Program
```
#include <stdio.h>
int main() 
{
    int x, y;
    printf("Enter the value of x: ");
    scanf("%d", &x);
    printf("Enter the value of y: ");
    scanf("%d", &y);
    if (x == y)
    {
        printf("X is equal to Y\n");
    } 
    else 
    {
        printf("X is NOT equal to Y\n");
    }

    return 0;
}
```

## Output
![image](https://github.com/user-attachments/assets/239575b2-8794-4a5b-b7fb-644fb0ecefbc)

## Result
C program to read values of x and y and print whether x == y or x != y using an if-else statement is written.
