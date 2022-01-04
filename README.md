# E-COMMERCE BACK-END

## table of contents
- [objective](#objective)
- [description](#description)
- [visuals](#visuals)
- [usage](#usage)
  
## objective
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## description
``` 
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
## visuals
[![Image from Gyazo](https://i.gyazo.com/9baaf03a193b817b1b712f72603ecf8f.gif)](https://gyazo.com/9baaf03a193b817b1b712f72603ecf8f) <br>
you can watch a full demonstration of the application [here](https://watch.screencastify.com/v/VatbRO4YQshn4Tdzd5YJ)!

## usage
this application requires node.js, express.js, and sequelize. <br>
first, gitclone the repo from github. cd into application and run ```mysql -u root``` then source the db/schema.sql and quit out of mysql. run ```npm run seed```, and then run ```npm start```.


  

  