📦 Sistema de Gestão de Stock em Python

Este projeto consiste numa aplicação de linha de comandos desenvolvida em Python que permite gerir o stock de materiais de forma simples, rápida e eficiente.

É ideal para iniciantes que querem praticar conceitos fundamentais de programação como:

Estruturas de dados
Funções
Condições
Ciclos
Interação com o utilizador
🎯 Objetivo

O objetivo principal deste programa é permitir ao utilizador controlar um conjunto de materiais e respetivas quantidades, simulando um pequeno sistema de inventário.

⚙️ Funcionalidades Detalhadas

➕1. Adicionar Material

Permite inserir um novo material no stock.

O utilizador introduz o nome do material
Se já existir, o sistema avisa
Caso contrário, pede a quantidade inicial

📌 Exemplo:

Nome do material: caneta
Quantidade inicial de caneta: 50

🔍 2. Consultar Stock

Permite verificar a quantidade disponível de um material específico.

Se existir, mostra a quantidade
Se não existir, informa o utilizador

📌 Exemplo:

Nome do material para consulta: caneta
O stock atual de caneta é: 50

🔄 3. Atualizar Stock

Permite modificar a quantidade de um material existente.

O utilizador pode:

Adicionar (A) unidades
Remover (R) unidades


📊 4. Exibir Stock Geral

Mostra todos os materiais registados com as respetivas quantidades.


🧠 Lógica do Programa

O sistema baseia-se num dicionário (dict), onde:

A chave é o nome do material (string)
O valor é a quantidade (inteiro)


📚 Conceitos de Programação Utilizados
Funções (def)
Dicionários (dict)
Estruturas condicionais (if/elif/else)
Ciclos (while)
Input/output (input, print)
