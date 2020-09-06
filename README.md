<h1 align="center">
    GoFinances :money_with_wings:
    <br>
</h1>

<p align="center">

  <img alt="GitHub" src="https://img.shields.io/github/license/rafacdomin/gofinances.svg">
</p>

<p align="center">
  <a href="#about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-use">How To Use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#author">Author</a>
</p>

<p align="center">
  <a href="https://mygofinances.netlify.app" target="_blank"><img src="https://api.netlify.com/api/v1/badges/553c749d-5122-4b43-a8a8-c8e6a84310e5/deploy-status" alt="Run in Netlify"></a>
<a href="https://insomnia.rest/run/?label=GoFinances-api&uri=https%3A%2F%2Fraw.githubusercontent.com%2Frafacdomin%2Fgofinances-api%2Fmaster%2Fgofinances-insomnia.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

## About

NodeJS project developed on [RocketSeat GoStack 13.0](https://rocketseat.com.br/). This project is an API for a personal finance application, with register of incomes and outcomes by CSV files.

<p align='center'>
  <img src="https://raw.githubusercontent.com/rafacdomin/GoFinances/master/.github/gofinances.png" alt="GoFinances Homepage" width="700"/>
</p>

## Technologies

This project was developed with the following technologies:

API:

- [NodeJS](https://nodejs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com)
- [PostgreSQL](https://www.postgresql.org)
- [TypeORM](https://typeorm.io/)
- [cors](https://www.npmjs.com/package/cors)
- [csv-parse](https://www.npmjs.com/package/csv-parse)

WEB:

- [ReactJS](https://reactjs.org)
- [Typescript](https://www.typescriptlang.org/)
- [React Router](https://reactrouter.com)
- [styled-components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [filesize](https://www.npmjs.com/package/filesize)

## How To Use
You can access the site clicking this button:

<a href="https://mygofinances.netlify.app" target="_blank"><img src="https://api.netlify.com/api/v1/badges/553c749d-5122-4b43-a8a8-c8e6a84310e5/deploy-status" alt="Run in Netlify"></a>


To clone and run this application, you'll need installed on your computer:
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/)
- [Yarn v1](https://classic.yarnpkg.com/) 
- One instance of PostgreSQL

> Obs.: I recommend using `docker` to create and run the PostgreSQL instance.

To run the server:

```bash
# Clone the repository
$ git clone https://github.com/rafacdomin/gofinances-api

# Create the instance of postgreSQL using docker
$ docker run --name GoFinancesPG -e POSTGRES_USER=postgres \
              -e POSTGRES_DB=gofinances -e POSTGRES_PASSWORD=docker \
              -p 5432:5432 -d postgres

# Go into the repository folder
$ cd gofinances-api

```

Make a copy of .env.example to .env and set YOUR enviroment variables

```bash
# Install dependencies
$ yarn

# Run the server
$ yarn dev:server
```

To run the App Web:

```bash
# Clone the repository
$ git clone https://github.com/rafacdomin/gofinances-web

# Go into the repository folder
$ cd gofinances-web

# Install dependencies
$ yarn

# Run the app
$ yarn start
```

## License

This project is under the MIT license. See the [LICENSE](https://github.com/rafacdomin/gofinances/blob/master/LICENSE) for more information.

---

## Author

<img  border-radius="50px" src="https://avatars3.githubusercontent.com/u/40310160?s=460&u=d2babe9b7f1c365955699550074910a1957525c8&v=4" width="100px" alt="Author"/>

Made with :purple_heart: by Rafael Domingues :wave: [Get in touch!](https://www.linkedin.com/in/rafaelcodomingues/)

[![Linkedin Badge](https://img.shields.io/badge/-Rafael_Domingues-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaelcodomingues/)](https://www.linkedin.com/in/rafaelcodomingues/)
[![Gmail Badge](https://img.shields.io/badge/-rafaelcodomingues@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rafaelcodomingues@gmail.com)](mailto:rafaelcodomingues@gmail.com)
[![DEV.to Badge](https://img.shields.io/badge/DEV.to-rafacdomin-black)](https://dev.to/rafacdomin)
[![GitHub followers](https://img.shields.io/github/followers/rafacdomin?label=Follow&style=social)](https://github.com/rafacdomin/?tab=follow)
