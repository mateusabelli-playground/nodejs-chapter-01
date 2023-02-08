# 👨‍💻 Desafios Ignite 2021 - Node.js

### 01 - Conceitos do Node.js

`branch challenge-01`

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no Node.js!

Essa será uma aplicação para gerenciar tarefas (em inglês _todos_). Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo _todo_;
- Listar todos os _todos_;
- Alterar o `title` e `deadline` de um _todo_ existente;
- Marcar um _todo_ como feito;
- Excluir um _todo_;

Tudo isso para cada usuário em específico (o `username` será passado pelo header).

### 02 - Trabalhando com middlewares

`branch challenge-02`

Nesse desafio você irá trabalhar mais a fundo com middlewares no Express. Dessa forma você será capaz de fixar mais ainda os conhecimentos obtidos até agora.

Para facilitar um pouco mais do conhecimento da regra de negócio, você irá trabalhar com a mesma aplicação do desafio anterior: uma aplicação para gerenciar tarefas (ou _todos_) mas com algumas mudanças.

Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo _todo_;
- Listar todos os _todos_;
- Alterar o `title` e `deadline` de um _todo_ existente;
- Marcar um _todo_ como feito;
- Excluir um _todo_;

Tudo isso para cada usuário em específico. Além disso, dessa vez teremos um plano grátis onde o usuário só pode criar até dez _todos_ e um plano Pro que irá permitir criar _todos_ ilimitados, isso tudo usando middlewares para fazer as validações necessárias.

### 03 - Corrigindo o código

`branch challenge-03`

Nesse desafio, temos uma aplicação Node.js que está em processo de desenvolvimento mas que já possui os testes necessários para fazer toda a validação dos requisitos (você não deve mexer nos testes).
Após algumas alterações no código da aplicação, parte dos testes deixaram de passar e agora só você pode resolver esse problema. Bora lá? 🚀

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate, **D**elete) de repositórios de projetos. Além disso, é possível dar likes em repositórios cadastrados, aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.

A estrutura de um repositório ao ser criado é a seguinte:

```javascript
{
  id: uuid(),
  title,
  url,
  techs,
  likes: 0
}
```
