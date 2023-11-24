# Biblioteca de livros utilizando MongoDB

Projeto Spring Boot que utiliza MongoDB para gerenciar informações sobre livros em uma biblioteca.

## Como Executar

Execute a classe principal `BibliotecaMongoApplication` para iniciar a aplicação Spring Boot. Acesse `http://localhost:8080` para interagir com a API.

## Endpoints da API

- **GET /livros**: Obter todos os livros.
- **GET /livros/autor/{autor}**: Obter livros por autor.
- **GET /livros/genero/{genero}**: Obter livros por gênero.
- **POST /livros**: Adicionar um novo livro.


  - Exemplo do corpo da requisição via Json:
    ```json
    {
      "titulo": "O guia do mochileiro das galáxias",
      "autor": "Dougla Adams",
      "anoPublicacao": 2007,
      "genero": "Aventura e Ficção Científica"
    }
    ```
- **DELETE /livros/{id}**: Remover um livro por ID.
