# nest

## Description

description

## Installation

```bash
$ npm install
```

## Running the app

Run db for dev:

```bash
docker run -p 3306:3306 -t -e MYSQL_ROOT_PASSWORD=my-secret-pw mysql
docker run -p 3306:3306 -t -e MYSQL_ROOT_PASSWORD=my-secret-pw mariadb
```
Start nest
```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
npm run start:prod
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
Goals:
[ ] User Model
[ ] ACL
[ ] Auth
