# Tech stack
- MERN stack
- Frontend ( React, firebase hosting, Material UI, FlexBox, Ticker)
- Backend (Node.js, Express.js server, Mongodb, Hosting on Heroku, Mongoose client)

# Command line installs
- Install node js and `npx create-react-app front-end`
- Go to firebase and create new project, register the project
- `npm install @material-ui/core` and `npm install @material-ui/icons`
- `npm i react-ticker`
- **In the backend folder** `npm init` then set up the package.json file, add `start: node server.js` and `type: module`
- `npm i express mongoose` and create server.js
- `npm i nodemon`
- Perform basic Heroku deploy
- In the backend folder initialize git and add and commit and add the remote heroku path and push and build
- In frontend `npm i axios`
- `firebase login` => `firebase init` => Hosting => Public directory as "build" and it is a single page app.
- `npm run build` and `firebase deploy`

### Setting up MongoDB
- mongodb.com => New project
- Database access => create user => admin and "jM8NPOI2pgbQL1fD"
- Network access => allow access from anywhere
- Go to database and connect and copy the application url and add the config to your server.js

# Bugs
- Instead of `const port = 9000;` add `const port = process.env.PORT || 9000;`