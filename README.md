
<h1 align="center">
  <img alt="Fastfeet" title="Fastfeet" src="../master/.github/logo.png" width="300px" />
</h1>

<h2 align="center">
  Fastfeet - Final Challenge for RocketSeat GoStack Bootcamp 10.0
</h2>

This full stack application project was developed at [RocketSeat GoStack Bootcamp](https://rocketseat.com.br/bootcamp) using ReactJS, NodeJS and React Native.

## :rocket: Features
- **[Express](https://expressjs.com/en/starter/installing.html)** — JavaScript back-end Framework
- **[Axios](https://github.com/axios/axios)** — API requests
- **[JWT](https://github.com/auth0/node-jsonwebtoken)** - JSON Web Token for authentication
- **[bcryptjs](https://github.com/dcodeIO/bcrypt.js)** - Encrypt password for authentication
- **[Redis](https://redis.io/documentation)** — For jobs
- **[Bee Queue](https://github.com/bee-queue/bee-queue)** — Task queue for jobs (uses Redis)
- **[Nodemailer](https://nodemailer.com/about/)** - E-mails
- **[Handlebar](https://handlebarsjs.com/)** - View template (used for e-mails)
- **[PostgreSQL](https://docs.mongodb.com/)** — DB for general data (except notifications and jobs)
- **[MongoDB](https://docs.mongodb.com/)** — DB used for notifications
- **[Sequelize](https://sequelize.org/)** - Used for manipulating SQL DB data
- **[Docker](https://www.docker.com/get-started)** — Containers for postgres and redis
- **[Multer](https://github.com/expressjs/multer)** - For file uploads
- **[youch](https://github.com/poppinss/youch)** - Error reporting
- **[Sentry](https://docs.sentry.io/)** - Error monitoring and reporting
- **[yup](https://github.com/jquense/yup)** - Value parsing and validation for requests
- **[date-fns](https://date-fns.org/)** - Date formatting

# Pre-requisites

- **Node** and **Yarn** installed;
- **Redis** and **PostgreSQL** instances running (Docker containers were used during development);
- **Android** emulator or device hooked up to your machine.

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
yarn android
```
