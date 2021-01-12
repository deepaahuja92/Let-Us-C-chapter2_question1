//# Let-Us-C-chapter2_question1
#include<stdio.h>
int main()
{
int num,digit,sum=0;
printf("Enter the five digit number:");
scanf("%d",&num);
digit=num/10000;
sum+=digit;
num%=10000;
digit=num/1000;
sum+=digit;
num%=1000;
digit=num/100;
sum+=digit;
num%=100;
digit=num/10;
sum+=digit;
num%=10;
sum+=num;
printf("sum of the numbers:%d",sum);
return 0;
}
