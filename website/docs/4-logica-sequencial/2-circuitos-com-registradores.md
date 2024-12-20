---
title: Circuítos com Registradores
description: Grupo 8
---


# Circuítos com Registradores
Grupo 8
## O que são Registradores?
Registradores são conjuntos de flip-flops conectados de tal forma que armazenam n bits de informação, todos sincronizados por um clock comum. Eles funcionam como uma memória volátil, especialmente na unidade central de processamento (CPU), onde são utilizados durante a execução dos programas. Apesar de serem rápidos, possuem uma capacidade de armazenamento muito limitada.
## Registradores Shift:
Em registradores shift, os valores armazenados em sequência são deslocados, fazendo com que o valor de cada flip-flop seja "empurrado" para o próximo. Esse deslocamento pode multiplicar ou dividir um número binário por 2 a cada pulso de clock, pois os valores avançam a cada subida do clock.
## Acesso Paralelo:
Em muitas aplicações, é necessário transferir dados de n bits. Isso pode ser feito de duas maneiras principais: transferência paralela ou transferência serial.

- **Transferência Paralela:** Todos os bits são transferidos ao mesmo tempo, em um único pulso de clock, mas isso requer n fios, um para cada bit.
- **Transferência Serial:** Alternativamente, podemos usar apenas um fio para enviar os bits um a um, usando um registrador shift. Esse método leva n ciclos de clock para transferir todos os bits, mas reduz a quantidade de fios necessários.

## Exercícios:

1. Considere a sequência 0101 em um registrador de 4 bits. Depois de 2 deslocamentos para a direita, qual será a sequência?

2. Um sistema precisa transferir 16 bits de informações. Quantos fios serão necessários para fazer isso de forma paralela? e de forma serial?

3. Faça um registrador de 4 bits utilizando flip-flops do tipo D.

4. Algebricamente o que ocorre com um número ao deslocarmos ele para a esquerda? e para a direita?

## Respostas:

1. r: `0001`

2. R: paralela: 16 fios, serial: 1 fio

3. R:

4. R: Ao deslocar para a direita dividimos o numero por 2 e ao deslocar para a esquerda, multiplicamos ele por 2.

:::info Autores

- Heitor Gomes de Oliveira - 15458350
- Dante Brito Lourenço - 15447326
- João Gabriel Pieroli da Silva - 15678578
:::
