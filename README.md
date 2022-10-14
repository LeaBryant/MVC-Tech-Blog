# MVC-Tech-Blog
## Purpose
CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. 

## User Story

```md
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Table of Contents
- [Tools](#tools)
- [Demo](#demo)
- [Installation](#installation)


## Tools
Your application’s folder structure must follow the Model-View-Controller paradigm. You’ll need to use the [express-handlebars](https://www.npmjs.com/package/express-handlebars) package to implement Handlebars.js for your Views, use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect to a MySQL database for your Models, and create an Express.js API for your Controllers.

You’ll also need the [dotenv package](https://www.npmjs.com/package/dotenv) to use environment variables, the [bcrypt package](https://www.npmjs.com/package/bcrypt) to hash passwords, and the [express-session](https://www.npmjs.com/package/express-session) and [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize) packages to add authentication.

## Installation
In a terminal run,

```
git clone repo
```

This will get you a local copy on your machine. Then type,

```
cd MVC-Tech-Blog
```

Press enter. After that type,

```
npm i
```

Your computer will gather all the dependencies for this application. You can then type, 

```
npm start
```

In your terminal to start a server running this application. In the browser you can type in, 

```
http://localhost:3001/
```

To visit a copy of this application running on your computer.

## Demo
Unavaible


# Developers 
- [Lea Bryant](https://github.com/LeaBryant)