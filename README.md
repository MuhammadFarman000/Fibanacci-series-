   //Fibanacci-series
   
#include<stdio.h>
int fib(int n)
{
if(n==0)
		return 0;
else if(n==1)
		return 1;
else
		return fib(n-1)+fib(n-2);
	
 }
 int main()
 {
	int n,i,a;
	n=5;
	printf("fabinocci series:");
	for(i=0;i<n;i++){
	a=	fib(i);
	printf("%d",a);
	}
	return 0;
}
