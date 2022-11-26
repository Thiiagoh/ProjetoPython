# Projeto Sobre Pesquisas Eleitorais do Brasil

A pesquisa foi feita atráves de uma analise de sentimento usando python e a rede social Twitter.

Para ser realizado a extração dos dados do twitter foram utilizados as seguintes api "python-twitter-vw" e "snscrape" e para realizar a analise de sentimento foi utilizado a api "textblob" e para conseguir recolher informaçoes sobre as eleições foi utilizado a api do "basedosdados" que usa informações do poder360.

Para rodar os scripts é necessario ter o python instalado e o power bi para poder ver os graficos.

Explicação sobre o script feito em python:

1° Primeiro bloco de comandos está realacionado á instalação das bibliotecas/api.
2° Segundo bloco de comandos está relacionado á importação dos comandos a serem utilizados
3° Terceiro bloco de comandos está relacionado á extração de dados do twitter, que funciona da seguinte maneira, primeiramente é definido a data de inicialização e a data final, logo em seguida o codigo vai entrar em loop, sendo assim definido pelo "for x in range(360):" naqual 360 representa o numero de dias, e o seguinte comando " if i>10:" naqual o 10 representa a quantidade de dados a serem recolhidos em determinado dia, apos passar pelo IF o codigo ira incrementar uma data tanto inicial quanto final para poder rodar até a quantia de dia informado, sendo assim ira recolher 10 twwites por dia durante 360 dias.
4° Quarto bloco 
