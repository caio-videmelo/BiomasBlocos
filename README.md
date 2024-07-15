# BiomasBlocos
Desafio DIO.me: Geração de Biomas em um Mundo de Blocos

# Explicação do Código:

## Entrada de Dados:

const quantidadeGolpes = parseInt(gets());: Lê um número inteiro positivo que representa a quantidade de golpes que serão dados com a picareta.

## Tipos de Minerais:

const minerais = ["Carvao", "Ferro", "Diamante", "Pedra"];: Array que contém os tipos de minerais disponíveis para serem obtidos ao atacar a rocha.

## Estrutura de Loop:

for (let i = 1; i <= quantidadeGolpes; i++) { ... }: Loop que itera de 1 até o número de golpes informado pelo usuário.

## Cálculo do Índice do Mineral:

let minaIndex = (i - 1) % minerais.length;: Usa o operador de módulo % para calcular o índice do mineral obtido a cada golpe. O -1 é utilizado para ajustar o índice, pois arrays em JavaScript são baseados em zero.

## Exibição da Saída:

print(i + ": " + minerais[minaIndex]);: Imprime o número do golpe seguido do mineral obtido. minerais[minaIndex] recupera o mineral correspondente ao índice calculado.

## Funcionamento:

O programa percorre cada golpe dado com a picareta e determina qual mineral foi obtido, seguindo a sequência definida no array minerais. O operador de módulo assegura que após o último mineral da lista, a sequência retorne ao início, simulando o ciclo de extração.

Esse código está pronto para ser executado em um ambiente que suporte as funções gets() e print(), como é comum em desafios de plataformas de competição ou treinamento online como a DIO (Digital Innovation One).

![PrintDesafio4](https://github.com/user-attachments/assets/7a523b9f-47ae-47e1-9002-682fc146ffc5)
