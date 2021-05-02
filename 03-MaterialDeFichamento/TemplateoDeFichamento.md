`No início deve incluir, o título do Artigo sobre o qual o fichamento está sendo feito, exemplo:`

# Incremental Strategy for Applying Mutation Operators Emphasizing Faults Difficult to be Detected by Automated Static Analyser

`Aqui deve-se colocar uma linha com a referência completa do artigo, exemplo:`

BARCELOS, Vinícius Silva; ANTONIO Cláudio Araujo; SÉRGIO Edmundo Spoto; MARCELO, Auri Rizzo Vincenzi. “Incremental Strategy for Applying Mutation Operators Emphasizing Faults Difficult to be Detected by Automated Static Analyser”, SBES’17, September 20–22, 2017, Fortaleza, CE, Brazil, 10 pages. DOI: [10.1145/3131151.3131169] (https://doi.org/10.1145/3131151.3131169)

## 1. Fichamento de Conteúdo

`Aqui deve-se incluir uma análise geral do artigo em um parágrafo de  8 a 15 linhas. É um texto corrido nas palavras da pessoa que está fazendo o fichamento (não deve ter cópia literal de conteúdo do artigo), pode conter opinião do leitor a partir do texto. Idealmente deve mencionar o contexto tratado pelo artigo, o problema que ele tenta resolver, o(s) método(s) que ele emprega e o(s) resultado(s) que obtém. O texto deve ser uma forma simples que resume o que se entendeu do artigo. Exemplo:`

Observa-se que o artigo se trata de técnicas e instrumentos que são essenciais no desenvolvimento de um software, para obter um produto com um baixo custo e com uma boa qualidade, logo destaca-se o uso de analisadores estáticos. Já uma técnica bastante conhecida e muito eficaz de testes de Defeitos é o Teste De Mutação, este tem como função verificar e eliminar defeitos do software, porém apresenta um custo mais alto. Sendo assim o artigo cita a importância da utilização de analisadores estáticos nesse processo de desenvolvimento de software, colocando-o como uma vantagem e realizando comparações com o Teste de Mutação. É importante ressaltar sobre o estudo de Araujo et al, este realizou experimentos com o uso do teste de mutação para avaliar a qualidade de analisadores estáticos automatizados, medindo a taxa de avisos que os analisadores emitiram como também os defeitos retratados pelos mutantes. Pode-se dizer que o objetivo deste artigo é determinar uma estratégia incremental de aplicação dos operadores de mutação em linguagem C, de acordo com as informações de análise estática. Foram realizados testes para dar continuidade ao estudo de Araujo, ou seja, uma avaliação das estratégias propostas utilizando conjuntos de casos de testes adequados ao teste de mutação. Foram utilizadas ferramentas como Splint (analisador estático) e a ferramenta Proteum/IM (mutação), usando 5 programas UNIX, buscando avaliar a qualidade da estratégia sugerida (emprego da estratégia STAT) com base nos conjuntos importantes, analisando o escore de mutação, o custo na questão de mutantes que foram gerados e o custo de mutantes equivalentes acarretados pelas estratégias. Contudo, com esses experimentos, os resultados demonstram que utilizar o STAT é uma vantagem, pois ela consegue verificar os defeitos mais complicados de serem detectados através da análise estática.

## 2. Fichamento Bibliográfico 

`Nesta parte, ideias e conceitos que aparecem no artigo devem ser organizados e descritos com as palavras do leitor, e, idealmente, devem ser indicadas as páginas onde aparecem no texto. Deve-se incluir de 3 a 6  itens. Exemplo:`

* _Umas das ferramentas muito importantes para detectar e eliminar defeitos em um software é o Teste de Mutação, este avalia a qualidade de critérios de teste (Página 1).
* _Ferramentas de análise estática podem ser usadas para ajudar a reconhecer defeitos e vulnerabilidades presentes em um software (Página 2).
* _A análise estática possui um custo menor, pois ela não requer a execução do código, além disso se baseia em regras e em representações abstratas (comportamento do código do produto)(Página 3).

## 3. Fichamento de Citações 

`Aqui devem ser adicionadas as frases mais importantes que aparecem no artigo. Deve ser uma transcrição exata de como estão escritas no artigo, devem ficar entre aspas. Esse fichamento é importante para que possa identificar facilmente como o autor do artigo descreveu um conceito, teoria, método, resultado etc. Deve-se incluir de 3 a 6  itens. Exemplo:`


* _“As atividades relacionadas à verificação e validação de software podem ser divididas em dois tipos: atividades de análise dinâmica e atividades de análise estática. ” _
* _“Por outro lado, as ferramentas de análise estática automatizadas podem ser empregadas para auxiliar no reconhecimento de certos tipos de defeitos e vulnerabilidades. ” _
* _“Uma técnica de teste bastante eficaz na detecção e eliminação dos defeitos presentes no software é o Teste de Mutação. Sendo considerado um excelente modelo de defeitos, o Teste de Mutação é, em geral, empregado para avaliar a qualidade de conjuntos de teste ou critérios de teste, tornando-o um muito utilizado em experimentação. ” _
* _“Um dos problemas do Teste de Mutação é o alto custo computacional devido ao grande número de mutantes gerados, que demandam tempo para a execução, e posterior análise de mutantes vivos para identificação de mutantes equivalentes. ” _
