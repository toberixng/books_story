# DEVELOPING A BOOK STORY APP

# 1. created a mMongoDB database
 - created a cluster
 - created database
 - set up the network
 - click on connect to get the Url to connect to data base

# 2. install dependencies for our application
    "connect-mongo": "^3.2.0",
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "express-handlebars": "^5.0.0",
    "express-session": "^1.17.1",
    "method-override": "^3.0.0",
    "moment": "^2.27.0",
    "mongoose": "^5.9.22",
    "morgan": "^1.10.0",
    "passport": "^0.4.1",
    "passport-google-oauth20": "^2.0.0"

# 3. updated package.json
    - updated the scripts command to show how and where our application will start
    - "scripts": {
            "start": "cross-env NODE_ENV=production node app",
            "dev": "cross-env NODE_ENV=development nodemon app"
            },

# 4. created a folder to save into our environment variable
    config(folder)
    config.env(file)

# 5. created a file called app.js, this app.js is the entry point of our application
    imported 
        - express
        - dotenv - this allow us to save all our global variable


# 6. created a file 
