# E-Commerce Backend

## Table of Contents
- [Description](#description)
- [Built With](#built-with)
- [Contribution](#contribution)
- [Installation](#installation)
- [Usage Instructions](#usage-instructions)
- [Demonstration Video](#demonstration-video)

## Description
This application is intended to allow users to manage products, product categories, and product tags for an e-commerce website. 

This application also serves as a submission to an assignement that tests students skills with Javascript, Node.js, and the Node.js Sequelize package.

## Built With
- JavaScript
- Node.js
    - MySQL2 package
    - Sequelize
    - Dotenv
- SQL
- MySQL

## Contribution
- Javascript and Node.js contributions by Micah Zahn

## Installation
- Clone down to a local repository.
- Run "npm install" in the root of the project to get the nessessary node modules.
- Ensure that MySQL is installed and open. Then run "source db/schema.sql" to initialize the employee_info database.
- In the root of the database, create a ".env" file.
    - In the file, add DB_NAME='ecommerce_db'
    - In the file, add DB_USER='your mysql username'
    - In the file, add DB_PW='your mysql password'
- Go to the root of the application and run "npm run seed" to seed the database.

## Usage Instructions
- Run "npm start" in the root of the project to start the server.
- Use a rest api to perform GET, POST, PUT, and DELETE actions.
- See "routes" folder for routes that can be used.

## Demonstration Video
