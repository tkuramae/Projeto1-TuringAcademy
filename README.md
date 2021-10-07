# Análise e limpeza de dados - Atletas Olímpicos

Neste primeiro exercício de aplicação dos conhecimentos adquiridos até então através das aulas do Turing Academy e dos cursos realizados no DataCamp, fomos instruídos a realizar uma análise de dados exploratória com foco na limpeza de dados, buscando possíveis relações entre as estatísticas dos atletas e da aquisição de medalhas.

Das bibliotecas utilizadas:
- Pandas
- Numpy
- Matplotlib
- Seaborn

As conclusões da EDA estão descritas ao final do notebook. É interessante perceber como o dataset utilizado dá espaço para aplicações de conceitos de aprendizado de máquina como o algoritmo de KNN para classificação dos atletas em suas modalidades.

---------------------------------------------------------------------

Enunciado do problema proposto:

Em 2021, aconteceu mais uma edição das Olimpíadas. Esse evento ocorre normalmente uma vez a cada quatro anos e reúne grandes atletas de diferentes países para competirem entre si em diversas modalidades. Aproveitando a grande mídia cobrindo os jogos da edição deste ano, o Comitê Olímpico Internacional (IOC) decidiu fazer um estudo em cima de todos os dados que eles possuíam de edições passadas a fim de obter insights interessantes para divulgarem. Mais especificamente, o comitê busca através dessa análise encontrar possíveis padrões entre os ganhadores de medalhas que já participaram das edições dos jogos. Para isso, sabendo da sua grande reputação como um grande cientista de dados, eles requisitaram você para executar essa tarefa. Sua missão é limpar e organizar os dados que eles te enviaram e analisá-los, anotando e descrevendo cada um dos seus passos e descobertas e, ao final, elaborar uma conclusão a respeito delas. Para isso, utilize os conhecimentos adquiridos nas aulas a respeito das bibliotecas de manipulação e análise de dados.

---------------------------------------------------------------------

Sobre o dataset* disponibilizado:
*O dataset utilizado está disponibilizado também neste repositório - junto ao código - em .csv

Estrutura geral:

1. ID - Um número de identificação único de cada atleta
2. Name - Nome do atleta
3. Sex - Gênero do atleta: M (masculino) ou F (feminino)
4. Age - Idade
5. Height - Altura em centímetros
6. Weight - Peso em kg
7. Team - Nome do time ao qual o atleta pertence
8. NOC - Nome do comitê olímpico nacional ao qual o atleta pertence, sempre será um código de 3 letras (BRA para Brasil, USA para Estados Unidos, etc.)
9. Games - Ano e época dos jogos
10. Year - Ano da edição que o atleta participou
11. Season - Estação na qual ocorreu os jogos Summer (verão) ou Winter (inverno)
12. City - Cidade onde ocorreu a edição dos jogos
13. Sport - Esporte do atleta
14. Event - Especificação a respeito da categoria do esporte (Ex. Futebol masculino, vôlei feminino, corrida 500m, etc.)
15. Medal - Medalha ganha pelo atleta: Gold (ouro), Silver (prata), Bronze, ou NA (nenhuma medalha)
