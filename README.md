### Tools Used: 
# Nodejs version - 20.11.1,
# Express (NPM version) - 10.4.0
# PostgreSQL - 16.2
## Setup PostgreSQL with Sequelize in Express
# [(https://www.robinwieruch.de/postgres-express-setup-tutorial/)]
### First make sure PostGre Sql is working 
* Then in index.js file modify the credential of database
### In my case this is
*  const pool = new Pool({
*  user: 'postgres',
*  host: 'localhost',
*  database: 'postgres1',
*  password: '9835',
*  port: 5432,
*  });
### Now change it according to your DB info
### After this run - npm install
##   Then run - node index.js to start server
