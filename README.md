# e-commerce-back-end

## Description

The goal of this project was to create the back end for an e-commerce site. The project would use a postgreSQL database and Sequalize to create a working Express.js API that that would get able to perform all four types of fetch requests. It can GET data about the products, categories and tags of items. It can also POST new items, PUT updates for items, and also DELETE items.

## Installation

You will need to open the terminal and run npm install to load in all necessary dependencies. Next you will need to find and open the .env.EXAMPLE file and add in your postgres username and password. Then rename the .env.EXAMPLE file to be just .env. Next you will want to open the terminal and open postgres with the command psql -U postgres. Then run the schema.sql file in the db folder so the necessary database is possibly dropped and then created. Then run the command npm run seed to create and seed the database tables. Once that is done the application should be ready to run.

## Usage

After installation is done you open the terminal and run the application with either node server.js or with npm start. This will start and syncronize the server with the sequelize database. From there you open insomniac and make your api fetch requests.

Below are screenshots showing insomnia requests being answered.

![Application at start]()

![Application showing data tables]()

Link to a walkthrough video showing the application in action:
[Walkthrough Video]()

## Credits

N/A

## License

N/A

## Contribute

N/A
