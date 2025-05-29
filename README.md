a# miprimerrepositorio
#include <stdio.h>

int main(int argc, char *argv[]) {
	int n1, n2, n3, auxiliar;
	printf("Por favor escriba el primer numero\n");
	scanf("%d", &n1);
	printf("Por favor escriba el segundo numero\n");
	scanf("%d", &n2);
	printf("Por favor escriba el tercer numero\n");
	scanf("%d", &n3);
	
	if(n1 > n3)
	{
		auxiliar = n1;
		n1 = n3;
		n3 = auxiliar;
	}
	if(n2 > n3)
	{
		auxiliar = n2;
		n2 = n3;
		n3 = auxiliar;
	}
	if(n1 > n2)
	{
		auxiliar = n1;
		n1 = n2;
		n2 = auxiliar;
	}
	
	printf("%d %d %d", n1, n2,n3);
	
	return 0;
}

