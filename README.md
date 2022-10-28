//# perimeter-circumference-area.c//
#include<stdio.h>
int main()
{
    float l,b,r,ar,pm,ac,cir;
    printf("enter the lenght:");
    scanf("%f",&l);
    printf("enter the breadth:");
    scanf("%f",&b);
    printf("enter the radious:");
    scanf("%f",&r);
    ar=l*b;
    pm=2*(b+l);
    ac=3.142*r*r;
    cir=2*3.142*r;
    printf("area of rectangle=%f\n",ar);
    printf("perimeter pf rectangle=%f\n",pm);
    printf("area of circle=%f\n",ac);
    printf("circumference of circle=%f\n",cir);
    return 0;
}
