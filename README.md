# E-commerce Back End Challenge
![Github license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description

The starter code for this challenge contained a working Express.js API, but needed to be configured to use Sequelize in order to interact with the MySQL database. This allows for the application to act as the hypothetical back end for an e-commerce site. 

## Tabe of Contents

* [UserStory](#user-story)

* [AcceptanceCriteria](#acceptance-criteria)

* [Installation](#installation)

* [Usage](#usage)

* [Mock-Up](#mock-up)

* [WalkthroughVideo](#walkthrough-video)

* [License](#license)

* [References](#references)

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
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Installation

Start by cloning the starter code and make sure you have all necessary dependencies (npm install). Then, add parameters to each of the models and fill out the get, put, post, and delete routes. Make sure to sync sequelize to the database on server start in the server.js file (sequelize.sync) and to create a .env file containing the database name, your MySQL username, and your MySQL password (if you have one)!

## Usage

Run mysql -u root (with -p at the end if you made a password) and type in source db/schema.sql. Then, exit MySQL and put 'npm run seed' into your terminal in order to seed the data into the models. Then, type in 'npm start' in order to start your server. Lastly, open the API get routes for Categories, Products, and Tags in Insomnia to make sure the data is being properly displayed as JSON and can return all or a single item from each. After that, test the API post, put, and delete routes in Insomnia to make sure the data is successfully created, updated, and deleted in the database (CRUD).

## Mock-Up

![Untitled_ Jan 23, 2023 10_44 PM](https://user-images.githubusercontent.com/114205917/214230637-6eafbaae-c959-4a6e-94be-e7f27259dca6.gif)

## Walkthrough Video

View this [here](https://drive.google.com/file/d/1Ur9i7Gv2Ud5_C7jxthPB-c7duvweibki/view)

## License 

```
 MIT
``` 

## References

* [ExpressJS](https://expressjs.com/en/guide/routing.html)

* [FreshDesk](https://cloudblue.freshdesk.com/support/solutions/articles/44001885918-rest-api-sent-through-insomnia-returns-500-for-some-requests)

* [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

* [Tabnine](https://www.tabnine.com/code/javascript/functions/express/Router/post)

* [Tabnine2](https://www.tabnine.com/code/javascript/functions/express/Router/put)

* [Tabnine3](https://www.tabnine.com/code/javascript/functions/express/Router/delete)
