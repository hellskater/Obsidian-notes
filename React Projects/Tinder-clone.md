# Tech stack
- MERN stack
- Will only use firebase to host the app, everything else we will build on our own
- Material UI
- heroku


# Command line installs
- Install node js and `npx create-react-app tinder-clone`
- Go to firebase and create new project, register the project
- `npm install @material-ui/core` and `npm install @material-ui/icons`
- `npm i react-tinder-card`
- In the tinder-backend folder, `npm init`, in entry point `server.js`
- In package.json of backend, enter `"type": "module"` and under scripts add `"start": "node server.js"`
- `npm i express mongoose`
- `npm i -g nodemon` and `nodemon server.js`
- `npm i cors`
- In front-end `npm i axios`
- Go to heroku and create new app
- `npm i -g heroku`
- Backend deployed in heroku and frontend deployed in firebase

---
- `npm i react-router-dom`

### Setting up MongoDB
- mongodb.com => New project
- Database access => create user => admin and "PtESWtfpWMmq07s5"
- Network access => allow access from anywhere
- Go to database and connect and copy the application url and add the config to your server.js

# Bugs
- useNewUrlParser, useUnifiedTopology, useFindAndModify, and useCreateIndex are no longer supported options. Mongoose 6 always behaves as if useNewUrlParser, useUnifiedTopology, and useCreateIndex are true, and useFindAndModify is false. Please remove these options from your code.
 ![[Pasted image 20210912160701.png]]