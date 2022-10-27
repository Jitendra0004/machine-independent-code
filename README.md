# machine-independent-code
#include<stdio.h>
#include<conio.h>
int main(){
    int f=1,n;
    printf("Enter the number : ");
    scanf("%d",&n);
    do{
    f=f*n;
    n--;
    } while(n>0);
    printf("The factorial value is : %d",f);
    return(0);
    
    printf("%d",f); /* unreachable */
}


/*
#include<stdio.h>
#include<conio.h>
int main(){
    int i,n;
    int fact=1;
    printf("Enter the number : ");
    scanf("%d",&n);
    for(i=n;i>=1;i--)
    fact=fact*i;
    printf("The factorial value is : %d",fact);
    return(0);
    
    printf("%d",fact); /* unreachable */
        }
