## Object-Relational Mapping (ORM): E-Commerce Back End

## Table of Contents
* [Project Description](#projectdescription)
* [Motivation for my Project](#motivationformyproject)
* [What I Learned](#whatilearned)
* [What I would do Differently](#whatiwoulddodifferently)
* [User Story](#userstory)
* [Acceptance Criteria](#acceptancecriteria)
* [Installation](#installation)
* [Links for Project](#linksforproject)
* [Acknowledgements](#acknowledgements)
* [Contact Information](#contactinformation)

## Project Description
This application uses the back end pat of code for an e-commerce site. I take a working Express.js API and configure it to use Sequelize to interact with a PostgreSQL database. In other words it is a digital shopping store that uses the database and server for inventory. It uses the Sequelize ORM to interact with a
MySQL database.


## Motivation for my Project
I wanted to learn how to use the ORM Sequelize to interact with a MySQL database. I also wanted
to learn how to use the Express.js API to interact with the database. I wanted to learn how
to use the Insomnia API to test the routes of the application. I wanted to learn how to
use the dotenv package to protect sensitive data. 

## What I Learned
I learned how to use the ORM Sequelize to interact with a MySQL database. I learned how to use
the Express.js API to interact with the database. I learned how to use the Insomnia API to
test the routes of the application. I learned how to use the dotenv package to protect sensitive data.
I learned how to used the GET, PUT, POST, and DELETE requests on insomnia to recieve data from the database.
I learned how to use the GET, PUT, POST, and DELETE requests on insomnia to send data
to the database. I learned how to use the GET, PUT, POST, and DELETE requests on
insomnia to update data in the database.


## What I would do Differently
I would include some other options like PATCH, HEAD, and OPTIONS to request data from the database.
I would also include more products in products.js to widen the options of the products sold in the store













## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the PostgreSQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```








## Installation
To install necessary dependencies, run the following command:
## Links
[videolink]
https://drive.google.com/file/d/1wh7ogX7GD8cNYbwxHjTbLUOmb9SSKD9P/view