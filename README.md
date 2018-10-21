## RESTFul APIs for Hotel.
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)]()

### Tech Stack
    NodeJs
    Mysql

#### Modules Used
    "body-parser": "^1.18.3",
    "chai-http": "^4.2.0",
    "chai-json-schema": "^1.5.0",
    "dotenv": "^6.1.0",
    "express": "^4.16.4",
    "mysql": "^2.16.0",
    "winston": "^3.1.0"
    "chai": "^4.2.0",
    "mocha": "^5.2.0",
    "nodemon": "^1.18.4",
    "request": "^2.88.0"

### Setup
    - Get all the node dependencies installed.
### Database setup
    - Get Mysql installed.
    - Create database - hotel
    - Update .env file with db credential
    - Import hotel_api.sql to database. 
### APIs Documentation and Usage
- [API DOCUMENTATION](https://documenter.getpostman.com/view/3407371/RWguxHLr)
- Import `Hotel_api.postman_collection.json` collection in postman to run the APIs.

### Use Application
- [x] Browse to root folder of app via terminal.
- [x] Type `node start` to start the application.
- [x] Hit the APIs from postman collection imported ealier.

### Test Cases
- Start application using `node start`
- Browse to test folder via terminal
- Type `npm test`

Currently there are 3 test cases
> `GET` To get all the rooms available in all hotel
> `GET` To get all the rooms available with specific hotel
> `POST`To create new hotel 

### Check ERROR logs
>we are using winston module for error
>logging.
>Errors will be prinited on console and
>stored in a file name all_logs.log in logs folder.
>Errors are stored with timestamp and thier log level.
