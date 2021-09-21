# E-Commerce Backend

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)
- [Links](#links)

## Description

The E-Commerce Backend allows the creating of a store inventory API through the command-line. The API will store information on products, such as the category they are in, their price, how much stock they have, and their associated store tags.

## Installation

To install, you must run MySQL with ```mysql -u root -p``` and then input ```source db/schema.sql```. Once you are finished initializing the database, you can enter ```node seeds``` in the terminal if you wish to seed the API with example data. If not, you can just run ```npm start``` to begin.

## Usage

Once the program is started, the user has a multitude of commands to work with. The user can see all, create new, update existing, or delete existing categories, products, or store tags. The associated route for categories is ```localhost:3001/api/categories```, while products is ```localhost:3001/api/products```, and tags is ```localhost:3001/api/tags```. In each of those associated routes, the user can run a GET command to get all, a POST to create new, a PUT to update an existing, or a DELETE to delete an existing. For the PUT and DELETE commands the user will have to give an id to an existing category, product, or tag (i.e. ```localhost:3001/api/category/3```).

Link to video walkthrough: https://drive.google.com/file/d/108BynqWfoLpWhcCsjSj8xFNTzvZHJX5Z/view?usp=sharing

## Questions

If you have any questions regarding the application that are not answered in this README, you can contact me at: 

github.com/ccardinale98

or

ccardinale98@gmail.com

## Links

https://drive.google.com/file/d/108BynqWfoLpWhcCsjSj8xFNTzvZHJX5Z/view?usp=sharing

https://github.com/ccardinale98/e-commerce-backend