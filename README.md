# e-commerce-back-end

![Video of application](./assets/mysql-shell.webm)
![Video of application](./assets/get-requests-all.webm)
![Video of application](./assets/get-requests-single.webm)
![Video of application](./assets/post-put-delete.webm)

## Description 

In this week's challenge we were tasked with building back-end files for an e-commerce site. We used a variety of packages in Node.js including: Express.js, Sequelize, mysql2, and dotenv.

The project contains Models for Products, Categories, and Tags that are featured on the site, and each of these Models has routes to api endpoints for GET, POST, PUT, and DELETE requests.

The database is created via the MySQL shell using the command 'SOURCE db/schema.sql'. The database is connected to our javascript files via a Sequelize connection, which uses environmental variables through the dotenv module to specify the database name, the database user, and the database password.

Data is seeded to the e-commerce database using a variety of seed files, which can be run using the command 'npm run seed'.

The server connection is established using the command 'node server.js'.

This application will not be deployed, instead I will upload videos featuring the functionality of the project.


## Credits

Stephen Dickey - the author of this project (me).

GitHub page: https://github.com/StephenWDickey

Marcelo Gachet - Coding Bootcamp Instructor

Joseph Jepson - Coding Bootcamp tutor