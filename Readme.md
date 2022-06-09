# setting up the server[express]

## npm init -y
package.json


## install dependencies [yarn add]
express, mongoDB : database
, dotenv : store variables
, jsonwebtoken : jwt is used to generate token
,bcrypt: hash/encrypt and decrypt password
 and cors : authenticate the header

## components 
index.js
models/schema
controllers : CRUD
routes localhost: PORT/create, /read,/ update
config :
middleware**

# import [file, dependency]

const function/package[name] =  require(path/full-package[name])

Example: [import-express-package] const express = require("express")
Example: [import from a file]
const {createUser, updateUser} = require("../controllers/userControllers.js)

# export [function from a file]