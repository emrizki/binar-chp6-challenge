# [FSW] - Chapter 6 Challenge 

### Challenge
1. Simple monolith dashboard using view engine (EJS) :heavy_check_mark:
2. Super user authentication login dashboard using static data :heavy_check_mark:
3. Create 3 table:
    - UserGame table :heavy_check_mark:
    - UserGameBiodata table :heavy_check_mark:
    - UserGameHistory table :heavy_check_mark:
4. Connect to SQL database with method:
    - Create UserGame data :heavy_check_mark:
    - Read UserGame data :heavy_check_mark:
    - Update UserGame data :heavy_check_mark:
    - Delete UserGame data :heavy_check_mark:
5. Designing and Implementing database schema that links 3 table which UserId as Parent Key (PK) :heavy_check_mark:
6. RESTFUL API one endpoint with CRUD method (create, read, delete, update) :heavy_check_mark:
7. Database table attribute:
    - UserGame :heavy_check_mark:
        * email 
        * username
        * password
    - UserGameBiodata :heavy_check_mark:
        * name
    - UserGameHistory :heavy_check_mark:
        * result
 
 ## Getting Started 🚀
 
 These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
 
 ### Prerequisites 📋
 
 You'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [NPM](http://npmjs.com)) installed on your computer.
 
 ```
node@v10.16.0 or higher
npm@6.9.0 or higher
git@2.17.1 or higher
```
## How To Use 🔧

From your command line, first clone:

```bash
# Clone this repository
$ git clone https://github.com/emrizki/binar-chp6-challenge.git

# Go into the repository
$ cd binar-chp6-challenge

# Remove current origin repository
$ git remote remove origin
```

Then you can install the dependencies using NPM:

Using NPM:

```bash
# Install dependencies
$ npm install

# Start development server
$ npx nodemon index.js
```

**NOTE**:
If your run into issues installing the dependencies with NPM, use this command:

```bash
# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
```
Once your server has started, go to this url `http://localhost:3000/` and you will see the website running on a Development Server:

<h2 align="center">
  <a href="https://ibb.co/q143DHZ"><img src="https://i.ibb.co/WKd4HrT/Screenshot-from-2021-09-20-22-09-50.png" alt="Screenshot-from-2021-09-20-22-09-50" border="0"></a>
</h2>

## Technologies used 🛠️

- [ExpressJS](https://expressjs.com/) - Web framework for Node.js
- [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) - Front-end open source toolkit
- [Sequelize](https://sequelize.org/) - A promise-based Node.js ORM for Postgres
- [PostgreSQL](https://www.postgresql.org/) - pen Source Relational Database
- [Sweetalert2](https://sweetalert2.github.io/) - JavaScript's PopUp Boxes


## Authors

- **M Rizki** - [https://github.com/emrizki](https://github.com/emrizki)

## License 📄

This project is licensed under the ISC License 
