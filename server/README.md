<p align="center"> 
  <h1 align="center">API de Sistema de Referral <span>Desenvolvido com 💜</span></h1>
  
  <p align="center">
    Uma API robusta para gerenciamento de sistema de indicações com ranking em tempo real
  </p>

  <!-- Adicione screenshots do projeto aqui quando disponível -->
  
  <h1 align="center">Sobre</h1>
  
  Este projeto é uma API REST desenvolvida para gerenciar um sistema de referral/indicações com ranking em tempo real. Utilizando PostgreSQL para armazenamento persistente e Redis para gerenciamento de rankings e contadores, a API oferece uma solução escalável e performática para sistemas de indicação.

Principais funcionalidades:
- Sistema de convites por link
- Ranking em tempo real dos usuários que mais indicaram
- Contagem de cliques em links de indicação
- Documentação automática com Swagger
- Sistema de cache com Redis
- Persistência com PostgreSQL

## 💡 Tecnologias Utilizadas

- [x] [Node.js](https://nodejs.org/)
- [x] [Fastify](https://www.fastify.io/)
- [x] [TypeScript](https://www.typescriptlang.org/)
- [x] [PostgreSQL](https://www.postgresql.org/)
- [x] [Redis](https://redis.io/)
- [x] [Drizzle ORM](https://orm.drizzle.team/)
- [x] [Zod](https://zod.dev/)
- [x] [Docker](https://www.docker.com/)

## 🚀 Como Executar

### Pré-requisitos

- Docker e Docker Compose
- Node.js 18+
- NPM ou Yarn

### Configuração do Ambiente

1. Clone o repositório:

```bash
git clone https://github.com/Andreoew/connect.git
cd connect
cd server

```

2. Instale as dependências:

```bash
npm install
```

3. Configure o ambiente server:

```bash
cp .env.example .env
```

4. Inicie o projeto:

```bash
npm run dev
```

## 📚 Documentação

A documentação automática está disponível no Swagger:

```bash
  http://localhost:3333/docs#/
``` 

## 📦 Estrutura do Projeto

```bash

  server/
    src/
      drizzle/
      functions/
      redis/
      routes/
      env.ts/
      server.ts/
```

## ✒ Author

<p align="center">
  <img width="200px" style="border-radius: 50%" alt="Author André de Souza" title="Author André de Souza" src="https://github.com/andreoew.png" />

  <h3 align="center">André de Souza</h3>
  
  <p align="center">  
    Done with love and faith not to give up 😅, get in touch!
  </p>
</p>  
  
<div align="center">

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-1f6feb?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vagnernervessantos/)](https://www.linkedin.com/in/andredessilva/)
[![Gmail Badge](https://img.shields.io/badge/-seutecdev@gmail.com-1f6feb?style=flat-square&logo=Gmail&logoColor=white&link=mailto:seutecdev@gmail.com)](mailto:seutecdev@gmail.com)
[![GitHub Badge](https://img.shields.io/badge/-GitHub-1f6feb?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/VagnerNerves)](https://github.com/andreoew)

</div>
