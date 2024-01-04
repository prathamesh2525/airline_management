# Welcome to Airline_management

## Project Setup

- clone the project on your local
- Execute `npm install` on the same path as your local direcotyr of the downloaded project
- create a .env file in root directory and add the following snvironment variable
  - `PORT=4747`
- Inside the src/config folder create a new file `config.json` abd then add the following piese of json

```
{
    "development": {
    "username": <YOUR_DB_LOGIN_NAME>,
    "password": <YOUR_DB_PASSWORD>,
    "database": <DB_NAME>,
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

```

- Once you've added your db config as listed above, go to the src folder from
  your terminal and execute `npx sequelize db:create`
