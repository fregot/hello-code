# hello-code
#include<stdio.h>
int main()
{int n,i,j,k;
  printf("enter n:");
  scanf("%d",&n);
  for(i=0;i<=n;i++)
    {for(j=0;j<=n-1-i;j++)
	printf(" ");
      for(k=0;k<=2*i;k=k+1)
	printf("*");
      printf("\n");
    }
  for(i=0;i<=n;i++)
    {
      for(k=0;k<=i;k++)
	printf(" ");
      for(j=1;j<=2*(n-i)-1;j++)
	printf("*");
      printf("\n");
    }
  
  
}
