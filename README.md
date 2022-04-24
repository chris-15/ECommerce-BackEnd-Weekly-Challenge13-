# E-commerce Back End Weekly Challenge 13


  ![badge](https://img.shields.io/badge/license-MIT%20License-blue)

 ## Table of Contents 
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Tests](#tests)
  - [Credits](#credits)
  - [License](#license)
  


## Description 

The purpose of this week's challenge was to a back-end server for an e-commerce website using node.js, express.js, MySQL, and Sequelize. The dotenv package was installed and used to store sensititve data like the users MySQL username and password.



Below are the challenge requirements:

- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

<br>

A video of the application in use: 

[Demonstration Video](https://drive.google.com/file/d/1XZGYOxI94kOa3ZES6aCLdHdSDqjbpLLs/view?usp=sharing)

<br>

## Installation

The user must install Node.js, Express.js, dotenv, MySQL2, and Sequelize packages before use.


## Usage 

This application can be used to manage an ecommerce back-end server database. To start the application, the user must first create the database in the MySQL shell command line. Then the user must seed the databse in the command line with the command "npm run seed". Finally the user can start the server with the command "npm start".

## Tests

No tests conducted for this application.

## Credits

- AskBCS
- Various Classmates
- TA's
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [MySQL2 Documentation](https://www.npmjs.com/package/mysql2#documentation)
- [MySQL Documentation](https://dev.mysql.com/doc/refman/8.0/en/)
- [dotenv Documentation](https://www.npmjs.com/package/dotenv)
- [Sequelize Documentation](https://sequelize.org/docs/v6/)
- [Express.js](http://expressjs.com/en/4x/api.html)


## License

MIT License

Copyright (c) [2022] [Christopher Sarmiento-Salas]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.