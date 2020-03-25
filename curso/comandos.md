## Install
```
$ npm install -s express
$ npm install -D nodemon
$ npm install -s knex
$ npm install sqlite3
$ npm install cors
```

## Knex
```
$ npx knex init
$ npx knex migrate:make create_ongs
$ npx knex migrate:latest # Executa o Medodo UP
$ npx knex migrate:make create_incidents
$ npx knex migrate:lastest
$ npx knex migrate:rollback # Executa o metodo DOWN
```