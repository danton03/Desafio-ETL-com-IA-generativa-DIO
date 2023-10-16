# Desafio DIO - Explorando IA Generativa em um Pipeline de ETL com Python


Neste desafio foi criado um ETL para geração de mensagens personalizadas de marketing bancário. Para isso, utilizou-se a API do Santander Dev Week para acessar os dados dos usuários e atualizar no banco de dados a coluna "news" de cada usuário acessado com uma mensagem personalizada sobre investimentos. 

Diferente das aulas de apoio, neste projeto optou-se por utilizar a API do PaLM AI, fornecido pelo google em um teste gratuito de 3 meses.



OBS.1: O correto funcionamento desse projeto depende da inserção da sua API KEY no local indicado na seção "Transformação" e do upload do arquivo CSV no google collab com o nome "SDW2023" conforme o seguinte exemplo:

```
UserID
1
2
3
4
5
```
OBS.2: Consulte no [Swagger](https://sdw-2023-prd.up.railway.app/swagger-ui/index.html) da API os IDs de usuário disponíveis.
