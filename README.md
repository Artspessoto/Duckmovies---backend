# Backend Duckmovies 🦆

## Documentação completa
* 📖 Documentação da API [Duckmovies](https://sleepy-lion-12c.notion.site/DuckMovies-508dedb0c2be4076be7a69d7386d76dc)

## Typescript

### 1. Install typescript

```bash
npm i --dev typescript
```

run `tsc --init` to create a `tsconfig.json` file

## Tecnologias utilizadas:

**Linguagens de programação e frameworks:**
* Node.js
* Express.js
* TypeScript

**Autenticação e autorização:**
* JSON Web Token (JWT)

**Validação de dados:**
* Zod

**Teste unitário:**
* Supertest

**Teste de integração:**
* Vitest

**Banco de dados:**
* Knex.js
* SQLite

**Segurança:**
* bcrypt

**Gerenciamento de erros assíncronos:**
* express-async-errors

## Como rodar o projeto
### 1. **Criar o arquivo `prod.env`**

O arquivo `prod.env` contém uma variável de ambiente essencial para o funcionamento da aplicação em produção. Como esse arquivo contém informações confidenciais, ele não está presente no repositório Git.

**Siga essas etapas para criar o arquivo `prod.env` em seu ambiente local:**
* Crie um arquivo chamado `prod.env` no diretório raiz do projeto.
* Adicione a seguinte variável de ambiente ao arquivo, substituindo `SEU_JWT_SECRETO` por uma string exclusiva e segura:
  <br>
```bash
JWT_SECRET = SEU_JWT_SECRETO
```
### 2. **Instale as dependências com NPM:**
```
npm install
```

### 3. **Inicie o servidor com:**
```
npm run dev
```

4. **Gerenciar tabelas do banco de dados com Knex:**
O Knex.js é utilizado para gerenciar as migrações de banco de dados neste projeto. As migrações garantem que o banco de dados esteja atualizado com as tabelas e campos mais recentes.

```
npm run migrate
```


