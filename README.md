<h1 align="center">
    🚀 Ignite - NodeJS
</h1>
<p align="center">Desafio Database Queries</p>

<p align="center">
  <img src="https://img.shields.io/badge/node-14.15.4-green"/>
  <img src="https://img.shields.io/badge/score-10.00-important" />
  <img src="https://img.shields.io/badge/last%20commit-september-blue" />
  <img src="https://img.shields.io/badge/license-MIT-success"/>
</p>

<p align="center">
  <a href="#-features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-pré-requisitos">Pré-Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-rodando-o-back-end-servidor">Backend</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Lincença</a>
</p>

<h3 align="center"> 
🚧  Finalizado  🚧
</h3>

### 📎 Features

- [x] Listagem de usuários cadastrados em ordem alfabética
- [x] Listagem de usuários através do nome completo
- [x] Listagem de usuário por id
- [x] Pesquisa de jogos

### 🛢 Tipos de "queries" utilizadas
- Raw Query
- Query Builder
- ORM (Object Relational Mapper)

### 💻 Modelagem do Banco de Dados

<img src="https://github.com/gabriel-nt/ignite-nodejs-database-queries/blob/main/src/assets/diagram.png" />

### ⚙ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e/ou [Yarn](https://https://yarnpkg.com/) 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone https://github.com/gabriel-nt/ignite-nodejs-database-queries

# Criei um container do docker
$ docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

# Instale as dependências
$ npm install ou yarn

# Execute os testes
$ yarn test

```

### :rocket: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- NodeJS
- TS
- Express
- Jest

### :memo: Licença

Esse projeto está sob a licença MIT.

<hr/>

Feito por Gabriel Teixeira
