# simple-interest
#include <stdio.h>

int main(){
    int si,p,r,t;
    printf("enter principle value :");
    scanf("%d",&p);
     printf("enter rate value :");
    scanf("%d",&r);
     printf("enter time value :");
    scanf("%d",&t);
    si=(p*r*t)/100;
    printf("simple interest=%d",si);
  return 0;
}
