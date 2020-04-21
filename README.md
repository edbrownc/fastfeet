
<h1 align="center">
  <img alt="Fastfeet" title="Fastfeet" src="../master/.github/logo.png" width="300px" />
</h1>

<h2 align="center">
  Fastfeet - Final Challenge for RocketSeat GoStack Bootcamp 10.0
</h2>

This full stack application project was developed at [RocketSeat GoStack Bootcamp](https://rocketseat.com.br/bootcamp) using ReactJS, NodeJS and React Native.

## :rocket: Features
# Backend
- **[Express](https://expressjs.com/en/starter/installing.html)** — JavaScript back-end Framework
- **[Axios](https://github.com/axios/axios)** — API requests
- **[JWT](https://github.com/auth0/node-jsonwebtoken)** - JSON Web Token for authentication
- **[bcryptjs](https://github.com/dcodeIO/bcrypt.js)** - Encrypt password for authentication
- **[Redis](https://redis.io/documentation)** — For jobs
- **[Bee Queue](https://github.com/bee-queue/bee-queue)** — Task queue for jobs (uses Redis)
- **[Nodemailer](https://nodemailer.com/about/)** - E-mails
- **[Handlebar](https://handlebarsjs.com/)** - View template (used for e-mails)
- **[PostgreSQL](https://docs.mongodb.com/)** — DB for general data (except notifications and jobs)
- **[Sequelize](https://sequelize.org/)** - Used for manipulating SQL DB data
- **[Docker](https://www.docker.com/get-started)** — Containers for postgres and redis
- **[Multer](https://github.com/expressjs/multer)** - For file uploads
- **[yup](https://github.com/jquense/yup)** - Value parsing and validation for requests
- **[date-fns](https://date-fns.org/)** - Date formatting

# Frontend
- **[React](https://reactjs.org/)** — A JavaScript library for building user interfaces
- **[Redux](https://redux.js.org/)** -State management (includes Saga and Persist)
- **[Immer](https://immerjs.github.io/immer/docs/introduction)** - Allows to work with immutable states using drafts 
- **[Axios](https://github.com/axios/axios)** — API requests
- **[yup](https://github.com/jquense/yup)** - Value parsing and validation for requests
- **[date-fns](https://date-fns.org/)** - Date formatting
- **[ESLint](https://eslint.org/)** - ESlint/Prettier/Editor Config using Airbnb style guide
- **[Reactotron](https://github.com/infinitered/reactotron)** - Application to inspect React applications

# Mobile
- **[React](https://reactjs.org/)** — A JavaScript library for building user interfaces
- **[Redux](https://redux.js.org/)** -State management (includes Saga and Persist)
- **[Axios](https://github.com/axios/axios)** — API requests
- **[date-fns](https://date-fns.org/)** - Date formatting
- **[ESLint](https://eslint.org/)** - ESlint/Prettier/Editor Config using Airbnb style guide
- **[Reactotron](https://github.com/infinitered/reactotron)** - Application to inspect React applications
- **[react-native-camera](https://github.com/react-native-community/react-native-camera)** - Use phone's camera

# Pre-requisites

- **Node** and **Yarn** installed;
- **Redis** and **PostgreSQL** instances running (Docker containers were used during development);
- **Android** emulator set up or device hooked up to your machine.

## ⚡️ Getting started

```
git clone https://github.com/edbrownc/fastfeet.git
cd fastfeet
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
yarn start
react-native run-android
```
