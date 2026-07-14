# Mini Projeto 02 - Python

## Descrição

Este projeto foi desenvolvido durante meus estudos de Python no curso da Data Science Academy (DSA).

O objetivo foi praticar conceitos básicos da linguagem Python em POO (Programação Orientada a Objetos) criando um mini-sistema bancário Full-Stack, aproveitando para trabalhar também a modularização como arquitetura de dados.

## Tecnologias utilizadas

- Python 3

## Funcionalidades

- Importação das bibliotecas necessárias
- Criação das classes necessárias para o projeto:
dsaentidades/: Contém as classes que representam as entidades de dados do nosso sistema (Cliente, Conta).
dsaoperacoes/: Contém a lógica de negócio e as operações principais (a classe Banco que gerencia tudo).
dsautilitarios/: Contém utilitários, como exceções customizadas.
dsa_mini_projeto2.py: É o ponto de entrada da nossa aplicação, responsável pela interface com o usuário (CLI - Command Line Interface).

A estrutura do projeto será:
Mini-Projeto2/
├── dsaentidades/
│   ├── __init__.py
│   ├── cliente.py
│   └── conta.py
├── dsaoperacoes/
│   ├── __init__.py
│   └── banco.py
├── dsautilitarios/
│   ├── __init__.py
│   └── exceptions.py
└── dsa_mini_projeto2.py