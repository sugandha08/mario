# mario
mario
#include <cs50.h>
#include <stdio.h>

int main(void)
{
      int choice = get_int("enter a number");
      while (choice<=0 | choice>8)
      {
          choice = get_int("enter a number");
      }  
    
    int i,j,k;
    for (i=0; i<choice; i++)
    {
          for (k=0; k<(choice-i); k++)
           {
             printf(" ");
           }
        for (j=0; j<=i; j++)
          {
           printf("#");
          }
        printf("\n");
    }
}
