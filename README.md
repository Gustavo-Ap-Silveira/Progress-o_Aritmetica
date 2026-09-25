#include <stdio.h>
int main () {
int numero, quant, razao, i;

    printf("Digite o numero:");
    scanf("%d", &numero);
    
    printf("Digite a razão:");
    scanf("%d", &razao);
    
    printf("Digite a quantidade de termos que progressão vai ter:");
    scanf("%d", &quant);
    
    for (i = 1; i <= quant; i++){
        printf("%d\n", numero);
        numero = numero + razao;
    }
    
    return 0;
}
