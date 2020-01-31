#include <stdio.h>
#include <stdlib.h>
/* This code is to help convert from decimal number base to another.
The code is self explanatory and should be easy to implement
*******Awontiirim- Curly***********************************
*/
int main()
{
int base[32];
int baseToconvert;// base to convert to
int number, count; // NUmber Represents the decimal system
puts("Enter the decimal number");
scanf("%d", &number);
puts("Enter the base to conver to:");
scanf("%d", &baseToconvert);
count=0;
while(number>0){
    base[count]= number%baseToconvert;
    number= number/baseToconvert;
    count++;
}
int i;
for (i=(count-1); i>=0; i--){
    printf("%d", base[i]);
}
return 0;
}
