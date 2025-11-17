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
