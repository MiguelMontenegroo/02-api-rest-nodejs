# 02-api-rest-nodejs

Requisitos funcionais:

- [x] O usuário deve poder criar uma nova transação.
- [x] O usuário deve poder obter um resumo da sua conta.
- [x] O usuário deve poder listar todas transações que ja ocorreram.
- [x] O usuário deve poder visualizar uma transação única.

Regras de negocio:

- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito que subtrairá.
- [] Deve ser possivel identificarmos o usuário entre as requisições.
- [] O usuário só pode visualizar transações o qual ele criou.

Requisitos não-funcionais:

-
02-api-rest-node: fastify(microframework?),tsx(converte o codigo typescript em javascript automatizado),eslint(padronizar o codigo),dotenv(gerenciar configurações de ambiente em aplicações),zod(configurar para validar e tratar as variáveis ambiente do projeto),insomnia(software popular utilizada para testar e interagir com APIs),vitest(testes),supertest(fazer requisições para a aplicação sem colocar no ar),tsup(deploy typescript converter pra javascript processo de build do projeto)
-------------------------------

Here’s the translation to English:

Functional Requirements:

 The user should be able to create a new transaction.
 The user should be able to get a summary of their account.
 The user should be able to list all transactions that have occurred.
 The user should be able to view a single transaction.
Business Rules:

 The transaction can be of the credit type, which will add to the total amount, or debit, which will subtract from it.
[] It should be possible to identify the user across requests.
[] The user can only view transactions that they have created.
Non-Functional Requirements:

02-api-rest-node:

Fastify (microframework?),
TSX (automatically converts TypeScript code to JavaScript),
ESLint (standardizes the code),
Dotenv (manages environment settings in applications),
Zod (set up to validate and handle the project's environment variables),
Insomnia (popular software used to test and interact with APIs),
Vitest (testing),
Supertest (makes requests to the application without deploying it),
Tsup (build process that converts TypeScript to JavaScript for deployment).