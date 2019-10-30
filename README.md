# Bootcamp 2019 - Gympoint

## Setup and run

```shell
yarn
yarn sequelize db:migrate
yarn sequelize db:seed:all
yarn dev
```

## Routes

| Path          | Method | Description                | Body fields                                                             |
| ------------- | :----: | -------------------------- | ----------------------------------------------------------------------- |
| /users        |  GET   | Retrieves all users        | N/A                                                                     |
| /users/:id    |  GET   | Retrieves an user by id    | N/A                                                                     |
| /users/       |  POST  | Creates a new user         | name: string, email: string, password: string                           |
| /users/:id    |  PUT   | Updates an user            | name: string, email: string, [password: string]                         |
| /students     |  GET   | Retrieves all students     | N/A                                                                     |
| /students/:id |  GET   | Retrieves an student by id | N/A                                                                     |
| /students/    |  POST  | Creates a new student      | name: string, email: string, age: integer, weight: float, height: float |
| /students/:id |  PUT   | Updates an user            | name: string, email: string, age: integer, weight: float, height: float |
