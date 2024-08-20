# Atividade-3

#include <stdio.h>
#include <stdlib.h>

int main() {
	
    // Declaração da variável para armazenar o número
    int numero;

    // Solicita ao usuário que insira um número
    printf ("Digite um numero: ");
    scanf ("%i", &numero);

    // Verifica se o número é par ou ímpar
    if (numero % 2 == 0) {
        printf (" O numero e par.");
    } else {
        printf (" O numero e impar.");
    }

    return 0;
}
