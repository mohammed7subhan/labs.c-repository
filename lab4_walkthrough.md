# Lab 4 - Code Walkthrough

## Code Analysis

Below is the given C program:

```c
#include <stdio.h>

int main(void)
{
    int apple;

    for(int i = 0; i < 3; i++)
    {
        apple = i;
        printf("apple: %d\n", apple);
        
        while(apple % 3 != 0)
        {
            apple = 4;
        }
        
        printf("while apple: %d\n", apple);
    }

    return 0;
}
