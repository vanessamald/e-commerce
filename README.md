# E-commerce: Object-Relational Mapping

## Description
Build a database application for an e-commerce site using MySQL2, Express and Sequelize

## User Story
- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the - MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and - DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

## Installation
- npm init
- npm install mysql2
- npm install sequelize
- npm install dotenv

## Usage 
- run mysql -u root -p
- after password prompt:
- source db/schema.sql
- quit
- npm start

## Contributing
Vanessa Maldonado
