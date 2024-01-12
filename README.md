# desafios-dio

**Compilado de desafios de código do Felipão proposto pelo Bootcamp Potência Tech Ifood-Programação do Zero da Dio.

1️⃣ Classificador de Nível de Herói
Objetivo: Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar algumas das mensagens abaixo:

Se XP menor do que 1.000 = Ferro, Se XP entre 1.001 e 2.000 = Bronze, Se XP entre 2.001 e 5.000 = Prata, Se XP entre 6.001 e 7.000 = Ouro, Se XP entre 7.001 e 8.000 = Platina, Se XP entre 8.001 e 9.000 = Ascendente, Se XP entre 9.001 e 10.000 = Imortal, Se XP maior ou igual a 10.001 = Radiante.

Ao final deverá ser exibida uma mensagem: "O Herói de nome {nome} está no nível de {nível}."

Conhecimentos aplicados no jogo
Variáveis:nome, xp, nivel
Operadores lógicos:&&
Estruturas condicionais:else, if else
Funções:console.log()


2️⃣ Calculadora de Partidas Rankeadas
Objetivo: Crie uma função que receba como parâmetro a quantidade de vitórias e derrotas de um jogador, depois disso retorne o resultado para uma variável, o saldo de Rankeadas deve ser feito através do cálculo (vitórias - derrotas).

Se vitórias menor do que 10 = Ferro, Se vitórias entre 11 e 20 = Bronze, Se vitórias entre 21 e 50 = Prata, Se vitórias entre 51 e 80 = Ouro, Se vitórias entre 81 e 90 = Diamante, Se vitórias entre 91 e 100 = Lendário, Se vitórias maior ou igual a 101 = Imortal.

Ao final deverá ser exibida uma mensagem: "O Herói tem de saldo de {saldoVitorias} está no nível de {nível}."

Conhecimentos aplicados no jogo
Declaração de Função (function): O código define uma função chamada calcularNivelRankeada, que aceita dois parâmetros: vitórias e derrotas. Declaração de Variáveis ​​​​(const e let): Utiliza a palavra-chave const para declarar a constante saldoVitorias e let para declarar a variável nível. Operadores Aritméticos (-): Calcula o saldo de vitórias subtraindo o número de derrotas do número de vitórias (const saldoVitorias = vitórias - derrotas;). Estrutura de Controle (if-else, if-else): Utiliza uma estrutura condicional para determinar o nível do herói com base no número de vitórias. Cada bloco if** ou else if contém condições que comparam o número de vitórias com disciplinas específicas. Literais de Modelo : Utiliza templates literários (delimitados por crases) para criar uma string que inclua o saldo de vitórias e o nível do herói. Exemplo : O Herói tem um saldo de ${saldoVitorias} e está no nível: ${nivel}. Chamada de Função (calcularNivelRankeada(150, 5): Chama a função calcularNivelRankeada com os valores 150 e 5 como argumentos para vencer derrotas, respectivamente. Saída no Console (console.log): Imprime no console uma string resultante que inclui o saldo de vitórias e o nível do herói. Conceitos Lógicos (&&, <, >=): Usa operadores lógicos ( &&, <, >=).


3️⃣ Escrevendo as classes de um Jogo
O que deve ser utilizado:
Variáveis, Operadores, Laços de repetição ,Estruturas de decisões, Funções, Classes e Objetos

Objetivo: Crie uma classe genérica que represente um herói de uma aventura e que possua as seguintes propriedades:
nome
idade
tipo (ex: guerreiro, mago, monge, ninja)

Além disso, deve ter um método chamado atacar que deve atender aos seguintes requisitos:
exibir a mensagem: "o {tipo} atacou usando {ataque}")
onde o {tipo} deve ser concatenado com o tipo que está na propriedade da classe
e no {ataque} deve seguir uma descrição diferente conforme o tipo, seguindo a tabela abaixo:
Se mago -> no ataque exibir (usou magia), Se guerreiro -> no ataque exibir (usou espada), Se monge -> no ataque exibir (usou artes marciais), Se ninja -> no ataque exibir (usou shuriken).

Saída
Ao final deve-se exibir uma mensagem: - "o {tipo} atacou usando {ataque}" Ex: mago atacou usando magia, guerreiro atacou usando espada.
