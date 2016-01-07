#include <stdio.h>
 
void main()
{
    int rows, i,  count, a = 1;
    printf("Enter the number of rows\n");
    scanf("%d", &rows);
    for (i = 1; i <= rows; i++)
    {
        for (count = 1; count <= i; count++)
        {
        printf("%d ",a);
        a++;
        }
        printf("\n");
    }
}
