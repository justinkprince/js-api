# Dependencies

First things first, we must install our known depnedencies for the web API.

- Babel - compiling ES2015+ into backwards compatible JS
    - [@babel/core](https://babeljs.io/docs/en/babel-core) - Main library
    - [@babel/cli](https://babeljs.io/docs/en/babel-cli) - CLI API for Babel core
    - [@babel/preset-env](https://babeljs.io/docs/en/babel-preset-env) - smart presets for Babel
    - [@babel/node](https://babeljs.io/docs/en/babel-node.html) - Compile Babel presets before running in Node CLI
- [Express](https://expressjs.com/) - app framework
- [Sqlite3](https://www.npmjs.com/package/sqlite3) - DB for storing articles
- [UUID](https://www.npmjs.com/package/uuid) - generate unique IDs for articles
- [Faker.js](https://www.npmjs.com/package/faker) - generate see data
- Babel, ESLint, Prettier configs
- Add scripts commands for dev and prod
- Add docs
