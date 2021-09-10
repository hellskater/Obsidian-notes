# Set-up

- Install node js and `npx create-react-app amazon-clone`
- Go to firebase and create new project, register the project and go to project options and copy the config details and create a new file named `firebase.js` in `src` folder and paste the config.
-  `npm install -g firebase-tools` install in terminal
- Delete all the test files and logo from src.
- `ctrl + j` to hide the terminal
- Install es7 snippets in vscode then rfce
- `npm i firebase`
- `firebase init` then `npm run build`(Every time you change something) then `firebase deploy`
- In the `firebase init` select hosting directory as "build"
- `npm i @stripe/stripe-js`
- `npm i @stripe/react-stripe-js`
- `npm i axios`
- Inside functions, `npm i express` then `npm i cors` then `npm i stripe`
- To emulate cloud function `firebase emulators:start`
- Create database in firestore
- `npm install moment`
- Stop the local emulator and deploy the backend `firebase deploy --only functions
- Replace the local baseURL with the one from firebase
- `firebase deploy --only hosting` To deploy the frontend
# Coding
- Install material-ui and icons
- We use BEM convention
- NO REFRESHING IN REACT
- Optional chaining
- Functions is the back-end and src is the front-end
- Check to see if git hub works