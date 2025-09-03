# 1st-code
to print the max of an array


#include <stdio.h>

int main() {
    int i,a[7]={1,4,6,3,8,5,7},max=a[0];
    for(i=0;i<=6;i++)
    {
        if(max<a[i])
        {
            max=a[i];
             
        }
        
       
        }
        printf("%d",max);

    return 0;
}
