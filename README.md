# PAA (Projetgo de Analise de Algoritmos)

## Objetivo
Esse repositorio tem como objetivo o estudo de algoritmos e estruturas de dados usando como base o livro do professor e pesquisador Nivio Ziviani, tendo em vista não so a replica de exemplos trazendo minha leitura sobre, mas também as soluções de alguns exercícios em conjunto com outros exercícios de maratona, onde farei paralelos em relação a leitura. Quero contribuir com:

- Aprendizado das principais estruturas de dados e algoritmos existentes.
- Reflexão sobre o que eu aprendi e uma visão minha sobre o tema.
- Uma revisão/aproundamento naquilo que eu já estudei.
- Aprender e mapear as utilidades de cada algoritmos e estrutura de dado.

## Linguagem 
Utilizarei o C++ devido a sua verbosidade para aprender e sua definição mais precisa do que estou manipulando/criando vou utilizar os seguintes parametros no g++:
- -O3: Onde ela faz as seguintes otimizações:
  - Inlining agressivo: Remove as chamadas de funções sempre que possivel pelo proprio codigo da faunção, evitando a necessidade "pular" para função e voltar.
  - Vetorização Automática: Faz os loops sequenciais normais processarem multiplos dados simultaneamente(SIMD- Single Instruction, Multiple Data).
  - Desenrolamento de laços(Loop Unrolling): Faz a duplicação de dados internos do loops com a finalidade de reduzir a quantidade de vezes que o programa precisa verificar a condição de parada.
  - Reorganização de memória e cache: Melhora a forma como os dados são alocados e lidos, tentando prever o uso para que a CPU gaste menos tempo esperando dados da memória RAM.
- -std=c++20: Essa flag definie qual versão do c++ vou ultilizar, no caso a vesão 20
- -Wall -Wextra: Traz todas as informações relevantes como bugs antes memso de executar.

A motivação por isso é graças as maratonas e problemas de DSA, e a utilização de C++ se torna um fator obrigatorio por ser sempre o mais otimizado e trazendo questão e visão de que se eu aprendo no mais complexo espero tornar mais simples minha experiência  em linguagens menos complexas.

## Metodologia
A metodologia a principio sera a leitura do livro e replicação de exemplos a fim de entender e argumentar seguido de problemas em plataformas de DSA(Beecrowd, LeetCode, Codeforce, etc ...), se sentir falta de conteudo trazer ao repoisitorio.

## Funcionamento 

