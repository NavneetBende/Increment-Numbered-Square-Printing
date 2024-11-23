PRINTING PATTERN:
1111

2222

3333

4444

PREREQUISITE:
Basic knowledge of C language and loops.

ALGORITHM:
Take number of rows/columns as input from the user and save it in any variable (‘r’in this case).
Run a loop ‘r’ number of times to iterate through the rows. From i=0 to i<r.  The loop should be structured as for( i=0 ; i<r ; i++).
Run a nested loop inside the previous loop to iterate through the columns. From  j=0 to j<r. The loop should be structured as for(j=0 ; j<r ; j++).
Inside the nested loop print ‘i’ to print the incremented value in each column of a row.
Inside the main loop print a newline to move to the next line after a row.
CODE IN C:
#include<stdio.h>
int main()
{
int i,j,r;                                       //declaring integer variables i,j for loops , r for number of rows
printf("Enter the number of rows/columns :\n");  //asking user for the number of rows;
scanf("%d",&r);                                  //taking number of rows and saving in variable r
for(i=1;i<=r;i++)                                //loop for number of rows
   {
      for(j=0;j<r;j++)                           //loop to print digit in every column of a row
        {
           printf("%d",i);                       //printing digit
        }
      printf("\n");                              //printing newline
   }
}
TAKING INPUT:
DISPLAYING OUTPUT:
