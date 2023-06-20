# FULL STACK REST API Ecommerce with React JS, Express and PostgresSQL

## Description

Backend API for an e-commerce site built with Node.js and Express
Endpoints for shopping, authentication, user accounts, and checkout
Provides setup for Postgres database

##Technologies Used
##Server
node.js 
npm 
express 
jsonwebtoken 
nodemon 
cors 

##Client
React
Bootstrap
React-router-dom

##Database
PostgresSQL

## Features
* User registration and login
* Authentication via JWT
* Email confirmation
* CRUD for blog posts
* PostgresSQL database

### Installing

```
git clone https://github.com/MariAnn85/EcommerceFullStack
cd client
npm start - start Frontend
cd server
npm run dev - start Backend

```

## Getting Started

To test the application

* Register on pgAdmin
* Create your free shared database and choose a username and password for it
* Add your username and password to the .env file (you need to create your .env file in the server of the project)
* Add the following fields with respective values to the .env file:

# Postgres Database
PGHOST=
PGUSER=
PGDATABASE=
PGPASSWORD=
PGPORT=
* Choose a random string as JWT secret or generate it in your terminal
* Copy it and place in in your .env file
* Example
TOKEN_SECRET="yourrandomlygeneratedsecret"
* Start the application
```
* Register via http://localhost:3000/auth/register with username, email, and password in the body as JSON format via Postman or any alternatives
* If successful, you should get a verification email
* Email link should look like this - http://localhost:3000/auth/user/confirm/somerandomlygeneratedjwttoken
* Opening the link will change your username confirmed field to true and show confirmed message in the response
* Login via http://localhost:3000/auth/login with the same email and password
* Your response should have a JSON token
* Place it inside the Authentication Token 
* Make a request to http://localhost:3000/products

## Authors
marin.apresyan@gmail.com
Marine Apresyan
