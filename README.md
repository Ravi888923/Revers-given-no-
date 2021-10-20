# Revers-given-no-
In c program
#include<stdio.h>
#include<conio.h>

int main()
{
  int n,reverse,reminder;
  printf("Enter the no to find its reverse:");
  scanf("%d", & n);
  
  While(n != 0)
  {
      reminder = n % 10;
      reverse = reverse *10 + reminder;
      n = n/10;
  }
   
   printf("Reverse of the is %d:", reverse); 
    return 0;
  }
