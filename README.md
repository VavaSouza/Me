# Me
#include <stdio.h>

int main() {
    // Declaração de variáveis
    float num1, num2;

    // Entrada de dados
    printf("Digite o primeiro número real: ");
    scanf("%f", &num1);

    printf("Digite o segundo número real: ");
    scanf("%f", &num2);

    // Operações
    float soma = num1 + num2;
    float subtracao = num1 - num2;
    float multiplicacao = num1 * num2;

    // Verificação para evitar divisão por zero
    float divisao = (num2 != 0) ? (num1 / num2) : 0;

    // Saída
    printf("Soma: %.2f\n", soma);
    printf("Subtração: %.2f\n", subtracao);
    printf("Multiplicação: %.2f\n", multiplicacao);
    printf("Divisão: %.2f\n", divisao);

    return 0;
} 
