# RestPlate
A simple boilerplate to build a quick and basic REST API, using Node.js, MongoDB and JWT for authentication.

## Features
In order to kick start a simple yet robust REST API (thanks to its simple/straight forward structure), this project offers the following features:
- Make your endpoints in few simple steps
- Define your models and make your CRUD quickly using Mongoose
- Protect your endpoints and use JWT to ask for Authorization
- Easy Unit/E2E Tests to implement


## Goal and orientation
This boilerplate is intended for beginners and junior developers (Seniors might find a use of it), hence the code is meant to be simple and explicit.
- Most of the code is commented for more context (if necessary)
- No TypeScript; only JavaScript with some ES6 features
- Simple folder structure but easy to adjust if needed
- Usage of basic, common and popular libraries (for good documentation, community and support)

## Quick start

### Installation
```npm install```

### Run dev server
```npm run dev```

### Run tests
```npm run test```

### Run for production
```npm start```

This decision belongs to DevOps (docker container, pm2 ...)


## Why these packages?

### Packages
- Express: Our minimal flexible web framework to handle routes, requests, responses, middlewares ...
- Mongoose: Our elegant ODM (Object Document Mapper) for MongoDB
- DotEnv: This simple library handles Env Variables
- Morgan: An HTTP request logger that helps to track all HTTP calls

### Dev Packages
- Nodemon: A must have tool that allows to watch files changes and restarts the app automatically
- Mocha: A nice popular test framework for our automatic tests
- Chai: An assertion library that works flawlessly with Mocha in order to make our TDD/BDD tests

## TODOS
- Basic CRUD implementation
- Add JWT authentication and authorization middleware
- Unit tests
- MongoDB Memory Server for our tests
- Logger and Debugger tools

## Notes
- Basic JWT (with home made middleware) over Passport for better understading of stateless authentication