# Installation-commands

## React
```
in terminal...
npx create-react-app (app name)
cd into the app 
yarn add react-router react-router-dom 

code . in terminal to open the app
this will get the basics set up

in your app.js at the top put:
import React, {useEffect, useState} from 'react';
import { BrowserRouter or HashRouter as Router, Link, Switch, Route} from 'react-router-dom';

in index.js: import { BrowserRouter as Router } from 'react-router-dom';
in index.js: wrap the <App /> in <Router></ Router>

#### Generate Unique Ids
yarn add uuid
import { v4 as uuid } from 'uuid';
  ex:
  const newID = uuid()
  key={uuid()}
  
#### React-Icons
npm install react-icons --save
To import into your file, use the code snippet on the website for your chosen icons
```


## Express
```
Open a terminal
Enter your desired folder
mkdir file name to create your nodejs/express project
cd into that nodejs project
use git init and yarn init to 
make your folder a node project and a git repo
touch .env .gitignore
open folder in vscode
update gitignore file to have both `node_modules and `.env` in your .gitignore ( This has to be done 100% correctly) do not make a commit until this has been done correctly
yarn add express mongoose dotenv
create your scripts object in pacakage.json (see below)
- Scripts Object

  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
  },
  
If you want to create user auth then...
yarn add jsonwebtoken
yarn add bcryptjs
import then into your index.js
  
Start coding your project
```


## Django


