#include<stdio.h>
int main()
{
  int number1,number2,x,y;
  printf("\nEnter two numbers:");
  scanf("%d %d",&number1,&number2);
  x=number1,y=number2;
  while(number1!=number2)
{
  if(number1>number2)
  number1=number1-number2;
  else
  number2=number2-number1;
}
  printf("L.C.M=%d",x*y/number1);
  return 0;
}


