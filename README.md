# Serverless-Series TODO MVC APP 

This is a modified version of the TodoMVC application that uses a backend.

For the simple API  the following actions need to be implemented

## Actions for backend

```
POST /api/todos - Create TODO
DELETE /api/todos/{id} - Delete TODO
PATCH /api/todos/{id} - Edit TODO
GET /api/todos - get all todos
```

## Building this app

This application is a monorepo built using `lerna`

Once cloned run `lerna bootstrap` to install dependencies then `npm run start` to start the application. 

NO backend has been added so the application will fail if you try to do anything 

