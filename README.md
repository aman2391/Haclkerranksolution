#include <stdio.h>

int main()
{

 char name[100] ;
 int ask, best,runs;
 float avg; 
  printf("------------BCCI selection commitee----------------\n\n");
// enter your full name 
  printf("Enter the Name:\n");
  scanf("%s", &name);
  
 // for bolwer press 1! and for batsmen press 2!
    printf("input the number 1 or 2\n");
    scanf("%i", &ask);

 if(ask==1)
  {
    printf("----------here details about bolwer---------------\n\n");

    printf("Enter the your  average and best:"); // Take space between Avg and Best(2/25)
    scanf("%f %i", &avg,&best); 
  
    if (avg>20.08 && best<=4/45) 
    {
        printf(" congratulations! selected in team\n");
    }
    else
    {
        printf("try next time\n");
    }
  
  }
    else if(ask==2)
  {
    printf("---------------Here details about batsmen-----------------\n");
    printf("\n enter your runs and Avg: ");
    scanf("%d %f", &runs, &avg);
    if(runs>=200 && avg>=20.18)
    {
     printf("Selected\n");
    }
    else 
    {
      printf("not selected :");
    }
  }  
   return 0;
} 
