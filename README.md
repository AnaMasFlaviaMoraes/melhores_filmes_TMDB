## Desafio proposto

- Escolher uma API pública (https://any-api.com/, ou qualquer outra);
- Consumir essa API através do nodejs;
- Criar uma página html para fazer consultas pela API;
- Subir como uma aplicação no Okteto (https://cloud.okteto.com/). Dica: https://okteto.com/docs/samples/node/

## API Escolhida:

**The Movie Database (TMDB)**

O site do TMDB disponibiliza uma coleção de filmes para inúmeras formas de pesquisa (por nome do filme, ator, diretor, ano de lançamento, etc.)
Para acesso a API foi necessário a realização de um cadasto para emissão da Key, somente com essa Key que o site valida seu acesso e permite a utilização do seu banco de informações. Sendo assim, para proteger a minha chave pessoal salvei-a dentro de um arquivo .env


## Sobre a aplicação

Aplicação é uma simples página HTML para busca de filmes através do nome digitado no campo de pesquisa. Além disso, caso seja do interesse, o usuário poderá receber a lista dos filmes mais bem avaliados pelo site.

Como o desafio exigia o uso da Okteto, foi necessário o uso do Docker para criação da imagem do Node.JS no ambiente do Okteto,
