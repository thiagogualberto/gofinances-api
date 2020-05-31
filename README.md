<h1 align="center">
    <p>GoFinances API</p>
</h1>

<h3 align="center">
    <!-- Descrição do projeto  -->
    Simple System to store financial transactions - REST API made with Node.js + Typescript
</h3>

</br>

<div align="center">

[![](https://img.shields.io/badge/made%20by-ThiagoGualberto-%237159C1)](https://www.linkedin.com/in/thiagogualberto84)
[![](https://img.shields.io/badge/node.js@lts-12.14.1-informational?logo=Node.JS)](https://github.com/nodejs/node/blob/master/doc/changelogs/CHANGELOG_V12.md#12.14.1)
![](https://img.shields.io/github/repo-size/thiagogualberto/gofinances-api.svg)
[![](https://img.shields.io/github/last-commit/thiagogualberto/gofinances-api.svg?color=red)](https://github.com/thiagogualberto/gofinances-api/commits/master)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/thiagogualberto/gofinances-api/blob/master/LICENSE.md)
</br></br>

<p id="insomniaButton" align="center">
    <a href="https://insomnia.rest/run/?label=FastFeet%20API&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fthiagogualberto%2Ffastfeet-api%2Fmaster%2FInsomnia_FastFeet.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

<p align="center">
  <a href="#man_technologist-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-getting-started">Getting Started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#clipboard-features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#thinking-contribution">Contribution</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#pushpin-support">Support</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licence">Licence</a>
</p>
</div>
</br>

# :man_technologist: Project

This project is a challenge of Rocketseat GoStack Bootcamp. It's a REST API built with NodeJS + Express + Typescript. This API is a simple system to store financial transactions.
</br></br>

# :rocket: Getting Started

## :gear: Back-end

To clone and run this api, you'll need Git, Node.js v12.14 or higher + Yarn v1.21 or higher + Docker installed on your computer. </br>
The first thing you need to do is to run these three containers on your machine:</br>

```bash
# Create a container in 'postgres' with the name of 'gostack_postgres'
$ docker run --name gostack_postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

From your command line:

```bash
# Clone this repo to your local machine using
$ git clone https://github.com/thiagogualberto/gofinances-api

# From the project root, enter the backend (gofinances-api) folder
$ cd gofinances-api

# Install the dependencies
$ yarn

# Create a database in 'postgres' with the name of 'gofinances'

# Run the migrations
$ yarn typeorm migration:run

# Everything ready to start the server
$ yarn dev:server
```

You can test this API in two ways:</br>
* Import the `Insomnia_FastFeet.json` file into Insomnia or,
* Click the button [Run in Insomnia](#insomniaButton)
</br></br>

# :clipboard: Features

## Funcionalities
* Transactions (Create, List and Delete)
* Create tags (Categories) when inserting new transactions.
* Import transactions (CSV file).


## Build with (Technologies)

This project was developed with the following technologies:
* [Bcrypt](https://www.npmjs.com/package/bcrypt) - Generation of User Password Hash
* [CSV Parser](https://www.npmjs.com/package/csv-parser) - Used to upload CSV files
* [Docker](https://www.docker.com/docker-community) - Container
* [DotEnv](https://www.npmjs.com/package/dotenv) - Loads environment variables
* [EditorConfig](https://editorconfig.org/) - Setting up the development environment
* [ESLint](https://eslint.org/) - JS Linter and code style
* [Express](https://expressjs.com/pt-br/) - Router of the Application
* [Jest](https://jestjs.io/) - JavaScript Testing Framework
* [Multer](https://github.com/expressjs/multer) - File Upload
* [Node.js](https://nodejs.org/en/) - Build the server
* [PostgreSQL](https://www.postgresql.org/) - Database
* [Prettier](https://prettier.io/) - Code Formatter
* [SuperTest](https://github.com/visionmedia/supertest) - Test
* [TypeORM](https://typeorm.io/#/) - ORM used with Node.js + TypeScript
* [TypeScript](https://www.typescriptlang.org/) - Build the server
* [VS Code](https://code.visualstudio.com/) with [Sucrase](https://github.com/alangpierce/sucrase) + [ESLint](https://eslint.org/) + [Prettier](https://prettier.io/) + [EditorConfig](https://editorconfig.org/) + [TypeORM](https://typeorm.io/#/)
</br></br>

# :thinking: Contribution

I'll be happy if you could provide me any feedback about the project, code, structure or anything that you can report that could make me a better developer!

```bash
#Fork this repo!
$ gh repo fork thiagogualberto/NOME_DO_REPO

#Clone this repo to your local machine using
$ git clone https://github.com/thiagogualberto/gofinances-api.git

# Create your feature branch using
$ git checkout -b my-feature

# Commit your changes using
$ git commit -m 'feat: My new feature'

# Push to the branch using
$ git push origin my-feature

# Create a new pull request

After your Pull Request is merged, can you delete your feature branch.
```

You can send how many PR's do you want, I'll be glad to analyse and accept them! And if you have any question about the project contact me by email or linkedin below and let's have a good chat.
</br></br>

# :pushpin: Support
My name is Thiago de Medeiros Gualberto and my contacts are:

* Email: <thiago.gou@gmail.com>
* Linkedin at [Thiago Gualberto](https://www.linkedin.com/in/thiagogualberto84/)

Connect with me at LinkedIn.

Thank you!
</br></br>

# :memo: Licence

[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/thiagogualberto/gofinances-api/blob/master/LICENSE.md)

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details
</br></br>

---
Made with ♥ Enjoy it!
