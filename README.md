
<h1 align="center">
  <img alt="Fastfeet" title="Fastfeet" src="../master/.github/logo.png" width="300px" />
</h1>

<h2 align="center">
  Fastfeet - Final Challenge for RocketSeat GoStack Bootcamp 10.0
</h2>

## :rocket: Technologies

This full stack application project was developed at [RocketSeat GoStack Bootcamp](https://rocketseat.com.br/bootcamp) using ReactJS, NodeJS and React Native.

# Pre-requisites

- **Node** and **Yarn** installed;
- **Redis** and **PostgreSQL** instances running (Docker containers were used during development);
- **Android** emulator or device hooked up to your machine.

## ⚡️ Getting started

```
git clone https://github.com/edbrownc/fastfeet.git
```

# Backend

```
cd backend
yarn
yarn sequelize db:migrate
yarn sequelize db:seed:all
```
-  After the database has been populated, you may start the api:
```
yarn dev
```
- To start the redis queue, open a new terminal and use:
```
yarn queue
```

# Frontend
```
cd frontend
yarn
yarn start
```

# Mobile
```
cd mobile
yarn
yarn android
```
