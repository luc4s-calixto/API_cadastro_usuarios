# 🧑‍💻 Projeto Cadastro de Usuários (Fullstack)

Projeto Fullstack desenvolvido com base nos vídeos do canal **DevClub**, com foco em ensinar do zero como criar uma API REST com Node.js e conectar com o frontend feito em React.

---
📋 Sumário

- [Estrutura do Projeto](#estrutura-do-projeto)
- [Como executar o projeto](#como-executar-o-projeto)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Funcionalidades](#funcionalidades)
- [Autor](#autor)

  ***

## Estrutura do Projeto

  ```
  API_CADASTRO_USUARIOS/
  ├── back/                      # Backend (Node.js + Express + MongoDB + Prisma)
  │   ├── prisma/                # Configuração do Prisma com MongoDB
  │   ├── generated/             # Prisma Client
  │   ├── server.js              # Servidor Express
  │   ├── .env                   # Variáveis de ambiente
  │   └── package.json           # Dependências do backend
  │
  ├── cadastro-usuarios/         # Frontend (React + Vite)
  │   ├── src/
  │   │   ├── pages/             # Páginas da aplicação
  │   │   ├── services/          # Conexão com a API
  │   │   └── main.jsx           # Arquivo principal do React
  │   ├── index.html
  │   └── package.json           # Dependências do frontend
  │
  └── README.md                  # Documentação
  ```

  ***

## Como executar o projeto

  ### ⚙️ Pré-requisitos

  - Node.js (v18+ recomendado)
  - MongoDB Atlas ou local
  - NPM

  ***

  ### ▶ Backend (API)

  ```
  cd back
  npm install
  npx prisma generate
  npx prisma db push
  npm start
  ```

  ***

  ### Frontend

  ```
  cd front
  npm install
  npm run dev
  ```

  🛠️ Arquivo .env:

  ```
  DATABASE_URL="mongodb+srv://<usuario>:<senha>@<cluster>.mongodb.net/<nomeDoBanco>?retryWrites=true&w=majority"
  ```

## Tecnologias utilizadas


  🔙 Backend

  - Node.js
  - Express
  - MongoDB
  - Prisma ORM
  - CORS

  🔜 Frontend

  - React
  - Vite
  - JavaScript
  - React Hooks (useState, useRef)
  - CSS

  ***

## Funcionalidades

  - Criar usuários
  - Listar usuários
  - Editar usuários
  - Deletar usuários
  - Integração entre front e back com API REST

  ***

## Autor
  Projeto desenvolvido por Lucas Calixto, com base no conteúdo do DevClub.
