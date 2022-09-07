# Atividade-14
Atividade.
#include <stdio.h>
#include <math.h>
//João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso. Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar. Imprima os dados do programa com as mensagens adequadas.
main(void) {
float peso, multa;
  printf("Inserir rendimento diário por quilo: ");
  scanf("%f", &peso);
        if (peso <= 50) {
        printf("\nquantidade autorizada, sem multa de excesso!");
          }
        else { (peso >= 50); 
          multa = (peso * 4) - 200;
        printf("\n\n%.0f quilos, LIMITE EXCEDIDO!", peso);
        printf("\nVocê precisa pagar uma taxa de %.1f reais ao governo", multa);
          }

  return 0;
}
