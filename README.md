# c-8
Rectangular pattern
#include <stdio.h>
int main()
{
    int i,j,n,m;
    printf("enter the row of matrix:");
    scanf("%d",&n);
    printf("enter the column of matrix:");
    scanf("%d",&m);
for(i=1;i<=n;i++){
    for(j=1;j<=m;j++){
        printf("*");
    }
    printf("\n");
}
return 0;
}
