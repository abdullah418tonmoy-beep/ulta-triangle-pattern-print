#include<stdio.h>
int main()
{
    int n,k,i,j;
    scanf("%d",&n);


    for(i=1;i<=4;i++)
    {
        for(j=1;j<=n+1-i;j++)
        {
            printf(" ");
        }

        for(k=1;k<=i;k++)
        {
            printf("*");
        }


        printf("\n");
    }
    return 0;

}

