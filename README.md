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
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int seed, n;

    printf("Enter the seed value: ");
    scanf("%d", &seed);

    printf("Enter how many random numbers to generate: ");
    scanf("%d", &n);

    srand(seed); // use seed for reproducible random numbers

    printf("Pseudo Random Numbers: ");
    for (int i = 0; i < n; i++) {
        printf("%d ", rand() % 100); // keep numbers small (0–99)
    }

    printf("\n");
    return 0;
}

```
# OUTPUT:
<img width="1919" height="683" alt="Screenshot 2025-11-02 175958" src="https://github.com/user-attachments/assets/bad6ba2d-b1e8-4657-8b57-852452f13f20" />

# RESULT:
The implementation of Pseudorandom Number Generation using Standard library is successful.
