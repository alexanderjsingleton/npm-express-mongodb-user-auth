# User Authentication With Express and Mongo

Aiming to include these functionalities in our uberAmbulance app for proper user-registration and user-authentication derived from a Treehouse tutorial on how to build a basic Node-app for user-authentication with Express and mongoDB.

## Launch Demo

### Install MongoDB

1. Go to [mongoDB community](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x) and follow instructions for install (assuming [homebrew](https://brew.sh/) is your system package-manager). 

	* `brew tap mongodb/brew`

	* `brew install mongodb-community@4.0`

	* `brew services start mongodb-community@4.0`

2. Fire-up mongo by typing `mongo`

3. check dbs by running `show dbs`

### NPM

1. Run `npm install`.

2. Watch for bcrypt issue- make sure to modify that dependency for `"bcrypt": "^3.0.6",` in the package.json file.

3. Run `node app.js` to launch the app but preferably `nodemon` if making live-changes while conducting tests on local host.