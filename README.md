# E-commerce Back End (ORM: Object-Relational Mapping)

## Description

A backend application using the MySQL database and Sequelize ORM for an e-commerce platform.

## Built with

- JavaScript
- MySQL2
- Node.js
- Sequelize
- Express
- dotenv

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install express`

`npm install dotenv`

## Usage

`mysql -u root -p`

`source db/schema.sql`

`npm run seed`

`npm start`

## Demonstration

### Creating the schema from the MySQL shell, seeding the database from the command line, and starting the server

<img src="./Develop/assets/video1.gif" alt="" /></br>
Video link: https://drive.google.com/file/d/1KNSdsGaOzPaBuJVvNiP7ZnSe_g9VyWtb/view

### GET routes for all categories, all products, and all tags in Insomnia

<img src="./Develop/assets/video2.gif" alt="" /></br>
Video link: https://drive.google.com/file/d/1Rh5A6CF6UNMpN3iLTWRdDEwi5bcx-1aG/view

### GET routes for a single category, a single product, and a single tag in Insomnia

<img src="./Develop/assets/video3.gif" alt="" /></br>
Video link: https://drive.google.com/file/d/1mkMriKv-yDRvGMgyu-jSDGxjjU1gq-3O/view

### POST, PUT, and DELETE routes for categories, products, and tags in Insomnia

<img src="./Develop/assets/video4.gif" alt="" /></br>
Video link: https://drive.google.com/file/d/1cxHeYlFZ3dKn7Nhjnhnm9OShXVKnk_P6/view
