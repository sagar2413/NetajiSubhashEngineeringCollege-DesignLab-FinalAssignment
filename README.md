<h1 align="center">
    <b>User Registration & Login systems in<br> Node.js using MongoDB </b> 
<br>
</h1>



## What is this for?
This is a Simple User Registration & Login systems app done with Node.js Framework using MongoDB(Atlas) as the data store, Express as the routing system, Body-parser as the parser for webpage, Express-session used  to track the user's session and of course Mongoose to make interacting with Mongo from Node easy.

## Getting Started

## Running the tests

### •Registration Form:
Allows the user to register their account by filling their Email, Username, Password.

<img src="./docs/registration.PNG" height="250" width="390" style="border: 1px solid black;">

### •Login Form:
If the user has been registered on the app, can login by passing the credentials.

<img src="./docs/login.PNG" height="220" width="390" style="border: 1px solid black;">

### •Password Reset:
If the user forget his/her password, can reset by entering the registered Email id <br>and reset the password.

<img src="./docs/forgetpass.PNG" height="200" width="400" style="border: 1px solid black;">

### DataBase:
Here we use **[MongoDB Atlas(Cloud)](https://www.mongodb.com/cloud/atlas)** as the database. Here we have two collection created, named as:
- users.
- sessions.


## Prerequisites
Tools that we need to run this app:

- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***
- ***[MongoDB (Atlas)](https://www.mongodb.com/cloud/atlas)***

## Installing
```
npm install
```
## Connection to DataBase Access
At line 11 on ```./server.js``` change ***```<DB_USERNAME>```*** with your DataBase UserName & ***```<DB_PASSWORD>```*** with your DataBase Password.

## To Run the App
```
node server.js
```

The server will start Running on
+ http://localhost:3100/


## Author

| Author                | Profile Link                                       |
| --------------------- | :------------------------------------------------- |
| **Sagar Saurabh** | **[sagar saurabh](https://github.com/sagar2413)** |



