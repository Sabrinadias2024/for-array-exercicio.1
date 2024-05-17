int main() {

    int numero, maior, menor;


    printf("Digite o 1º número: ");
    scanf("%d", &numero);

    maior = menor = numero;
    
    for (int i = 2; i <= 5; ++i) {
        printf("Digite o %dº número: ", i);
        scanf("%d", &numero);

        if (numero > maior) {
            maior = numero;
        } else if (numero < menor) {
            menor = numero;
        }
    }

    printf("O maior número é: %d\n", maior);
    printf("O menor número é: %d\n", menor);

    return 0;
}
