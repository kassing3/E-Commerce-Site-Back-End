# E-commerce Back End
[![The MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Description
This application provides back-end programming for an internet retail company's e-commerce website based on the following acceptance criteria:

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Installation
To use this application, use the command ```npm install``` to download the necessary modules/packages. Also, you will need MySQL to Sequelize the database.

## Usage
To use this application, add your MySQL username and password to an environment variable file. In the designated folder, connect your database through Sequelize using the command ``` source db/schema.sql.``` Next, seed your database using the command line and entering ```npm run seed.``` Finally, run the application by entering the command ```npm start.```

For a better understanding of it's functionality and how to use the program, feel free to view the [Walk-through Video](https://drive.google.com/file/d/1F33IUZpy6NtprKZ0wpC2Fj78br29KUjN/view).


## License
This project is licensed under [The MIT License](https://opensource.org/licenses/MIT)

 
