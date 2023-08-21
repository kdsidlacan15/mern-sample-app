# MERN-sample-workout-app

This is a sample **MERN CRUD** app inspired by [Net Ninja's Youtube Channel](https://www.youtube.com/@NetNinja)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)

## About

A Simple workout tracker app good for learning using the MERN stack for beginners.

## Features

- With Authenticaiton using **JWT**
- **Bcrypt** for Encryption
- React's **useReducer** for handling simple state
- MongoDB Atlas for DB.
  To Learn more about MongoDB Atlas please see [MongoDB Atlas Documentation](https://www.mongodb.com/docs/atlas/)

## Installation/Running in your local Machine

Clone Repository and enter the root folder.

```bash
$ git clone https://github.com/kdsidlacan15/mern-sample-app.git
$ cd mern-workout-app
```

From root folder Install Server packages and Run Server

### Note:

To be able to run backend server, you must setup your own .env variables. Keys for env variables needed are saved in **env-sample.txt** file inside the backend folder.

```bash
$ cd backend
$ npm install
$ npm run dev
```

From root folder Install React packages and Run

```bash
$ cd frontend
$ npm install
$ npm start
```

You can Acess the app by going to [localhost:3000](http://localhost:3000)

## Running With Docker

**Pull Backend Image**

```bash
$ docker pull kdsidlacan/workout-app-api:latest
```

**Pull Frontend Image**

```bash
$ docker pull kdsidlacan/workout-app-frontend:latest
```

**Start Application**

```bash
$ docker-compose up -d
```
