# E-Commerce-Back-End

![ICS](https://img.shields.io/badge/license-ICS-orange)

## Table of Contents
- [License](#license)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Tests](#tests)
- [Usage](#usage)
- [Walkthrough](#walkthrough)
- [Contact](#contact)


## License
Read more about the license here: [ICS](https://choosealicense.com/licenses/isc/)

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

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

**You'll need these packages to run the application:**
- mySql2
- Express
- Dotenv
- Sequelize

**Open Insomnia once the app is starts running:**
```
App listening on port 3001!
```

## Tests
**To test the application, run this code in the CLI:**
```
npm start
```

## Usage
The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./assets/get-all.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./assets/get-one.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./assets/create-update-delete.gif)

## Walkthrough
Watch the walkthrough to see how the application is used: <ins>[E-commerce Backend](assets/walkthrough-e-commerce-backend-.webm)<ins>

## Contact

### Questions? Reach me here:  
Github: Amandagl1  
Email: leeandama87@gmail.com