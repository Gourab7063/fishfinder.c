#include <stdio.h>

int main() 
{
  int a,b,c,d;
  printf("Enter strictly increasing or decreasing or identical integer values\n");
  scanf("%d%d%d%d",&a,&b,&c,&d);
  if(a<b && b<c && c<d)
    printf("Fish Rising");
      else if (a>b && b>d && c>d)
      printf("fish is coming up");
      else if (a==b && b==c && c==d && d==a)
      printf("fish is at constant depth");
  else
    printf("no fish");
  return 0;
}
