# EX-NO-6-Pseudo-Random-Number


## AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## ALGORITHM:

Step-1: Start the program and import the required libraries.

Step-2: Seed the random number generator using the current time(i.e) rand(time(0));

Step-3: Get the number of randon number to generate.

Step-4: Pass the value for number of iterations and print the numbers.

Step-5: End the program.

## NAME: RAJA RITHIKA
## REG NO: 2305001029

## PROGRAM:
```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
int main() { 
int i, n; 
srand(time(0)); 
printf("Enter how many pseudorandom numbers you want to generate: "); 
scanf("%d", &n); 
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
for (i = 0; i < n; i++) { 
int randomNumber = rand() % 100; 
printf("%d ", randomNumber); 
} 
printf("\n"); 
return 0; 
}
```
## OUTPUT:

<img width="835" height="252" alt="image" src="https://github.com/user-attachments/assets/f1155700-f71c-4932-aedc-e8b0312b828e" />



## RESULT:
Hence the experiment has been executed successfully
