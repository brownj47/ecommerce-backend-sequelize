# E-Commerce Backend: Sequelize

## Description

This application is a backend server that uses MySQL, and is manipulated with javascript through express.js and sequelize.js. I learned about nesting data in JSON objects, creating url routes, syncing a server to a database, and manipulating a database through JavaScript. 
## Installation

1. Clone the repo found at this link: [https://github.com/brownj47/ecommerce-backend-sequelize](https://github.com/brownj47/ecommerce-backend-sequelize)
2. Install MySQL following this guide: [https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide](https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide)
3. Run the command 'mysql -u root -p' in the terminal while in the root directory of the cloned repo to open mysql.
4. From the root directory of the repo, run 'SOURCE db/schema.sql;' to create the data structure for your application.
5. Run the command 'exit;' to exit mysql.
6. Run npm i to install the node modules.
7. Rename the file '.env.example' to '.env', and fill the enclosed fields with the password you set for MySQL.
8. Run 'npm run seed' to seed the database.


See this link for a detailed walkthrough: https://drive.google.com/file/d/1hdUgp4vxri3koYUd1ZOdCmYGXEJ0Yc-h/view


## Usage

Run 'npm start' to start the server. 
Then drag and drop the insomnia.json file found in the root directory fo the project into an insomnia collection and it should import, allowing you to run and test all of the routes on the server. 