# 2024_cha7-2
#include <stdio.h>

int main()
{
    int myAge = 43;
    int *p;
    printf("myAge value = %d\n",myAge);
    printf("myAge's address in memory = %p\n",&myAge);// Outputs 0x7ffe5367e044

    p = &myAge;
    printf("pointer p's value = %p\n",*p);

    return 0;
}
