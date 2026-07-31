# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;

    srand(time(NULL));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Generated Pseudorandom Numbers:\n");

    for(i = 0; i < n; i++)
    {
        printf("%d ", rand());
    }

    return 0;
}
```

# OUTPUT:
<img width="926" height="278" alt="image" src="https://github.com/user-attachments/assets/9da7f728-9d73-4b7c-8e91-a8340e0d6b57" />


# RESULT:
Thus, the implementation of Pseudo-Random-Number had been executed successfully. 
