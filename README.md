# Typescript Express Typeorm Boilerplate

[![Build Status](https://travis-ci.com/v2xnetwork/typescript-express-typeorm-boilerplate.svg?branch=master)](https://travis-ci.com/v2xnetwork/typescript-express-typeorm-boilerplate)

### Requirements
- Node v8+
- npm v6+
- PostgreSQL

### Instructions
- Download the repo.
- Create 2 PostgreSQL databases. One for testing & other as main database
- Copy the `env.example` file from root of project and create a new `.env` file from it.
- Set the configuration parameters there (App port, app host, database host, port, username, password etc)
- Install the dependencies by running `npm install`
- Start the project by running `npm start`
- If you want to run in watch mode, then run `npm run watch`.
- In Postman or any other client, send a `GET` request to `<host:port>/api/` to see the API welcome response.

### Testing
- Run `npm test` to start the unit tests.

## API 

### Documentation
Coming soon...

### Authentication
We use JWT Bearer authentication. To get a authentication token, send a POST request to /api/login` with a valid email & password. You'll receive the token in response.

To authenticate further requests, set HTTP header `Authorization` to `Bearer <auth-token>` in http request.
