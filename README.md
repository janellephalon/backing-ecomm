# Backing E-Comm - Homework 13

## Description
This application is designed to demonstrate an understanding of fundamental architecture of e-commerce websites. The goal is to configure Sequelize to interact with a MySQL database - building the back end of an e-commerce site. 

## Table of Contents 
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Demo](#demo)
  - [Contributors](#contributors)


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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation
`npm init` <br>
`npm install mysql2` <br>
`npm install sequelize`<br>
`npm install dotenv`

## Usage
`npm run seed`<br>
`npm start`

## Demo 
* [Category Route Walkthrough](https://drive.google.com/file/d/1LwZIm48rgxHSH4MilHmKJZZs7G2V7CKv/view?usp=sharing)
* [Product Route Walkthrough](https://drive.google.com/file/d/1nzrb_yGz6yG5moV5GNP3cEj8NA1HK0-m/view?usp=sharing)
* [Tag Route Walkthrough](https://drive.google.com/file/d/1o13LQHujvt-0zdL87Mg1XPhBYP6ZCohT/view?usp=sharing)

## Contributors
* [Janelle Phalon](https://github.com/janellephalon) - Columbia University Coding Bootcamp 
* [Starter Code](https://github.com/coding-boot-camp/fantastic-umbrella) 
