# ASCII_value_For_loop
#include<stdio.h>
#include<stdlib.h>
int main()
{
	char i;
	system("clear");
	printf("ASCII value from \n\n");
	for(i='A';i<='Z';i+=1)
	{
		printf("\n%c,%d",i,i);
	}
	for (i='a';i<='z';i+=1)
	{
		printf("\n%c,%d",i,i);
	}
	printf("\n\n");
	return 0;
}
