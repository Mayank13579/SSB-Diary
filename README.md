# SSB Blo
- A blogging website to create posts sharing thoughts, ideas, and experiences.
- This website also supports Markdown to create different text styles and make your posts more readable.
- Just create an account and compose your own posts and don't forget to like other's posts 😁.
- Also get the collection of all of your posts in your profile.

<br>

https://user-images.githubusercontent.com/75828760/127818439-0672a363-6aee-4758-b35d-efd513376927.mp4

<br />



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
    git clone https://github.com/<your user-name>/POST-O-BLOG.git
```

- Run command `cd POST-O-BLOG`

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
- That's all, now just Sign Up to POST-O-BLOG and compose your own posts.
<br>
<br>



## CONTRIBUTING
This project is open for contributions so Pull requests and Issues are welcome.


