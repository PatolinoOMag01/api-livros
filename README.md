# 📚 API de Livros

API desenvolvida para realizar o gerenciamento de livros, permitindo
cadastrar, consultar, atualizar e excluir informações de livros.

## 🎯 Objetivo

O objetivo desta API é praticar o desenvolvimento de uma aplicação
backend utilizando operações de **CRUD**.

CRUD significa:

-   **Create** --- cadastrar um novo livro
-   **Read** --- consultar os livros cadastrados
-   **Update** --- atualizar informações de um livro
-   **Delete** --- excluir um livro

## 🛠️ Tecnologias utilizadas

-   API REST
-   JSON
-   Banco de dados
-   Git e GitHub

> As tecnologias específicas utilizadas no projeto podem ser adicionadas
> aqui, como Python, FastAPI, Node.js, Express, MySQL, SQLite, entre
> outras.

## 📖 Estrutura de um livro

Cada livro pode possuir informações como:

``` json
{
  "id": 1,
  "titulo": "Dom Casmurro",
  "autor": "Machado de Assis",
  "ano_publicacao": 1899,
  "genero": "Romance"
}
```

## 🚀 Endpoints

  Método   Endpoint         Descrição
  -------- ---------------- ------------------------
  GET      `/livros`        Lista todos os livros
  GET      `/livros/{id}`   Busca um livro pelo ID
  POST     `/livros`        Cadastra um novo livro
  PUT      `/livros/{id}`   Atualiza um livro
  DELETE   `/livros/{id}`   Exclui um livro

## ➕ Cadastrar um livro

### Requisição

`POST /livros`

``` json
{
  "titulo": "O Pequeno Príncipe",
  "autor": "Antoine de Saint-Exupéry",
  "ano_publicacao": 1943,
  "genero": "Fábula"
}
```

### Exemplo de resposta

``` json
{
  "id": 2,
  "titulo": "O Pequeno Príncipe",
  "autor": "Antoine de Saint-Exupéry",
  "ano_publicacao": 1943,
  "genero": "Fábula"
}
```

## 🔎 Listar livros

`GET /livros`

Retorna todos os livros cadastrados na API.

## ✏️ Atualizar um livro

`PUT /livros/{id}`

Permite modificar as informações de um livro já cadastrado.

## 🗑️ Excluir um livro

`DELETE /livros/{id}`

Remove o livro correspondente ao ID informado.

## ▶️ Como executar

1.  Clone o repositório:

``` bash
git clone URL_DO_REPOSITORIO
```

2.  Entre na pasta do projeto:

``` bash
cd nome-do-projeto
```

3.  Instale as dependências necessárias.

4.  Execute a aplicação.

5.  Utilize ferramentas como **Postman**, **Insomnia** ou a documentação
    automática da API para testar os endpoints.

## 👨‍💻 Autor

Projeto desenvolvido para fins de estudo e prática de desenvolvimento de
APIs.
