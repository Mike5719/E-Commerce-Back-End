# E-Commerce-Back-End

## Description

In this challenge assignment we were asked to build the back end for an e-commerce site by modifying starter code. This was done by configuring a working Express.js API to use Sequelize to interact with a MySQL database. 

The Acceptance Criteria is as follows:

```md
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

To run this application the user will need to install the following npm packages:
    - express@4.17.1
    - mysql2@2.1.0
    - sequelize@5.21.7

The user will also need to source the schema.sql in MySQL, seed the database by using the command npm run seed in the node terminal. Finally npm start will start the application.


## Usage

Link to walkthrough video demonstrating the functionality of the application:

https://drive.google.com/file/d/1zpSdylESMZh7t44py9pQ_gAUQ83YuH1c/view


The application can be used in the Insomnia environment.

![Insomnia Screenshot](<./assets/Screenshot.png>)

## Credits

TA Mark Alfano helped me debug the router.put function in the category-routes.js file on lines 48-60.
AskBCS assisted with debugging line 11 in the tag-routes.js file.
AskBCS also assisted with debugging the association models starting on lines 19 and 28 in the index.js file within the models folder.


## License

MIT License










