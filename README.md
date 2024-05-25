# module13
# E-commerce Back End

This is the back end for an e-commerce site using Express.js, Sequelize, and PostgreSQL. It manages categories, products, and tags.

## User Story

As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies.

## Acceptance Criteria

- Add database credentials to a `.env` file to connect using Sequelize.
- Run schema and seed commands to create and seed the database.
- Start the server to sync Sequelize models with the database.
- API GET routes display data in JSON format.
- API POST, PUT, and DELETE routes allow data manipulation.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/khalilhusnain/module13.git
    cd module13
    ```
2. Install dependencies:
    ```sh
    npm install
    ```
3. Create a `.env` file with your PostgreSQL credentials:
    ```env
    DB_NAME='your_database_name'
    DB_USER='your_postgresql_username'
    DB_PASSWORD='your_postgresql_password'
    DB_HOST='localhost'
    DB_PORT=5432
    APP_PORT=3000
    ```
4. Create and seed the database:
    ```sh
    npx sequelize-cli db:create
    npx sequelize-cli db:migrate
    npx sequelize-cli db:seed:all
    ```

## Usage

Start the server:
```sh
npm start
```
## API Routes
# Categories

GET /api/categories
GET /api/categories/:id
POST /api/categories
PUT /api/categories/:id
DELETE /api/categories/:id

# Products

GET /api/products
GET /api/products/:id
POST /api/products
PUT /api/products/:id
DELETE /api/products/:id

# Tags

GET /api/tags
GET /api/tags/:id
POST /api/tags
PUT /api/tags/:id
DELETE /api/tags/:id
# Demo Video
Watch the [Demo Video](https://drive.google.com/file/d/1DbZsPQXGwuJiGrqTZtmXGimwcjiv01ZB/view?usp=sharing) to see the setup and usage of the application.
