# Validação de Dados em Python 🐍

Estudante de **Engenharia Eletrotécnica e de Computadores na FEUP** | Projetos pessoais em Python e programação.

## Sobre o projeto
Este projeto foi desenvolvido durante o ensino secundário em Python.  
Objetivo: **Validar dados de entrada do utilizador** de forma segura, garantindo que os valores inseridos atendem a regras específicas para nome, idade, salário, sexo e estado civil.

---

## Funcionalidades
- Validação de **nome** (mais de 3 caracteres)
- Validação de **idade** (entre 0 e 150)
- Validação de **salário** (maior que 0)
- Validação de **sexo** (`f` ou `m`)
- Validação de **estado civil** (`s`, `c`, `v` ou `d`)
- Exibição dos dados validados de forma organizada

---

## Tecnologias usadas
- Python 3.x
- Input/output no terminal

---

## Como usar
1. Clone o repositório


Exemplo de uso:

Digite um nome (superior a 3 caracteres): Jo
Nome inválido! Deve ter mais de 3 caracteres.
Digite novamente o nome: João
Digite a idade (0 a 150): 200
Idade inválida!
Digite novamente a idade: 25
Digite o salário: -500
Salário inválido! Deve ser maior que zero.
Digite novamente o salário: 1200
Digite o sexo (f para feminino, m para masculino): x
Sexo inválido! Digite apenas 'f' ou 'm'.
Digite novamente o sexo (f/m): m
Digite o estado civil (s, c, v, d): z
Estado civil inválido!
Digite uma das opções (s, c, v ou d): s

--- Dados Validados ---
Nome: João
Idade: 25
Salário: 1200.0
Sexo: m
Estado Civil: s
