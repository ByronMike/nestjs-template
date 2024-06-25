# NestJS Boilerplate

⚡ An open-source Boilerplate for NestJS developers who want to build a high-performance, maintainable, and enjoyable app: NestJS, TypeScript, ESLint, Prettier, Docker, PostgreSQL, Prisma, Jest, and Swagger.

## 🔥 Features

- [NestJS](https://nestjs.com) for building scalable server-side applications
- Type checking with [TypeScript](https://www.typescriptlang.org)
- Linter with [ESLint](https://eslint.org)
- Code Formatter with [Prettier](https://prettier.io)
- Containerization with [Docker](https://www.docker.com)
- Database management with [PostgreSQL](https://www.postgresql.org) and [Prisma](https://www.prisma.io)
- API Documentation with [Swagger](https://swagger.io)
- Testing with [Jest](https://jestjs.io)

## 👨🏻‍💻 Getting Started

### Prerequisites

- Node.js (>=20.x)
- npm or yarn
- Docker (optional, for containerized setup)

### Installation

1. Clone the repository:

   ```
   bash
   git clone https://github.com/ByronMike/nestjs-template.git
   cd nestjs-template
   ```

2. Install dependencies:

```
npm install
# or
yarn install
```

3. Running the database

```bash
docker compose up
```

4. Running the app

```bash
# development
$ npm run start

# watch mode (preferred)
$ npm run start:dev

# production mode
$ npm run start:prod
```

## 📘 Check the swagger

http://localhost:4000/api#/

## 🧪 Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## 🚀 Deploy to Production
You can build and start the app in production mode with:
```bash
npm run build
npm run start:prod
# or
yarn build
yarn start:prod
```

## 💖 Contributing
1. Fork this repository.
2. Create your branch: `git checkout -b my-remarkable-contribution`.
3. Commit your changes: `git commit -m 'feat: add my remarkable contribution'`.
4. Push to the branch: `git push origin my-remarkable-contribution`.

## 📝 License

Licensed under the MIT License, Copyright © 2024

See [LICENSE](LICENSE) for more information.

---

Made with :heart: by Michaël Auger <a href="https://www.linkedin.com/in/auger-michael/">My Contact</a>
