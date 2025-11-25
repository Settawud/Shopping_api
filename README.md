# Shopping API (CRUD)

This is a RESTful API for a Shopping application built with [NestJS](https://nestjs.com/). It provides CRUD operations for managing products and uses MySQL as the database.

## Features

- **Product Management**: Create, Read, Update, Delete (CRUD) products.
- **Database Integration**: Uses TypeORM with MySQL.
- **API Documentation**: Integrated with Swagger UI.

## Tech Stack

- **Framework**: NestJS
- **Language**: TypeScript
- **Database**: MySQL
- **ORM**: TypeORM
- **Documentation**: Swagger

## Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd crud_api
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```

## Configuration

Ensure you have a MySQL database running and configure the connection settings in `src/app.module.ts` (or use environment variables).

## Running the Application

```bash
# development
npm run start

# watch mode
npm run start:dev

# production mode
npm run start:prod
```

## API Documentation

Once the application is running, you can access the Swagger UI documentation at:

```
http://localhost:3000/api
```
(Note: The path `/api` depends on your `main.ts` configuration. If you haven't set a global prefix or Swagger path, check `src/main.ts`.)

## License

This project is [UNLICENSED](LICENSE).
