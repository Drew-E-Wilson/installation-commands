# Installation-commands

## React
```
in terminal...
1. npx create-react-app (app name)
2. cd into the app 
3. yarn add react-router react-router-dom 

4. code . in terminal to open the app
this will get the basics set up

in your app.js at the top put:
5. import React, {useEffect, useState} from 'react';
6. import { BrowserRouter or HashRouter as Router, Link, Switch, Route} from 'react-router-dom';

7. in index.js: import { BrowserRouter as Router } from 'react-router-dom';
8. in index.js: wrap the <App /> in <Router></ Router>

#### Generate Unique Ids
9. yarn add uuid
10. import { v4 as uuid } from 'uuid';
  ex:
  const newID = uuid()
  key={uuid()}
  
#### React-Icons
11. npm install react-icons --save
To import into your file, use the code snippet on the website for your chosen icons
```


## Express
```
1. Open a terminal
2. Enter your desired folder
3. mkdir file name to create your nodejs/express project
4. cd into that nodejs project
5. use git init and yarn init to 
6. make your folder a node project and a git repo
7. touch .env .gitignore
8. open folder in code editor (vscode)
9. update gitignore file to have both `node_modules and `.env` in your .gitignore ( This has to be done 100% correctly) do not make a commit until this has been done correctly
10. yarn add express mongoose dotenv
11. create your scripts object in pacakage.json (see below)
- Scripts Object

  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
  },
  
12. If you want to create user auth then...
yarn add jsonwebtoken
yarn add bcryptjs
import then into your index.js
  
13. Start coding your project
```


## Django


