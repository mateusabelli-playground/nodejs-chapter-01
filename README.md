# _Todos_ API ✔

Essa é uma aplicação **Node.js** de uma API que permite ao usuário que se cadastre e gerencie seus _todos_. As ações são feitas por meio de rotas de operações **CRUD** e cada usuário possuí uma lista de _todos_ própria. O aplicativo e o design foram criados pela @Rocketseat e entregues como um desafio de módulo no **Ignite Bootcamp** de Node.js

## 👨‍💻 Desafios

### 01 - Conceitos do Node.js

Será permitida a criação de um usuário com `name` e `username` bem como fazer o CRUD de *todos*:

- Criar um novo _todo_;
- Listar todos os _todos_;
- Alterar o `title` e `deadline` de um _todo_ existente;
- Marcar um _todo_ como feito;
- Excluir um _todo_;

Tudo isso para cada usuário em específico

### 02 - Trabalhando com middlewares

Os mesmos requisitos do desafio anterior porém dessa vez teremos um plano grátis onde o usuário só pode criar até dez todos e um plano Pro que irá permitir criar todos ilimitados, isso tudo usando middlewares para fazer as validações necessárias.

## 🌐 Rotas da API

### Usuários

| Método  | Endpoint        | Descrição                   |
| ------- | --------------- | --------------------------- |
| `GET`   | `/users:id`     | Encontrar um usuário por ID |
| `POST`  | `/users`        | Criar um novo usuário       |
| `PATCH` | `/users:id/pro` | Atualizar plano do usuário  |

### _Todos_

| Método   | Endpoint         | Descrição                        |
| -------- | ---------------- | -------------------------------- |
| `GET`    | `/todos`         | Encontrar _todos_ do usuário     |
| `POST`   | `/todos`         | Criar uma nova _todo_ do usuário |
| `PUT`    | `/todos:id`      | Atualizar uma _todo_             |
| `PATCH`  | `/todos:id/done` | Marcar uma _todo_ como concluída |
| `DELETE` | `/todos:id`      | Excluir uma _todo_               |

## 📦 Rodando o projeto

```bash
# Clone o repositório e instale as dependências
git clone https://github.com/mateusabelli/todos-api.git

cd todos-api

pnpm install
```

```bash
# Execute a aplicação (Porta :3333)
pnpm run dev

# Execute os testes unitários
pnpm run test
```
