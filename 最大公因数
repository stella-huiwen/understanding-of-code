#include<stdio.h>
int main()
{
    int m,n,x,y,z;
    scanf("%d %d",&m,&n);
    x=m;
    y=n;
    if(x<y)
    {
        z=x;
        x=y;
        y=z;
    }
    while(y)
    {
        z=x%y;
        x=y;
        y=z;
    }
    printf("%d",x);
    return 0;
}
