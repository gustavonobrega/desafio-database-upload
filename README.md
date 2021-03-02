<h1 align="center">

<br>
GoFinances - API
</h1>

<p align="center">An API for transaction management.</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License MIT">
  </a>
</p>

<hr />

## Features

A Node.js API built with Express and all the latest tools and best practices in development!

-  **TypeScript** 
-  **Express** 
-  **TypeORM**
-  **Postgres**
-  **Multer**
-  **Jest**
-  **ESlint/Prettier/EditorConfig**

## Dependencies

- [Node.js](https://nodejs.org/en/) 8.0.0 ou >
- [Yarn](https://yarnpkg.com/pt-BR/docs/install)
- [Docker](https://www.docker.com/)

## Prerequisites

To run this server you will need three containers running on your machine.

To do so, you will need to run the following commands:

- `docker run --name database -e POSTGRES_PASSWORD=docker -p 5433:5432 -d postgres`;

_Remember: If you restart your machine, you will need to start again the server with `docker start <container_id>`._

## Getting started

_Consider checking out the FrontEnd [repository](https://github.com/gustavonobrega/gofinances-web)!_

1. Clone this repo using `https://github.com/gustavonobrega/gofinances-api.git`
2. Move to the appropriate directory: `cd gofinances-api`.<br />
3. Run `yarn` to install dependencies and `yarn typeorm migration:run ` to execute sequelize migrations.<br />
6. Run `yarn dev:server` to run the servers at `http://localhost:3333`.
