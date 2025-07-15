# Technical-Report
# Create Backend folder
  - folder name : api
  - Initialize node - "npm init -y" (It will create package json)
  - Initialize express - "npm install express"  (import express from 'express')
  - to run file : index.js (main file)
    use import and make sure packagejson "type": "module",
    to start project "start": "node index.js" (change script)

    app.listen(8800, ()=>{
    console.log('connected to backend ')           -------             //run backend: node index.js

})                                                        

# Mongodb
 - create cluster : 
 - "npm install dotenv" (for import dotenv from "dotenv")
 - import mongoose from "mongoose"   ("npm install mongoose")

install bycrpt
npm install bcrypt   (import bcrypt from "bcryptjs";)
login and register

# To jwt
 - npm add jsonwebtoken  (import jwt from "jsonwebtoken";
)
 - to generate json web token : "openssl rand -base64 32" (here store in .env file JWT key. )
 - to add cookies : npm add cookie-parser
 - app.use(cookieParser());  (in server.js)  //import cookieParser from "cookie-parser";




https://chat.deepseek.com/a/chat/s/4108a96c-d2cf-4fea-bc4c-890049f56638
https://chatgpt.com/share/68755f49-ab08-800c-9f2f-584460b521c8

https://chatgpt.com/share/6872488d-a05c-800c-9af3-d09f37149ac5


## for frontend
- npx create-react-app frontend-new
- npm install
- npm start -- --verbose
- npx react-scripts start
