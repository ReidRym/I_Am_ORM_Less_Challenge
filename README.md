# I Am ORM Less Challenge
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Description
This repository contains an Express.js API with a MySQL database for an e-commerce website. It uses the latest technologies to provide a secure and functional back-end. After adding the database name, MySQL username, and MySQL password to an environment variable file, users can connect to the database using Sequelize. Schema and seed commands can be run to create a development database and seed it with relevant test data. Once the application is invoked, the server is started and the Sequelize models are synced to the MySQL database. API GET routes can be opened in Insomnia Core for categories, products, or tags, which will display the data in a formatted JSON. API POST, PUT and DELETE routes can also be tested in Insomnia Core, allowing users to successfully create, update, and delete data in the database. With this repository, users will be able to provide a secure and up-to-date back end for their e-commerce website.

## Images 

## Table of Contents

* [TITLE](#title)
* [DESCRIPTION](#description)
* [INSTALLATION](#installation)
* [USAGE](#usage)
* [BADGES](#badges)
* [FEATURES](#features)
* [TESTS](#tests)
* [CONTACT](#contact)
* [GITHUB](#github)
* [EMAIL](#email)


## Installation
1. Clone or download this repository. 
2. Navigate to the root directory and open a terminal window.
3. Install the necessary dependencies with the command `npm install`.
4. Create a `.env` file in the root directory. 
5. Enter your MySQL username, password, and database name in the `.env` file.
6. To start the server, run the command `npm start`.
7. To create the development database and seed it with relevant test data, run the command `npm run schema:create` followed by `npm run seed:run`.
8. Use Insomnia Core to open the GET routes in order to view the data in a formatted JSON.
9. Use Insomnia Core to open the POST, PUT and DELETE routes in order to create, update, or delete data in the database.

You are now ready to use this Express.js API with a MySQL database for your e-commerce website!


## Usage
1. Clone or download this repository. 
2. Navigate to the root directory and open a terminal window.
3. Install the necessary dependencies with the command `npm install`.
4. Create a `.env` file in the root directory. 
5. Enter your MySQL username, password, and database name in the `.env` file.
6. To start the server, run the command `npm start`.
7. To create the development database and seed it with relevant test data, run the command `npm run schema:create` followed by `npm run seed:run`.
8. Use Insomnia Core to open the GET routes in order to view the data in a formatted JSON.
9. Use Insomnia Core to open the POST, PUT and DELETE routes in order to create, update, or delete data in the database.

You are now ready to use this Express.js API with a MySQL database for your e-commerce website!

## license
MIT

## Features  
• Connect to MySQL database using MySQL2 and Sequelize packages
• Create a development database and seed it with test data
• Start a server and sync the Sequelize models with the database
• Open API GET routes in Insomnia Core to display data in JSON format
• Test API POST, PUT and DELETE routes to create, update and delete data in the database
• Utilize dotenv package to store sensitive data like MySQL username, password and database name in an environment variable file
• Provide a secure and up-to-date back end for e-commerce website users


## Tests  
This repository contains automated tests that ensure the API is working correctly with the database as expected. To set up automated tests, you will need to configure the database details as environment variables in a .env file. Choose your favorite framework for running tests, which utilize the Sequelize API to ensure that integration of data points between the API and database match expectations. Once the .env file has been configured, users can run `npm run test` to ensure that all the API routes are working correctly. Users can also create extra test specs as needed to check for specific criteria. Deploying unit test scripts to the repository will also be beneficial in the long-term, ensuring that the code remains secure and up-to-date. With these automated tests, users will be able to make sure their e-commerce website is functioning correctly and that the API is securely integrated with the MySQL database.


## GitHub
GitHub: [github.com/ReidRym](https://github.com/github.com/ReidRym)


## Email
Email: [irishreid55@gmail.com](mailto:irishreid55@gmail.com);









