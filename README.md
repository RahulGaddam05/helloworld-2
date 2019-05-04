# helloworld-2 
#include<stdio.h> 
void swap(int a,int b); 
void main() 
{ 
int x,y; 
printf("enter the values of x and y"); 
scanf("%d %d",&x,&y); 
swap(x,y); 
} 
void swap(int a,int b) 
{ 
int c=a; 
a=b; 
b=c; 
printf("the value of x is %d",a);  
printf("the value of y is %d",b); 
}

