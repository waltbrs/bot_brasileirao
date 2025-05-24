# bot de analise brasileirao seria

faça um bot que envie mensagem às 6h00 no telegram de analíse estátisca nos dias em que ocorre jogos do brasileirão serie.

### linguagens de programacao
- python

### ferramentas
- flashscore 
- data football

#### flashscore

o programa fara um scrapping no site do flashscore nesse url (https://www.flashscore.com.br/futebol/brasil/brasileirao-betano/#/Yi0LvPEj/table/overall);
ele deverá identificar as datas, se a data selecionada coincidir com a data da variável data_hoje, armazena o nome das duas equipes e o horário da partida.

Cria uma função que faz e busca e o download da planilha  excel do brasileirao, nome do arquivo brazil.xlsx .

Já tendo disponível o nome das equipes que irão se confrontar, faz uma busca no arquivo brazil.xlsx dos últimos dos 10 confrontos entre as duas equipes.

Sugestão da mensagem:

Nos últimos 10 confrontos entre equipe_mandante vs equipe_visitante, houveram n_empate empates entre as duas equipes, n_vitoria_mandante vitoria do equipe_mandante e n_vitoria_visitante vitória da equipe visitante.

mostrar histórico do confronto:

- data_confronto equipe_mandante gol_mandante x gol_visitante equipe_visitante
- data_confronto equipe_mandante gol_mandante x gol_visitante equipe_visitante
- data_confronto equipe_mandante gol_mandante x gol_visitante equipe_visitante
- data_confronto equipe_mandante gol_mandante x gol_visitante equioe_visitante
- ...
- ...
- ...




