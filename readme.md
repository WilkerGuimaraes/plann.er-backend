# plann.er - Backend

## 📃 Descrição

Este projeto é um sistema backend desenvolvido com **JavaScript** uma aplicação de gestão de viagens.

## Requisitos

- [ ✔ ] O organizador pode cadastrar uma nova viagem informando local, data e hora;
- [ ✔ ] O organizador pode convidar pessoas através de um envio de e-mail;
- [ ✔ ] O organizador pode cadastrar uma nova atividade de acordo com o período da viagem;
- [ ✔ ] O organizador pode cadastrar links relacionados a viagem;
- [ ✔ ] Os convidados precisam confirmar por e-mail que irão na viagem;

## 🛠 Tecnologias

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Fastify](https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

## 🧰 Recursos

Este projeto aborda o uso de algumas ferramentas de desenvolvimento back-end utilizado em conjunto com o Node.js:

- `prisma`: o prisma é um ORM que foi utilizado para simplificar a interação com o banco de dados fornecendo uma interface amigável para consultas e manipulação de dados.
- `cors`(Cross-Origin Resource Sharing): é um mecanismo de segurança utilizado pelos navegadores para determinar se scripts de uma origem determinada têm permissão para acessar recursos de outra origem na web. Com isso o projeto Front-end conseguiu realizar as solicitações da API sem violar as políticas de segurança do navegador.
- `zod`: o zod é uma biblioteca TypeScript de validação de esquemas (schema validation) e tipagem de dados.
- `nodemailer`: é uma biblioteca para Node.js que permite enviar e-mails de forma fácil e eficiente.

## 💻 Executando

- Após clonar o repositório, é necessário possuir um arquivo `.env` para definir os valores de variáveis ambiente que serão usadas na aplicação.

  ![code](https://github.com/user-attachments/assets/804f5522-cb43-4a05-8a7b-425a07ea897c)

1. `DATABASE_URL: DATABASE_URL="file:./dev.db"`
   Esta variável define a URL de conexão ao banco de dados.

2. `API_BASE_URL: API_BASE_URL=""`
   Esta variável define a URL base para a API da sua aplicação.

3. `WEB_BASE_URL: WEB_BASE_URL=""`
   Esta variável define a URL base para a interface web da sua aplicação.

4. `PORT=`
   Esta variável define a porta na qual o servidor da sua aplicação estará escutando.

- Após definir os valors das variáveis de ambiente, acesse a pasta do projeto e execute o seguinte comando para instalar todas as dependências:

```

npm install

```

- E por fim, execute este script para executar a aplicação:

```

npm run dev

```

O servidor estará rodando na porta `3333` do seu navegador:`http://localhost:3333`

## 🙋‍♂️ Colaboradores

Este projeto foi desenvolvido por mim Wilker Guimarães, com o auxílio do evento NLW-Journey na trilha de Node com o objetivo de desenvolver meus conhecimentos em Node.js abordando os conceitos mais modernos de desenvolvimento back-end utilizando esta tecnologia.
