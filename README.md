
# Project Mongodb Commerce

Pratica de todos os conceitos aprendido sobre o banco de dados não relacional Mongodb.

Nesse projeto, foi trabalhado com o banco de dados `commerce`, que contém dados do cardápio do McDonald's, como ingredientes, valores nutricionais e dados fictícios de vendas. As instruções de como restaurar o banco podem ser lidas a seguir.



## Stack utilizada

- Docker
- Mongodb


## Rodando com Docker

Clone o projeto

```bash
  git clone git@github.com:DavidJRRJ/Project-Mongodb-Commerce.git
```

Entre no diretório do projeto

```bash
  cd Project-Mongodb-Commerce
```

Crie um container com um volume apontado para a pasta do projeto

```bash
  docker run -d --name=nomeDoContainer -v "$PWD:/app" -p 27017:27017 mongo:5.0
```

Acesse o terminal do container com o comando

```bash
  docker exec -it nomeDoContainer bash
```

