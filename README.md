# setting-up-calendar-for-sept2015
the following code prints the calendar for September 2015
#include<stdlib.h>
#include<stdio.h>
void main()
{ int i=1;
printf("%18s \n","September 2015");
printf("%2s %2s %3s %2s %3s %2s %3s \n","S","M","Tu","W","Th","F","S");
while(i<=29)
{
if(i==1)printf("%9d",i);
else
printf("%4d",i);
printf("%3d",i+1);
if(i+2==31)
{printf("\n");break;
}
printf("%4d",i+2);
printf("%3d",i+3);
printf("%4d\n",i+4);
printf("%2d",i+5);
i=i+7;
}}
