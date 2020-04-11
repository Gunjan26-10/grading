# grading
Developed by Gunjan Narkhede
#include <stdio.h>
int main()
{
	int n;
	printf("enter the marks");
	scanf("%d",&n);
	if(n>=85 && n<=100)
	{
		printf("grade A");
	}
	if(n>=70 && n<=84)
	{
		printf("grade B");
	}
	if(n>=55 && n<=69)
	{
		printf("grade C");
	}
	if(n>=40 && n<=54)
	{
		printf("grade D");
	}
	if(n<40)
	{
		printf("grade F");
	}
}
