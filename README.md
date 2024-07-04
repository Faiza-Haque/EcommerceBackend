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
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria
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


## Installation
To install this application you will need to install the following dependencies like postgres, npm install, npm run seed, and install database schema.sql.
Steps to follow:
1. Clone the repository to your local machine.
2. Open the terminal and navigate to the root directory of the project.
3. Run the command "npm install" to install the necessary dependencies.
4. Create a .env file in the root directory of the project and add the following environment variables
- DB_NAME
- DB_USER
- DB_PW
5. Run the command "npm run seed" to seed the database with test data.
6. Run the command "npm start" to start the server.
7. Open Insomnia and test the API routes.
8. Enjoy!
In order to run these platform you'll need to follow these steps in the terminal.
Step 1. psql -U postgres
Step 2. \i db/schema.sql
Step 3. npm install
Step 4. npm run seed
Step 5. npm start
Afterwards, you'll open Insomnia to run test on the application.
GET routes to return all categories, all products, and all tags being tested in Insomnia Core.
The categories, tags, and products will have GET, POST, PUT and DELETE as options on the left side of the http link. Depending on the the request you are making use the GET, POST, PUT, and DELETE request to see the necessary data requests.
Use the schema.sql file in the db folder to create your database using PostgreSQL shell commands. Use environment variables to store sensitive data, like your PostgreSQL username, password, and database name.


## Links
[videolink]
https://drive.google.com/file/d/1wh7ogX7GD8cNYbwxHjTbLUOmb9SSKD9P/view
[githublink]
https://github.com/Faiza-Haque/EcommerceBackend


## Acknowledgments 
- Tutors and TAs
- Thinh, Marissa, Anna
- My Instructor
- My Friends
Everyone listed above helped me complete this project. I would like to thank them for their support.


## Contact Information
Thanks for exploring my Repo!

If you would like to know more please feel free to contact me:
Email: faizahaque90@gmail.com
GitHub URL: https://github.com/Faiza-Haque
LinkedIn URL: https://www.linkedin.com/authwall 