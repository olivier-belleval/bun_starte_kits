# Bun Starter Kits

## Objectives

Get backend and frontend starters running with Bun Js.

### Backend
**The backend starter is a simple REST API with a Postgres database.**

branch: `backend-starter`

It's an architecture to get you started with Bun API typescript.

ORM : Prisma
use Express middleware

#### How to use

- Clone the repository
- Install dependencies with `bun install`
- Run the server with `bun dev` dev mode or `bun start` production mode
- Go to `http://localhost:3000/swagger/` to see the API documentation
- architecture:
  - `prisma/` contains the ORM
    - `prisma/prisma.schema` contains the models
  - `src/` contains the source code
    - `src/controllers/` contains the controllers
    - `src/services/` contains the services
    - `src/utils/` contains the utils
    - `src/utils/prismaClient.ts` is the entry point of the ORM
    - `src/index.ts` is the entry point of the application
    - `src/routers` contains the routes
    - `src/middlewares` contains the middlewares
    - `src/types` contains the types
    - `src/config` contains the config



### Frontend
**The frontend starter is a SSR React application.**

branch: `frontend-starter`

It's a atomic design architecture to get you started with Bun SSR REACT typescript.
