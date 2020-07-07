## Aplicação fullstack using MongoDB, NodeJs, React e Redux
<p align="center">
  <img src="https://img.shields.io/badge/Mongoose-5.1.1-blue.svg?colorB=449a45">
  <img src="https://img.shields.io/badge/React-16.3.2-blue.svg">
  <img src="https://img.shields.io/badge/Redux-4.0.0-blue.svg?colorB=764abc">
  <img src="https://img.shields.io/badge/Nodejs-9.11.1-blue.svg?colorB=90c53f">
  <img src="https://img.shields.io/badge/Express-4.16.3-blue.svg?colorB=47535e">
  <br/>
  <img src="./doc/img/crud.gif">
</p>

#### Backend features
The Mongo database was hosted on MLab for convenience.
Gravatar for profile photo has been implemented, if the user's email has an avatar
in wordpress it is automatically saved in the bank.
Sensitive routes were protected using JWT in conjunction with passport.


#### Using
- Nodejs
  * Express
  * Nodemon - To reset the server whenever there is a change
  * Passport - To protect private broken 
  * Jwt - To protect private broken
  * Bcrypt - To Encrypt user passwords before saving to the bank
- MongoDB
  * Mongoose

#### Frontend features
React was used in conjunction with Redux and React-router to build the SPA.
Protected routes redirect to the home and are only accessible through auth.
Localstorage was used to persist the user state when reloading pages.

#### Using
- React
  * Redux - To manage the application state
  * asyncRoutes - Routes load in chunks, thus avoiding the application getting heavy on the first load
- Axios - To make HTTP requests
- Native local storage - To persist state and auth on private routes
- MaterialUI components

## How to start the application

#### Requirements

- Node.js
- NPM

### Installing the packages


Run the command below to install the dependencies:
``` bash
npm install
```

### Starting the server


Run the command below to start Nodejs and connect to the MongoDB database:
``` bash
npm run server
```


Wait for the execution and the API will be running in the Url `http://localhost:8001/api/`

The available endpoints are:
- Post - Login [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#0e46cf7d-edf9-416c-bfab-84022d8a346e)
- Post - Register [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#db625518-ec7d-41c7-9894-189322033ac6)
- Put  - Update Profile [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#ee34ae20-fe46-46f5-8666-7ed784448d65)
- Del  - Delete Account [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#1481a07f-160a-4b9c-ba95-7ceb20266b53)
- Get  - List Users [more](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq#5f812e40-7bf1-47e8-87bb-1390b2fdf70b)

[Full documentation can be found at Postman](https://documenter.getpostman.com/view/4374482/teste-fullstack/RW87p9Mq)

Leave the server running on one terminal, open another and proceed to the next step:

### Starting the React SPA

To do this, just execute the command below, and that's it! : D
``` bash
npm start
```

The application will automatically launch in the browser at Url `http://localhost:3000`

<br/>

### Copyright and license
The MIT License (MIT). Please see License File for more information.

<br/>
<br/>

<p align="center"><img src="http://www.mayor01.com/assets/img/apple-icon-180x180.png" width="35" height="35"/></p>
<p align="center">
<sub>A little project by <a href="http://www.mayor01.com/">Ojo Mayowa</a></sub>
</p>

