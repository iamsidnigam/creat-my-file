#include <stdio.h>

int main(void){
	
	int i,j;
	int n=5;
	for (i=1;i<=n;i++)
	{
		for (j=1;j<=n;j++)
		{
			printf("%c",(char)(j+64));
		}
		printf("\n");
	}

	return 0;
}
