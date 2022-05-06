#include<stdio.h>
int main()
{
    int i=34;
    int *j=&i;
    
    printf("The  value of j is %u\n",j);
    j++;
    printf("The value of j is %u\n",j);
    return 0;
}
