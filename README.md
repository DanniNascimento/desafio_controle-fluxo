# Desafio Controle de Fluxo - Java

Este é um projeto desenvolvido como parte de um exercício sobre controle de fluxo em Java. O objetivo do projeto é implementar a lógica para receber dois números inteiros como parâmetros e realizar uma contagem a partir do primeiro número até o segundo, validando a entrada e utilizando exceções personalizadas para garantir que o segundo número seja maior que o primeiro.

## Funcionalidade

O programa deve:
1. Receber dois números inteiros via terminal.
2. Validar se o primeiro número é maior que o segundo.
3. Caso a validação falhe, lançar uma exceção personalizada chamada ParametrosInvalidosException.
4. Caso a validação seja bem-sucedida, imprimir uma mensagem para cada número da sequência entre os dois números.

## Estrutura do Projeto

O projeto é composto pelas seguintes classes:

- *Contador.java*: Contém a lógica principal para receber os parâmetros do usuário, realizar a validação e imprimir os números.
- *ParametrosInvalidosException.java*: Uma exceção personalizada para ser lançada quando o primeiro número for maior que o segundo.
