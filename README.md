# Calculadora de IMC Profissional
Este projeto é uma ferramenta de linha de comando (CLI) desenvolvida em Python para calcular o (IMC) Índice de Massa Corporal. O foco principal deste repositório não é apenas o cálculo em si, mas a aplicação de boas práticas de programação, como tratamento de exceções, tipagem de dados e modularização.

# Objetivo do Projeto
O projeto foi criado para demonstrar habilidades fundamentais em Python Ele resolve o problema comum de entradas de dados inválidas e fornece uma classificação precisa baseada nos padrões da OMS.

# Tecnologias e Conceitos Aplicados
Linguagem: Python 3.x
Modularização: Divisão do código em funções com responsabilidades únicas (Cálculo, Classificação e Interface).
Type Hinting: Uso de dicas de tipo (float, str, ->) para melhorar a legibilidade e manutenção.
Tratamento de Exceções: Implementação de blocos try-except para capturar erros de entrada.
Documentação: Uso de Docstrings para descrever o comportamento de cada função

#  A Lógica por Trás
O cálculo é realizado utilizando a fórmula padrão:
IMC = peso / altura ** 2

# Exemplo de classsificação  
> 18.5 = abaixo do peso
18.5 até 24.9 = peso normal
25.0 até 29.9 = sobrepeso
<= 30.0 = obesilidade
