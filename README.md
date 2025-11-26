# Estruturas-Condicionais
🎫 Sistema de Verificação de Idade para Entrada em Eventos
📌 Descrição do Projeto

Este projeto consiste em um programa simples em Python que simula um sistema de verificação de idade para permitir ou negar a entrada de uma pessoa em um evento.
Ele utiliza estruturas condicionais (if, elif, else), recebe dados digitados pelo usuário e exibe mensagens de acordo com a idade informada.

🧠 Objetivos da Atividade

Utilizar corretamente estruturas condicionais

Trabalhar com entrada e saída de dados

Desenvolver um código claro, organizado e comentado

Implementar lógica básica de decisão

🖥️ Funcionamento

O programa solicita que o usuário digite sua idade.
Com base no valor informado, o sistema decide:

Idade menor que 0: Idade inválida

Menor de 14 anos: Entrada proibida

Entre 14 e 17 anos: Permitido somente com responsável

18 anos ou mais: Entrada liberada

📄 Código Completo
# Sistema de verificação de idade para entrada em eventos

# Entrada de dados
idade = int(input("Digite sua idade: "))

# Estruturas condicionais
if idade < 0:
    print("Idade inválida. Tente novamente.")

elif idade < 14:
    print("Você NÃO pode entrar no evento. É permitido apenas para maiores de 14 anos.")

elif 14 <= idade < 18:
    print("Você pode entrar, mas SOMENTE acompanhado de um responsável.")

else:
    print("Entrada liberada! Aproveite o evento 😊")

▶️ Como Executar

Instale o Python (versão 3.x).

Salve o arquivo como verificacao_idade.py.

Execute pelo terminal/cmd:

python verificacao_idade.py


Digite a idade quando solicitado.

📚 Tecnologias Utilizadas

Python 3

Entrada e saída padrão

Estruturas condicionais

📌 Autor

Projeto desenvolvido por Alex Paulo como atividade prática de Python.

# Estruturas de Repetição – Exercício

## 📌 Descrição
Este projeto contém dois programas simples em Python que exibem todos os números pares entre 1 e 100.  
A atividade demonstra o uso correto de:

- Estruturas de repetição (for e while)
- Operadores lógicos
- Organização do código

---

## 🚀 Arquivos incluídos
- contador_for.py → Exibe números pares usando *for*
- contador_while.py → Exibe números pares usando *while*

---

## 📦 Como executar
1. Certifique-se de ter o Python instalado.
2. Execute no terminal:

### Usando o código com FOR:
bash
python contador_for.py


### Usando o código com WHILE:
bash
python contador_while.py


---

## 📝 Objetivo do exercício
Exercitar:
- Loops *for* e *while*
- Condicionais simples
- Operadores lógicos
- Estruturação de código em Python

---

## 👤 Autor
Projeto desenvolvido por Alex Paulo como atividade prática de Python.

# Sistema de Cadastro de Alunos – Listas em Python

## 📌 Descrição
Este projeto recebe nomes de alunos inseridos pelo usuário, armazena todos em uma *lista* e exibe todos os nomes ao final.  
O exercício faz parte do módulo de estudo sobre *listas, entrada dinâmica de dados e iteração em Python*.

---

## 🚀 Funcionalidades
- Entrada ilimitada de nomes
- Uso adequado de listas
- Impressão organizada dos elementos
- Loop dinâmico usando while

---

## 📦 Como executar
1. Tenha o Python instalado.
2. Execute no terminal:

bash
python alunos_lista.py


---

## 📁 Estrutura

listas-alunos/
│
├── alunos_lista.py
└── README.md


---

## 👤 Autor
Projeto desenvolvido por Alex Paulo como atividade prática de Python.

# Cadastro de Produtos – Dicionários em Python

## 📌 Descrição
Este projeto implementa um sistema simples para cadastrar produtos com *nome* e *preço, armazenando as informações em um **dicionário (dict)*.  
A atividade faz parte do módulo de aprendizagem sobre manipulação de dicionários em Python.

---

## 🚀 Funcionalidades
- Cadastro de produtos com nome e preço
- Armazenamento em dict()
- Inserção e recuperação de dados
- Impressão organizada dos itens cadastrados

---

## 📦 Como executar
1. Certifique-se de ter o Python instalado.
2. Execute no terminal:

bash
python cadastro_produtos.py


---

## 📁 Estrutura do projeto

dicionario-produtos/
│
├── cadastro_produtos.py
└── README.md


---

## 👤 Autor
Projeto desenvolvido por Alex Paulo como atividade prática de Python.
