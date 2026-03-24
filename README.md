#include<stdio.h>
#include<conio.h>
void main()
{
   int n,i,flag=0;
   printf("Enter the Number");
   scanf("%d",&n);
   for(i=0;i%2==0;i++)
   {
    if(i%n==0)
    {
      flag=1;
      break;
    }
   }
   if(i==0)
   {
    printf("No. is not prime");
   }
   else
   {
    printf{"No. is Prime");
   }
   getch();
   }
   
