# format-specifier
This is a program to convert decimal number into various system like hexadecimal, octal, etc using format specifier in program of pointers in c programming.


#include<stdio.h>

int main()
{
    int a;
    printf("Enter one number a:");
    scanf("%d",&a);
    int* ptra= &a;
    printf("The address of pointer to a is %p\n",&ptra);
    printf("Value of a is %d\n",*ptra);
    printf("Adderss of a is %p\n",*ptra);
    printf("Octal representation of a is %o\n",*ptra);
    printf("Hexadecimal of a is %x\n",*ptra);
    return 0;
}
