# hulloworld
#include <stdio.h> 
int main() {
	int a;      printf("Enter an integer: ");     
	scanf_s("%i", &a);   
	printf("a = %i\n", a);

	float b;   
	printf("Enter a float: ");    
	scanf_s("%f", &b);      printf("b = %f\n", b);

	char text[100];
	scanf_s("%s", text,100);
	printf("%s", text);



	// wait for a keypress    
	getchar();      // we need two of them because of scanf!      
	getchar();  } 
