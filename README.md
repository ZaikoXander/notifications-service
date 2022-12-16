<p align="center">
  <img height="80" src="./documentation/ignite-lab.svg"/>
</p>

## Descrição

Uma aplicação de serviço de notificações construída no Ignite Lab 2022 de Node.js.

![Nestjs](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![PrismaORM](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![ApacheKafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)

## Instalação

```bash
# npm
$ npm install

# ou use yarn
$ yarn
```

## Inicializando a aplicação

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Testes

```bash
# unit tests
$ npm run test

# test coverage
$ npm run test:cov
```

## Testes da integração com Kafka

É preciso fazer um clone do [repositório](https://github.com/ZaikoXander/kafka-producer) abaixo:

```bash
# kafka producer
$ git clone https://github.com/ZaikoXander/kafka-producer.git
```

Ao abri-lo rode o script abaixo para testar a criação de notificações:

```bash
# npm
$ npm run produce

# ou use yarn
$ yarn produce
```

### Autor: ZaikoXander(Alex Daniel)
