## ✨Object Relational Mapping: E-Commerce Back End✨

## Description 
This is a backend application that features mysql database for an e-commerce site. This application was built using MySQL, Express, and Sequelize. The database is seeded with data.

## Installation 
1. Run the commands `npm i` to install the necessary dependencies
2. Run `mysql -u root -p` and log into mysql
3. Run the command `source db/schema.sql` once logged into your MySQL database
4. Run `npm run seed` to seed data to your database
5. Finally, `npm start`, and go into Insomnia to test routes

## Demo

[ecommerce-part1.webm](https://user-images.githubusercontent.com/117967802/219299858-1d8f249d-017c-4222-ada7-40f5c4eedd36.webm)




[ecommerce-part2.webm](https://user-images.githubusercontent.com/117967802/219299877-7afcdf25-8567-4e30-aa02-8061861f819b.webm)





[ecommerce-part3.webm](https://user-images.githubusercontent.com/117967802/219299886-2ff610ae-8505-412d-9d2c-a63da4894c19.webm)





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
