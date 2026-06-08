# Projeto calculadora

Calculadora em Python
Descrição

Este projeto consiste em uma calculadora desenvolvida em Python que permite ao usuário realizar operações matemáticas básicas por meio do terminal.

A aplicação foi criada com foco no aprendizado de estruturas fundamentais da linguagem Python, como:

Variáveis
Entrada e saída de dados
Estruturas condicionais (if, elif e else)
Estruturas de repetição (while)
Tratamento de exceções (try e except)
Operadores matemáticos
Funcionalidades

A calculadora realiza as seguintes operações:

Operação	Operador
Adição	+
Subtração	-
Multiplicação	*
Divisão	/
Divisão Inteira	//
Resto da Divisão	%
Exponenciação	**

Além disso, o programa:

Exibe uma apresentação inicial para o usuário.
Valida entradas numéricas.
Trata erros de divisão por zero.
Permite realizar múltiplos cálculos sem reiniciar o programa.
Como executar o projeto
Requisitos
Python 3 instalado na máquina.
Executando o arquivo Python

No terminal, navegue até a pasta do projeto e execute:

python calculadora.py

ou

python3 calculadora.py
Como executar utilizando o arquivo .sh

Crie um arquivo chamado executar.sh com o seguinte conteúdo:

#!/bin/bash
python3 calculadora.py

Conceda permissão de execução:

chmod +x executar.sh

Execute o script:

./executar.sh
Explicação do código
Apresentação ao usuário

O programa solicita o nome do usuário e oferece uma breve explicação sobre o funcionamento da calculadora.

Entrada de dados

Os valores são recebidos através da função input() e convertidos para números utilizando float().

Tratamento de erros

O código utiliza try e except para impedir que entradas inválidas interrompam a execução do programa.

Exemplo:

try:
    valor1 = float(input('Digite o primeiro valor: '))
except ValueError:
    print('Entrada inválida.')
Estruturas condicionais

As operações matemáticas são executadas utilizando estruturas if, elif e else, verificando qual operador foi informado pelo usuário.

Estruturas de repetição

O programa utiliza laços while para:

Validar entradas.
Permitir que o usuário realize várias operações consecutivas.
Encerrar o programa somente quando o usuário desejar.
Tratamento de divisão por zero

Antes de realizar divisões, o código verifica se o segundo valor é igual a zero para evitar erros matemáticos.

Autor

Projeto desenvolvido por mim como atividade prática de Python para aplicação de conceitos fundamentais da linguagem.
