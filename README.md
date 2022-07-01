<h1 align="center">E-Commerce Database</h1>

## Description

This app primarily deals with the back end for a dummy e-commerce website. It exclusively features Express.js API in conjunction with Sequelize. MySQL is also used to create, initialize, and seed a database with products by tag, category, and product IDs.

Below are .gif files showing functionality of the app. In order to test the API routing, Insomnia was used to create the environment for testing.

### Get All Categories/Tags/Products

![Get All Categories/Tags/Products](./assets/13-orm-homework-demo-01.gif)

### Get Category/Tag/Product By ID

![Get Category/Tag/Product By ID](./assets/13-orm-homework-demo-02.gif)

### Create Category/Tag/Product by ID

![Create Category/Tag/Product by ID](./assets/13-orm-homework-demo-03.gif)

## Full Movie Link for App Functionality (2 Parts)

[Part 1](https://www.youtube.com/watch?v=VltFkmXgOt8I)

[Part 2](https://www.youtube.com/watch?v=vaM9IXlZ-DU)

## Installation Parameters

`npm i` allows for necessary installation of miscellaneous packages. `mysql -u root -p` and `source db/schema.sql` are necessary for login to mySQL, and initialization of the database. Finally, `npm run seed` and `node server.js` is used, both to seed the database and initialize the app. From here, the app will be able to listen onto the proper port, hereby activating the routes and ensuring proper CRUD functionality.

## Test Parameters

No tests necessary. Just plug and go!

## Questions? Comments?

Contact me on Github or via email! </br>
Github: [github.com/joeytmab](github.com/joeytmab) </br>
Email: [joseph.t.binas@gmail.com](joseph.t.binas@gmail.com)
