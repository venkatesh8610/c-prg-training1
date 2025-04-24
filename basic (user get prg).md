#include <stdio.h>

void main()
{
    char n[35],g,a[100];
    float c;
    printf("ENTER YOUR DETAILS :-\n NAME : \n CGPA : \n GRADE : \n ADDRESS : \n");
    scanf("%s%f%s%s",n,&c,&g,a);
    printf("\n NAME : %s \n CGPA : %.3f \n GRADE : %c \n ADDRESS : %s \n",n,c,g,a);
}
