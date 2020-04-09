<h1 align="center">
	<img alt="GoStack" src=".github/GoStackLogo.png" width="200px" />
</h1>

<h3 align="center">
  GoBarber ✂️
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/emersonefm/projetogobarber">
  
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/emersonefm/projetogobarber">
  
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/emersonefm/gobarber">
  
  <a href="https://github.com/EliasGcf/gobarber/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/emersonefm/projetogobarber">
  </a>
  
  <a href="https://github.com/EliasGcf/gobarber/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/emersonefm/projetogobarber">
  </a>
  
  <img alt="GitHub" src="https://img.shields.io/github/license/emersonefm/projetogobarber">
</p>

<p align="center">
  <a href="#-instalação-execução-e-desenvolvimento">Instalação, execução e desenvolvimento</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

## 💻 Instalação, execução e desenvolvimento

### Pré-requisitos

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [MongoDB](https://www.mongodb.com/)

**Faça um clone desse repositório**

### Backend

- A partir da raiz do projeto, entre na pasta do backend rodando `cd backend`;
- Rode `yarn` para instalar as dependências;
- Crie um banco de dados no `postgres` com o nome de `gobarber`;
- Rode `cp .env.example .env` e preencha o arquivo `.env` com **SUAS** variáveis ambiente;
- Rode `yarn sequelize db:migrate` para executar as migrations;
- Rode `yarn dev` para iniciar o servidor.
