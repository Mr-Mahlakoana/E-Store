# Mern stack E-Commerce website

This is a Mern (Mongodb, Express, React, Nodejs) stack e-commerce web app

## Demo Website

👉 Demo : 

[![IMAGE ALT TEXT HERE]()

## Tech stack

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- React: Components, Props, Events, Hooks, Router, Axios
- Redux: Store, Reducers, Actions
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github,
- Deployment: Heroku


## Run Locally

### 1. Clone repo


### 2. Setup MongoDB
 - Download and Install it from [mongodb.com](https://www.mongodb.com/try/download/community)

### 3. Create .env file
- Create .env file in project folder
- Enter these lines to that:

```
MONGODB_URL=mongodb://localhost/databasename
JWT_SECRET=somethingsecret
PAYPAL_CLIENT_ID="your paypal client id" or sb
```

### 4. Run Backend

```
$ npm install
$ npm run build
$ npm start
```

### 5. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 6. Create Admin User

- Run this on chrome: http://localhost:5000/api/users/createadmin
- Note admin email and password


