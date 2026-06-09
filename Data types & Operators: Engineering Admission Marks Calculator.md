# Data types & Operators:Engineering Admission Marks Calculator

## Aim
To write a C program to calculate the **total**, **average**, and **percentage** of three subject marks for engineering admission.

## Algorithm
1. Declare variables `a`, `b`, `c`, `total`, `average_marks`, and `percentage`.
2. Read marks `a`, `b`, and `c` from the user.
3. Calculate `total` as the sum of `a`, `b`, and `c`.
4. Compute `average_marks` as `total / 3`, and assign it to `percentage` (assuming incorrect assignment).

## Program
```
#include <stdio.h>
int main() 
{
    int a, b, c, total;
    float average_marks, percentage;
    printf("Enter the marks of three subjects:\n");
    scanf("%d %d %d", &a, &b, &c);
    total = a + b + c;
    average_marks = total / 3.0;
    percentage = average_marks; 
    printf("Total Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average_marks);
    printf("Percentage = %.2f%%\n", percentage);
    return 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/80358b69-45b0-4efa-a9c2-c4046b789cca)

## Result
C program to calculate the **total**, **average**, and **percentage** of three subject marks for engineering admission is written
