# Udagram - Hosting a Full-Stack Application

project 3 of Advanced Web Development Nanodegree from Udacity - EGFWD

## Getting Started

1. Clone this repo - write in terminal :

   ```sh
   git clone https://github.com/ahkh7/AK_Udagram.git
   ```

2. ```sh
   cd ak_udagram
   ```
3. ```sh
   npm run frontend:install
   npm run backend:install
   ```
4. #### DB Creation and Migrations

   ```sh
   psql -U postgres
   ```

   ```sh
   CREATE DATABASE POSTGRES_DB;
   CREATE DATABASE POSTGRES_DB_TEST;
   ```

   ##### Create .env file and use this variables:

   -  POSTGRES_HOST=
   -  PORT=
   -  DB_PORT=
   -  POSTGRES_USERNAME=
   -  POSTGRES_PASSWORD=
   -  RDS_DIALECT=
   -  POSTGRES_DB=
   -  AWS_REGION=
   -  AWS_PROFILE=
   -  AWS_BUCKET=
   -  URL=
   -  AWS_ACCESS_KEY_ID=
   -  AWS_SECRET_ACCESS_KEY=
   -  JWT_SECRET=

   ##### Note

   -  Server Port = 3000
   -  Database Port = 5432

   ##### Install Migrations

   ```sh
   db-migrate up
   ```

5. ```sh
   1. cd udagram-api

   3. npm run dev
   ```

   -  Then

   ```sh
   1. cd ../

   2. cd udagram-frontend

   3. npm start
   ```

### Dependencies

A list of project dependencies can be found [here](docs/dependencies.md).

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

##### Unit Tests:

Unit tests are using the Jasmine Framework.

##### End-to-End Tests:

The e2e tests are using Protractor and Jasmine.

## S3 Link

http://ak-udagram1.s3-website-us-east-1.amazonaws.com

## Built With

-  [Angular](https://angular.io/) - Single Page Application Framework
-  [Node](https://nodejs.org) - Javascript Runtime
-  [Express](https://expressjs.com/) - Javascript API Framework

## By

Ahmed Khairy - github.com/ahkh7

## Version

-  0.1

## License

Udacity project
