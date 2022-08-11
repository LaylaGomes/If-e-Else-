# If-e-Else-
Exercícios de If e Else



#include <stdio.h>

int main(){

	int idade;
	
	printf("Informe a sua idade:\n");
	scanf("%d", &idade);
	
    
	if(idade >= 18){
		printf("Maior de idade!\n");
		printf("Pode entrar na Fiestaa.\n");
	} else {
		printf("Menor de idade!\n");
		printf("Não pode entrar\n");
	}  
}
______________________________________________ Outro 02_____________________________________________________________________________

#include<stdio.h>

	int main(){
int a;
int i;
int nascimento;

	printf("Em que ano estamos:\n");
	scanf("%d", &nascimento);
	printf("Qual foi seu ano de nascimento:\n");
	scanf("%d", &a);

	i=nascimento-a;

	if(i>=16){printf("Pode votar :)\n");
	}else{printf("Que pena, nao podera votar :'(\n");
}
}
