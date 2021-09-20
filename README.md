# [FSW] - Chapter 6 Challenge 

### Challenge
1. Simple monolith dashboard using view engine (EJS) ✅
2. Super user authentication login dashboard using static data ✅
3. Create 3 table:
    - UserGame table ✅
    - UserGameBiodata table
    - UserGameHistory table
4. Connect to SQL database with method:
    - Create UserGame data
    - Read UserGame data
    - Update UserGame data
    - Delete UserGame data
5. Designing and Implementing database schema that links 3 table which UserId as Parent Key (PK)
6. RESTFUL API one endpoint with CRUD method (create, read, delete, update)
7. Database table attribute:
    - UserGame
        * email
        * username
        * password
    - UserGameBiodata
        * name
    - UserGameHistory
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

From your command line, first clone Simplefolio:

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
$ npm start
```

**NOTE**:
If your run into issues installing the dependencies with NPM, use this command:

```bash
# Install dependencies with all permissions
$ sudo npm install --unsafe-perm=true --allow-root
```
Once your server has started, go to this url `http://localhost:3000/` and you will see the website running on a Development Server:

<h2 align="center">
  <img src="https://ibb.co/q143DHZ" alt="homepage" width="100%">
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
