# sistema_banc-rio.py

Este repositório contém a solução para o desafio de projeto "Criando um Sistema Bancário", parte do bootcamp da DIO. O objetivo é implementar as operações essenciais de um banco para um único usuário utilizando a linguagem Python.

## Objetivo do Desafio
Desenvolver um sistema que modernize as operações de um grande banco, focando na simplicidade e eficiência da primeira versão.

##  Funcionalidades Implementadas

### 1. Depósito 
- Permite depositar apenas valores positivos.
- Todos os depósitos são armazenados em uma variável para exibição no extrato.

### 2. Saque 
- Limite de 3 saques diários.
- Limite máximo de R$ 500,00 por saque.
- Verificação de saldo: o sistema impede o saque caso não haja dinheiro suficiente em conta.
- Todos os saques são registrados no extrato.

### 3. Extrato
- Lista todos os depósitos e saques realizados.
- Exibe o saldo atual formatado como "R$ xxx.xx".
- Caso não haja movimentações, exibe a mensagem: "Não foram realizadas movimentações."

## Tecnologias Utilizadas
* Python 3.x
