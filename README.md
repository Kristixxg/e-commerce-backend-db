# E-Commerce Back-end Management Tool
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This application provides a back-end for e-commerce companies to management their databases. The application uses Express.js API to use Sequelize to interact with MySQL database.

A link to walk-through videos that demonstrate application's functionalities:

https://drive.google.com/drive/folders/1Ou5_jZdFKEA3lKVLcQOigcN4GSzyyV6x?usp=sharing


## Usage

You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data like a user’s MySQL username, password, and database name. User needs to create a new .env file for sensitive data.


## Demo
- Invoke the application from the command line

<img src="assets/Invoke.gif" width="900">

- After creating the models and routes, run `npm run seed` to seed data to your database so that you can test your routes.

<img src="assets/seeds-db.gif" width="900">

- GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

<img src="assets/Get-categories_products_tags.gif" width="900">

- GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

<img src="assets/GET-category1_product1_tag1.gif" width="900">

- POST route for categories being tested in Insomnia Core:

<img src="assets/POST-category.gif" width="900">

- PUT route for categories being tested in Insomnia Core:

<img src="assets/PUT-category.gif" width="900">

- DELETE routes for categories being tested in Insomnia Core:

<img src="assets/DELETE-category.gif" width="900">

- POST route for products being tested in Insomnia Core:

<img src="assets/POST-product.gif" width="900">

- PUT route for products being tested in Insomnia Core:

<img src="assets/PUT-product.gif" width="900">

- DELETE routes for products being tested in Insomnia Core:

<img src="assets/DELETE-product.gif" width="900">

- POST route for tags being tested in Insomnia Core:

<img src="assets/POST-tag.gif" width="900">

- PUT route for tags being tested in Insomnia Core:

<img src="assets/PUT-tag.gif" width="900">

- DELETE routes for tags being tested in Insomnia Core:

<img src="assets/DELETE-tag.gif" width="900">

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) 2022 Kristy Guo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



