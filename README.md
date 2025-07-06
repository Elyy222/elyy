#include <stdio.h>

// Desafio Super Trunfo - Rio de Janeiro ; São Paulo
// Tema 2 - Comparação das Cartas
// Este código inicial serve como base para o desenvolvimento do sistema de comparação de cartas de cidades.
// Siga os comentários para implementar cada parte do desafio.

int main() {
    // Definição das variáveis para armazenar as propriedades das cidades

    // Carta 1 - São Paulo
    char estadoA[] = "A";
    char codigoA[] = "A01";
    char nomeCidadeA[] = "São Paulo";
    int populacaoA = 12325000;
    float areaA = 1521.11;
    float pibA = 699.28;
    int pontosTuristicosA = 50;

    // Carta 2 - Rio de Janeiro
    char estadoB[] = "B";
    char codigoB[] = "B02";
    char nomeCidadeB[] = "Rio de Janeiro";
    int populacaoB = 6748000;
    float areaB = 1200.25;
    float pibB = 300.50;
    int pontosTuristicosB = 30;

    // Comparação de Cartas
    printf("Comparando População:\n");
    if (populacaoA > populacaoB) {
        printf("%s tem maior população que %s.\n", nomeCidadeA, nomeCidadeB);
    } else {
        printf("%s tem maior população que %s.\n", nomeCidadeB, nomeCidadeA);
    }

    printf("\nComparando Área:\n");
    if (areaA > areaB) {
        printf("%s tem maior área que %s.\n", nomeCidadeA, nomeCidadeB);
    } else {
        printf("%s tem maior área que %s.\n", nomeCidadeB, nomeCidadeA);
    }

    printf("\nComparando PIB:\n");
    if (pibA > pibB) {
        printf("%s tem maior PIB que %s.\n", nomeCidadeA, nomeCidadeB);
    } else {
        printf("%s tem maior PIB que %s.\n", nomeCidadeB, nomeCidadeA);
    }

    printf("\nComparando Pontos Turísticos:\n");
    if (pontosTuristicosA > pontosTuristicosB) {
        printf("%s tem mais pontos turísticos que %s.\n", nomeCidadeA, nomeCidadeB);
    } else {
        printf("%s tem mais pontos turísticos que %s.\n", nomeCidadeB, nomeCidadeA);
    }

    return 0;
}