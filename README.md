# E-commerce Website Back End
## Table of Contents
- [Description](#Description)
- [Technologies Used](#Technologies-Used)
- [Getting Started](#Installation)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#Configuration)
- [Usage](#usage)
  - [API Routes](#API-Routes)
  - [Testing](#Testing)
- [Contributing](#Contributing)
- [License](#license)

## Description
This is the back end for an e-commerce website that utilizes the latest technologies to help your company compete effectively in the online retail space. It provides a robust Express.js API integrated with a MySQL database using Sequelize for data modeling and interaction.

## Technologies Used
. Express.js
. MySQL
. Sequelize

## Installation

To set up the project locally, follow these steps:

1. Clone this repository to your local machine:
git clone git@github.com:Punk1776/ORM.git

2. Navigate to the project directory:
cd ORM

3. Install the required dependencies:
### npm install

## Configuration

Before running the application, you need to configure your database connection. Follow these steps:

1. Create an environment variable file (e.g., .env) in the project root.

2. Add the following variables to your .env file:
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password

Replace your_database_name, your_mysql_username, and your_mysql_password with your actual MySQL database credentials.

## Usage

After configuring the database, you can start the application by right clicking on the server.js file and opening your terminal, in your terminal enter the following commands:

### npm run seed 
### npm start

This will start the server and sync Sequelize models with the MySQL database.
[Untitled_ Sep 27 2023 3_04 PM.webm](https://github.com/Punk1776/ORM/assets/135387049/19cc9593-7571-4f16-ae43-4feeb0723d78)


## API Routes

The API provides the following routes:

GET /api/categories: Get a list of all categories in JSON format.
GET /api/products: Get a list of all products in JSON format.
GET /api/tags: Get a list of all tags in JSON format.
POST /api/categories: Create a new category.
POST /api/products: Create a new product.
POST /api/tags: Create a new tag.
PUT /api/categories/:id: Update an existing category by ID.
PUT /api/products/:id: Update an existing product by ID.
PUT /api/tags/:id: Update an existing tag by ID.
DELETE /api/categories/:id: Delete a category by ID.
DELETE /api/products/:id: Delete a product by ID.
DELETE /api/tags/:id: Delete a tag by ID.

## Testing
You can use Insomnia Core or any API testing tool to test the API endpoints. Make sure to test GET, POST, PUT, and DELETE routes for categories, products, and tags as specified in the acceptance criteria.

## Contributing
We welcome contributions from the community. If you'd like to contribute to this project, please follow our contribution guidelines.

## License
This project is licensed under the MIT License.
