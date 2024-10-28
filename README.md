#include<stdio.h>
#include<conio.h>
int main()
{
int x=5,y=10,result;
clrscr();
printf("rollno:209");
printf("\n name:isa sodawala");
printf("\n x & y original value:%d%d",x,y);
result=x++;
printf("\n postfix increment:x value:%d\t result value:%d",x,result);
result=++y;
printf("n prefix increment:y value:%d\t result value:%d",y,result);
getch();
return 0;
}
