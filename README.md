# node-docker-truck-app

## About
This is Node.js API built to do CRUD Operations on TRUCK DATABASE

## Requirements
### Intro
In this exercise you are going create a Rest full API, that will be responsible for saving and
listing trucks data as following
- Create and Edit a Truck
- View a Truck
- List all Trucks
- Create/save Truck Location (latitude/longitude)
- List all locations of a truck
### Technical Requirements
- You must use the NodeJS in backend
- You must save the data in a database.
- You can use other libraries to help if you want, ex:
- Express, Sequelize, etc
- Build System (Gulp/Grunt/NPM)

## Implementation Details 
- The API has been built using Node.js
- MongoDB for storing Truck Information 
- Mongoose for Object Modelling Tool on MongoDB
- API Endpoints Test done using Postman
- Unit API Tests done using JEST and Super Test
- User Authentication using JWT Token
- Bcrypt for encrypting Passwords

## Running Application Locally
- Ensure Node and MongoDB is installed on your machine
- Navigate to this project directory 
- Run following commands
* ```npm install```
* ```npm run dev```

## Running JEST Tests Locally
- Ensure Node and MongoDB is installed on your machine
- Navigate to this project directory 
- Run following commands
* ```npm run test```

## Running Application on Docker
- Ensure Docker is installed on your machine
- Navigate to this Project directory
- Run following commands
* ```docker-compose build```
* ```docker-compose up```

