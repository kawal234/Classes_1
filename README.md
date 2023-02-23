# Classes_1
#include<stdio.h>

int main(){
//	int a;
//	printf("Enter a Number : ");
//	scanf("%d",&a);
//	int i=1;
//	while(i<=10){
//		printf("%d X %d\n",a,i);
//		i=i+1;


//	long long int fact=1;
//	int i=1,n;
//	printf("Enter a Number : ");
//	scanf("%d",&n);
//	if(n<0){
//		printf("factorial of Number is not possible");
//	}else{
//		while(i<=n){
//			fact=fact*i;
//			i=i+1;
//		}
//		printf("the factorial is : %lld",fact);
//	}
	
	
	// Sum of digits 
//	int num;
//	int count=0;
//	printf("Enter the number:");
//	scanf("%d",&num);
//	while(num!=0){
//		count=count+(num%10);
//		num=num/10;
//	}
//	
//	printf("The Value is : %d",count);


	int num;
	int count=0;
	printf("Enter the number:");
	scanf("%d",&num);
	while(num!=0){
		count=count+num;
		num=num/10;
	}
	
	printf("The Value is : %d",count);
}
