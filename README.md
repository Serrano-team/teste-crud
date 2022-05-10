# -- Teste --

# Backend
Desenvolver uma API JSON REST, que utilize os métodos (​GET​, ​POST​, ​PUT​, DELETE​).

# Frontend
Deverá ser SPA e consumir todos endpoints da API.

# Banco de dados
Monte uma base de usuários com a seguinte estrutura:

```
nome: varchar
sexo: char
datanascimento: date
idade: integer
```

# API endpoints

```
GET /users
Codes 200
```
Retorna todos os usuários.

```
GET /users?
Codes 200 / 404
```
Retorna os usuários de acordo com o termo passado via querystring e paginação.

```
GET /users/{id}
Codes 200 / 404
```
Retorna os dados de um usuário.

```
POST /users
Codes 201 / 400
```
Adiciona um novo usuário.

```
PUT /users/{id}
Codes 200 / 400
```
Atualiza os dados de um usuário.

```
DELETE /users/{id}
Codes 204 / 400
```
Apaga o registro de um usuário.


# Tecnologias necessárias
- PostgreSQL.
- VueJS.
- PHP.
- Docker.


# Entrega
- Desejável que aplicação e o banco rodem em docker.
- Enviar o link do projeto no github, com explicação no README.
