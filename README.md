# 📝 Projeto Cadastro de Usuários

O **Projeto Cadastro de Usuários** é uma aplicação **Full Stack** desenvolvida com foco em **boas práticas de arquitetura, organização de código e separação de responsabilidades** entre **Frontend, Backend, Banco de Dados e Infraestrutura**.

O projeto foi estruturado para ser **escalável, modular e preparado para produção**, sendo ideal para **estudos avançados**, **demonstração técnica** e **portfólio profissional**.

---

## 🚀 Funcionalidades

- 👤 Cadastro de usuários
- 📄 Listagem de usuários
- ✏️ Atualização de dados
- 🗑️ Remoção de registros
- 🌐 Comunicação via API REST
- 🧩 Estrutura modular
- 📦 Build otimizado
- 🐳 Ambiente containerizado com Docker
- ⚡ Pronto para deploy

---

## 🧰 Stacks e Tecnologias Utilizadas

### 🎨 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

- Interface responsiva
- Estilização utilitária com Tailwind CSS
- Componentes visuais com Bootstrap
- Manipulação de DOM e eventos com jQuery
- Consumo de API REST

---

### 📦 Build & Bundler
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)

- Empacotamento de arquivos
- Otimização de assets
- Build para produção

---

### 🌐 Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge)

- API RESTful
- Arquitetura em camadas
- Tipagem estática com TypeScript
- Organização de rotas e controllers

---

### 🗄️ Banco de Dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

- Banco de dados relacional
- Persistência de dados
- Estrutura preparada para evolução

---

### ⚙️ Infraestrutura & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-0db7ed?style=for-the-badge)

- Containerização da aplicação
- Orquestração de múltiplos serviços
- Padronização de ambiente
- Separação entre ambientes (dev / prod)
- Base preparada para CI/CD

---

## 📂 Estrutura do Projeto
```
projeto-cadastro/
│
├── backend/
│ ├── src/
│ │ ├── controllers/
│ │ ├── routes/
│ │ ├── services/
│ │ └── app.ts
│ ├── Dockerfile
│ └── package.json
│
├── frontend/
│ ├── src/
│ │ ├── js/
│ │ ├── styles/
│ │ └── templates/
│ ├── build/
│ │ ├── bundle.js
│ │ └── index.html
│ ├── webpack.config.js
│ └── package.json
│
├── docker-compose.yml
├── .gitignore
└── README.md
```
---

## ▶️ Como Executar o Projeto

### 🐳 Executar com Docker
```
docker-compose up --build
```
💻 Executar Manualmente

Backend
```
cd backend
npm install
npm run dev
```
Frontend
```
cd frontend
npm install
npm run build
```

Abra no navegador:

```
frontend/build/index.html
```
🎯 Objetivo do Projeto

- Demonstrar domínio Full Stack

- Aplicar arquitetura organizada e escalável

- Trabalhar com API REST

- Utilizar Tailwind CSS, Bootstrap e Webpack

- Utilizar Docker e Docker Compose

- Criar um projeto sólido para portfólio profissional

- 🔮 Evoluções Futuras
- 🔐 Autenticação e autorização (JWT)

- 🔎 Busca e filtros avançados

- 📊 Paginação

- ⚛️ Migração para React ou Vue

- 🚀 Pipeline CI/CD

👨‍💻 Autor
Desenvolvido por Diego Hugo

⭐ Se este projeto te ajudou ou inspirou, deixe uma estrela no repositório!
