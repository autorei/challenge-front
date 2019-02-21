# Challenge  Front-End Developer (Architect focused) - Canal da Peça

Para avaliarmos melhor seu conhecimento e a forma como toma decisões técnicas, precisamos ter acesso ao seu código e apresentar alguns problemas próximos ao mundo real para saber como resolveria.

Esse desafio não tem a intenção de resolver nenhum problema interno do Canal da Peça e também não utilizará seu código como base para desenvolvimento de tecnologias internas.

Recomendamos fortemente que esse projeto seja open source para que outras pessoas possam consultar seu trabalho e também contribuir com o desenvolvimento de algo interessante.

# Objetivo

Utilizando dados mockados  ou alguma API pública (personagens, musicas, vídeos, produtos etc), criar uma aplicação:

- Que seja uma SPA (Single Page Application)
- Seja possível cadastrar um novo item (mesmo que não salve na API)
- Liste itens em formato de cards
- Sejam paginados com 10 cards por página
- Possua uma barra de busca para pesquisar os cards
- Cada card terá uma ação de "adicionar ao favorito", que fará com que aquele card fique em destaque para o usuário.

## Exemplos de API

Você pode consultar a API pública que quiser ou então utilizar um JSON mockado para desenvolver essa mini aplicação. Deixaremos abaixo recomendações:

### APIs

- Marvel API: [https://developer.marvel.com](https://developer.marvel.com/)
- Spotify WEB API: [https://developer.spotify.com/documentation/web-api](https://developer.spotify.com/documentation/web-api)
- Outras:  [https://github.com/toddmotto/public-apis](https://github.com/toddmotto/public-apis)

### Exemplo de listagem de carros mockado
```json
    [
      {
          "Name":"chevrolet chevelle malibu",
          "Miles_per_Gallon":18,
          "Cylinders":8,
          "Displacement":307,
          "Horsepower":130,
          "Weight_in_lbs":3504,
          "Acceleration":12,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"buick skylark 320",
          "Miles_per_Gallon":15,
          "Cylinders":8,
          "Displacement":350,
          "Horsepower":165,
          "Weight_in_lbs":3693,
          "Acceleration":11.5,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"plymouth satellite",
          "Miles_per_Gallon":18,
          "Cylinders":8,
          "Displacement":318,
          "Horsepower":150,
          "Weight_in_lbs":3436,
          "Acceleration":11,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"amc rebel sst",
          "Miles_per_Gallon":16,
          "Cylinders":8,
          "Displacement":304,
          "Horsepower":150,
          "Weight_in_lbs":3433,
          "Acceleration":12,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"ford torino",
          "Miles_per_Gallon":17,
          "Cylinders":8,
          "Displacement":302,
          "Horsepower":140,
          "Weight_in_lbs":3449,
          "Acceleration":10.5,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"ford galaxie 500",
          "Miles_per_Gallon":15,
          "Cylinders":8,
          "Displacement":429,
          "Horsepower":198,
          "Weight_in_lbs":4341,
          "Acceleration":10,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"chevrolet impala",
          "Miles_per_Gallon":14,
          "Cylinders":8,
          "Displacement":454,
          "Horsepower":220,
          "Weight_in_lbs":4354,
          "Acceleration":9,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"plymouth fury iii",
          "Miles_per_Gallon":14,
          "Cylinders":8,
          "Displacement":440,
          "Horsepower":215,
          "Weight_in_lbs":4312,
          "Acceleration":8.5,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"pontiac catalina",
          "Miles_per_Gallon":14,
          "Cylinders":8,
          "Displacement":455,
          "Horsepower":225,
          "Weight_in_lbs":4425,
          "Acceleration":10,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"amc ambassador dpl",
          "Miles_per_Gallon":15,
          "Cylinders":8,
          "Displacement":390,
          "Horsepower":190,
          "Weight_in_lbs":3850,
          "Acceleration":8.5,
          "Year":"1970-01-01",
          "Origin":"USA"
       },
       {
          "Name":"citroen ds-21 pallas",
          "Miles_per_Gallon":null,
          "Cylinders":4,
          "Displacement":133,
          "Horsepower":115,
          "Weight_in_lbs":3090,
          "Acceleration":17.5,
          "Year":"1970-01-01",
          "Origin":"Europe"
       }
    ]
```
Exemplo completo: [https://github.com/vega/vega/blob/master/docs/data/cars.json](https://github.com/vega/vega/blob/master/docs/data/cars.json)

# Ferramentas

Pode ser utilizado as tecnologias e ferramentas que quiser para o desafio - não queremos avaliar a tecnologia em si, mas suas decisões por trás da escolha de cada uma delas.

A única obrigação é que utilize algum sistema de versionamento para que possamos revisar os commits de forma cronológica.

# Prazos

Você terá **10 dias** para a realização do desafio.

# Notas

- Os dados do sistema podem ser mockados, não é necessário desenvolver o backend para o desafio
- Qualidade final é **essencial**. Desenvolva algo que iria para produção.
- Cumprindo o objetivo principal, você esta livre para criar e adicionar features que integrem bem a aplicação

# Dúvidas

Sinta-se a vontade pra entrar em contato em <dev@canaldapeca.com.br>.  
Por favor coloque o nome do teste como assunto do email.
