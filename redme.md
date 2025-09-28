# JAC (Jornada Acadêmica e Comunitária)

Plataforma para gestão de eventos acadêmicos e comunitários, com gamificação e sistema de reconhecimento de participação.

## Status do Projeto

📌 **28/09 – Primeira versão funcional**

* Cadastro de usuários
* Recomendação básica de eventos
* Integração inicial com banco de dados

## Estrutura do Projeto

### Backend

* Repositório: [jac-back-end-main](https://github.com/GBertonsin/jac-back-end)
* Stack: Node.js, Express, Sequelize, PostgreSQL
* Funcionalidades atuais:

  * Cadastro de usuário
  * CRUD inicial de eventos
  * Integração com banco de dados

### Frontend

* Repositório: [jac-front-end-main](https://github.com/GabrielGFC/JAC-FRONT-END)
* Stack: React (Vite + TypeScript)
* Funcionalidades atuais:

  * Tela de login/cadastro
  * Recomendação básica de eventos

## Como rodar localmente

### Pré-requisitos

* Node.js >= 18
* PostgreSQL rodando local ou via Docker

### Backend

```bash
git clone https://github.com/GBertonsin/jac-back-end.git
cd jac-back-end
npm install
npm run dev
```

### Frontend

```bash
git clone https://github.com/GabrielGFC/JAC-FRONT-END.git
cd jac-front-end
npm install
npm run dev
```

A aplicação ficará disponível em:

* **Backend**: [http://localhost:3000](http://localhost:3000)
* **Frontend**: [http://localhost:5173](http://localhost:5173)
