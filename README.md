# User Management API

API REST desenvolvida com Node.js, Express, Prisma ORM e MongoDB para gerenciamento de usuários.

## Tecnologias utilizadas

- Node.js
- Express
- Prisma
- MongoDB
- JavaScript

## Funcionalidades

- Criar usuário
- Listar usuários
- Atualizar usuário
- Deletar usuário
- Filtros via query params

## Rotas

| Método | Rota | Descrição |
|--------|------|-----------|
| POST | /usuarios | Criar novo usuário |
| GET | /usuarios | Listar usuários |
| PUT | /usuarios/:id | Atualizar usuário |
| DELETE | /usuarios/:id | Deletar usuário |

## Como executar o projeto

1. Clone o repositório:

git clone https://github.com/caiocruz1337/nodejs-user-api-prisma-mongodb

2. Instale as dependências:

npm install

3. Crie um arquivo .env com:

DATABASE_URL="sua_string_do_mongodb"

4. Gere o client do Prisma:

npx prisma generate

5. Inicie o servidor:

node server.js

Servidor rodando em:
http://localhost:3000
