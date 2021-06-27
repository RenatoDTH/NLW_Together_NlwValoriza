# NLW6_VALORIZA

Projeto realizado em nodeJS com Typescript, trazendo autenticação com jwt, apresentando um sistema de valorizamento a partir de tags e mensagens.Os ensinamentos foram trazidos pela [Rocketseat](https://rocketseat.com.br/)

## Introdução

É apresentado neste projeto a criação, listagem, criação e autenticação de usuários, tags, etc.salvando mensagens no banco de dados.
Foi utilizado o TypeORM para realizar as migrtions e o SQLite como banco de dados.

## Preparação

Ao baixar o projeto, é necessário rodar:

```
npm run
ou
yarn
```

Instalado as dependências, é necessário criar o banco de dados. O utlizado neste projeto foi o SQLite e a integração com o TypeORM pode ser encontrado no ormconfig.json na raiz da pasta backend.
Para criar o banco de dados e rodar as migrations já criadas, é necessário rodar:

```
npm run typeorm migration:run
ou
yarn typeorm migration:run
```

Isso vai fazer com que o banco seja criado e as tabelas também.
Para rodar o projeto no backend é só necessário rodar:

```
npm run dev
ou
yarn dev
```

Que ele irá rodar na porta 3333.

Você em seguida pode usar o Postman ou Insomnia para testar as requisições.
