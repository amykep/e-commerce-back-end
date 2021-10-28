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
Add a .env file to the root folder that contain the following:</br>
DB_NAME='ecommerce_db'</br>
DB_USER='new_user'</br>
DB_PW='XXXXXX'</br>


## Walkthrough Videos
Create Schema and Seed Data
![Screenshot of note adding](./images/App-Initiation.gif)</br>
GET routes - Return all Categories, Products and Tags
![Screenshot of note viewing](./images/findAll.gif)</br>
GET routes - Return single Category, Product or Tag
![Screenshot of note deleting](./images/findOne.gif)</br>
Categories routes - Post, Put and Delete
![Screenshot of note deleting](./images/category-functions.gif)</br>
Products routes - Post, Put and Delete
![Screenshot of note deleting](./images/products_Functions.gif)</br>
Tags routes - Post, Put and Delete
![Screenshot of note deleting](./images/tags_Functions.gif)</br>

## Demonstration Videos
https://drive.google.com/drive/folders/1LUoVF3PZhso4GpKp_ERdaL-gAf1d10hQ?usp=sharing


## Github Page: 
https://github.com/amykep/e-commerce-back-end