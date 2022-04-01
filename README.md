#include<stdio.h>

int main()
{
    int n, i, c=0;
    printf("Hello world!");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        if(i%2==0)
        {
           c++;
         }
    }
    if(c==2)
    {
        printf(" %d is a prime number", n);
    }
    else
    {
        printf(" %d is a not a prime number", n);
    }
    return 0;
}
