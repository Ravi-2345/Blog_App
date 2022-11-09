# Blogosphere

- A blogging website to create posts sharing thoughts, ideas, and experiences.
- Just create an account and compose your own blogs.
- Also get the collection of all of your posts in your profile.
- Users can also like the posts.

## signup page
![image](https://user-images.githubusercontent.com/102463812/200890223-6e0371c0-4369-4a0d-a09c-bc6183cd41ec.png)

## sign in page
![image](https://user-images.githubusercontent.com/102463812/200890325-06a4f808-fb3a-4745-99e7-a42342e5a70d.png)

## Blogosphere homepage
![image](https://user-images.githubusercontent.com/102463812/200890511-17f81c74-753e-4782-b7c8-02386c0ad019.png)

## User's Feed
![image](https://user-images.githubusercontent.com/102463812/200890657-c1b9b4db-edb8-4c3f-bc4f-65272a17bc1a.png)

## User's profile page (own)
![image](https://user-images.githubusercontent.com/102463812/200894006-9573381d-f094-44be-b0be-74b5c0cdb27c.png)
 Here the user can delete their blogs.
## other user's profile page
![image](https://user-images.githubusercontent.com/102463812/200894259-9e91b503-5440-48b1-92d9-e59a2b0f2da2.png)
Here the user doesn't have the access to delete others posts.
## Compose page
![image](https://user-images.githubusercontent.com/102463812/200893648-faefc04a-5331-4daf-953a-a3a4c4b54b71.png)

## About page 
![image](https://user-images.githubusercontent.com/102463812/200893721-78181e36-5649-4ceb-a9cf-ef91039e5bb5.png)


## TECHNOLOGY USED

![HTML](https://img.shields.io/badge/-HTML-333333?style=flat&logo=HTML5)
![CSS](https://img.shields.io/badge/-CSS-333333?style=flat&logo=CSS3&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/-JavaScript-333333?style=flat&logo=javascript)
<br>
![MongoDB](https://img.shields.io/badge/-MongoDB-333333?style=flat&logo=mongodb)
![Express](https://img.shields.io/badge/-ExpressJS-333333?style=flat&logo=express)
![Node.js](https://img.shields.io/badge/-Node.js-333333?style=flat&logo=node.js)
![Embedded JS](https://img.shields.io/badge/-Embedded%20JS-333333?style=flat&logo=ejs)
![NPM](https://img.shields.io/badge/-Npm-333333?style=flat&logo=npm&logoColor=white)
<br>
![Git](https://img.shields.io/badge/-Git-333333?style=flat&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-333333?style=flat&logo=github)
![Heroku](https://img.shields.io/badge/-Heroku-333333?style=flat&logo=heroku&logoColor=6567a5)

<br>

## NPM DEPENDENCIES

```
  "dependencies": {
    "body-parser": "^1.19.0",
    "dompurify": "^2.3.0",
    "dotenv": "^10.0.0",
    "ejs": "^3.1.6",
    "express": "^4.17.1",
    "express-session": "^1.17.2",
    "jsdom": "^16.6.0",
    "marked": "^2.1.3",
    "method-override": "^3.0.0",
    "mongoose": "^5.13.3",
    "mongoose-findorcreate": "^3.0.0",
    "passport": "^0.4.1",
    "passport-google-oauth20": "^2.0.0",
    "passport-local-mongoose": "^6.1.0"
  }
```

<br>

## LOCAL ENVIRONMENT SETUP

- Clone repository by running this command on git-bash

```
    git clone https://github.com/<your user-name>/Blog_App.git
```

- Install Dependencies using

```
    npm install
```

- Run this command when in root directory to make `.env` file

```
    touch .env
```

- Add this to `.env` file
  - Please Note, the ATLAS_URI is not the database link of MongoDB Atlas, its just the variable name. The URL is for local use only.

```
    SECRET=thisIsMySecret
    ATLAS_URI=mongodb://localhost:27017/postblogDB
```

- Testing : Run this command on your terminal/ bash to start the Mongo server on port 27017(default).

```
    mongod
```

- Run this command to start the project.

```
    node app.js
```

- Open link to view the website in your browser window if it doesn't open automatically.

```
    http://localhost:3000/
```

- That's all, now just Sign Up to MyBlog and compose your own posts.
  <br>
  <br>

## CONTRIBUTING

This project is open for contributions so Pull requests and Issues are welcome.
# Blog_App
# Blogosphere
