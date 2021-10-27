# e-commerce-back-end
## Description
This application build the back end for an e-commerce site. It took a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## User Story
* AS A manager at an internet retail company
* I WANT a back end for my e-commerce website that uses the latest technologies
* SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API</br>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file</br>
THEN I am able to connect to a database using Sequelize</br>
WHEN I enter schema and seed commands</br>
THEN a development database is created and is seeded with test data</br>
WHEN I enter the command to invoke the application</br>
THEN my server is started and the Sequelize models are synced to the MySQL database</br>
WHEN I open API GET routes in Insomnia Core for categories, products, or tags</br>
THEN the data for each of these routes is displayed in a formatted JSON</br>
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core</br>
THEN I am able to successfully create, update, and delete data in my database</br>

## Languages
HTML, CSS, JavaScript, Node.js, Express.js, Npm Modules, dotenv Package, Sequelize, MySQL2

## Installation
The application require the use of node.js, Express.js, Sequelize & MySQL2 for running it.

## To Run the Application
Add a .env file to the root folder that contain the following
```
DB_NAME='ecommerce_db'
DB_USER='new_user'
DB_PW='XXXXXX'

## Screen Shots of the HTML
Adding Notes
![Screenshot of note adding](./images/note-taker1.png)
Retrieving Notes
![Screenshot of note viewing](./images/note-taker2.png)
Deleting Notes
![Screenshot of note deleting](./images/note-taker3.png)


## Deployed application link
https://secure-journey-45023.herokuapp.com

## Github Page: 
https://github.com/amykep/e-commerce-back-end