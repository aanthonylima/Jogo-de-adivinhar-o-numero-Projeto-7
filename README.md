# Jogo de adivinhar o número - Projeto 7
Um jogo de "adivinhe o número" utilizando apenas funcionalidades como if, else, while e array em JavaScript.

A principal funcionalidade do programa é permitir que o jogador tente adivinhar um número aleatório entre 1 e 100, com um sistema de pontuação baseado em tentativas. Para isso, foram utilizadas estruturas de controle como while para repetir as rodadas enquanto o jogador desejar continuar, e if/else para verificar se o palpite está correto, além de informar se o número é maior ou menor que o chute. 
O array “tabela” é usado para armazenar o resumo de cada rodada. Nele, são guardadas informações como tentativas, pontuação e número sorteado. Isso permite mostrar um histórico completo no final do jogo com console.table().
A função Math.random() combinada com Math.floor() é usada para gerar números inteiros aleatórios entre 1 e 100, garantindo que cada rodada tenha um número secreto diferente. As variáveis “tentativas”, “pontos”, “rodada” e “tabela” são utilizadas para controlar a lógica do jogo, sendo ela: contar as tentativas, calcular a pontuação, armazenar os dados de cada rodada e manter o histórico do jogo.
