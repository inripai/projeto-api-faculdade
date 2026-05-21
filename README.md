# API de Jogos

Esta é uma API RESTful simples desenvolvida para gerenciar uma biblioteca de jogos. Ela permite listar os jogos salvos, adicionar novos títulos e consultar informações detalhadas de um jogo específico através do seu ID.

## Link da Documentação

A documentação interativa da API está disponível no GitHub Pages:
[INSERIR SEU LINK DO GITHUB PAGES AQUI]

## Endpoints Disponíveis

- **`GET /jogos`**: Retorna a lista com todos os jogos cadastrados na biblioteca.
- **`POST /jogos`**: Recebe um payload (nome e gênero) para adicionar um novo jogo.
- **`GET /jogos/{id}`**: Retorna os detalhes de um único jogo com base no ID fornecido na URL.
