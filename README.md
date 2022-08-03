
  # Ecommerce Backend

  ## Description

  * Create a backend for a theoretical E-Commerce site
  * Helps connect multiple databases into one larger one

  ## Table of Contents

  - [Installation](#Installation)
  - [Usage](#Usage)
  - [Contributors](#Contributors)
  - [Tests](#Tests)
  - [Questions](#Questions)

  ## Installation

  * Can be done by simply cloning from GitHub

  ## Usage

  ### Step 1 (YOU MUST HAVE NODE AND MYSQL ALREADY INSTALLED)
  * Once downloaded, open project in vscode, then open Terminal.  Once there, you need to run 'npm install express mysql2 sequelize dotenv'

  ### Step 2

  * Once you have installed the necessary modules, you can then create a .env file in your root directory, and fill it out to look like the following img:

  ### Step 3

  * In your terminal, type 'mysql -u root' and if your sql has a password, add -p.  Once in, type 'source db/schema.sql', then 'use ecommerce_db'.  Once completed, type 'exit'

  ### Step 4

  * In order to populate your database, type 'npm run seed' in your terminal.

  ### Step 5

  * Now that you are done with the preparation, you can now type 'npm start' in your terminal to start the server.  Now, you can go to Insomnia and try the different routes.
    * Base URLs for Routes
      * Category: localhost:3001/api/categories
      * Product: localhost:3001/api/products
      * Tags: localhost:3001/api/tags

  ## Contributors
  
  * Jake Mendez

  ## Tests

  * https://drive.google.com/file/d/1ZNU8PPJciBjV0UL4xiuZMtwjzah1Tthz/view

  ## Questions

  * [GitHub](https://github.com/jakem8532)
  * [Email](jakem8532@gmail.com)

