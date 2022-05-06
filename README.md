## Table of contents

## License

# Description
An application for the back end for an e-commerce site.

## Installation

After cloning the application to your terminal go to the root of the project directory. Enter in the terminal 'npm init-y' and 'npm i sequelize mysql2 dotenv'

## Usage

Go to the mysql shell by running the following command 'mysql -u root -p' and then enter your password. Run the following command to source the database 'source db/schema.sql'. Enter 'show databases' and then enter 'use ecommerce_db'. Then enter 'quit' to close the mysql shell. In your terminal seed the database by running the following command 'npm run seed' and then enter 'npm start'. Go to Insomnia to test the routes. 


## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

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

