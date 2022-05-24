## Description

A test of NestJS to build a simple api to test features of the framework.

## How to use

Structure of User:
  {
    
    "_id": "jgak68g64jasd12iuy6",
    "name": "Just Testing",
    "email": "exampel@nestapi.test,
    "password": "00000",
  }

Routes: 

| Method | Route | Description |
|---|---|---|
| `GET` | /users/{id} | Return one or more users. |
| `POST` | /users | To create an user. |
| `PATCH` | /users/{id} | Update an existing user. |
| `DELETE` | /users/{id}  | Remove an user. |

## Installation

```bash
$ npm install
```

Rename the .env.example and set your MONGO_CONNECTION query on .env file.

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
