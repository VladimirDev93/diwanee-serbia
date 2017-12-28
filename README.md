# Diwanee Serbia FE TEST

[![Greenkeeper badge](https://badges.greenkeeper.io/VladimirDev93/diwanee-serbia.svg)](https://greenkeeper.io/)

# Prerequisites 
- `NodeJS ( >= 8.x )`
- `npm ( >= 5.x )`

# Installation
```bash
~$ npm i 
```

This will install the following **npm** modules:
- `Babel-CLI` ***a tool that is used for Babel modules***
- `Babel ES6 preset` ***module that transpiles ES6 code to ES5 so that the older browsers can support the app***
- `Lite-server` ***for serving the app on local server***

# Usage

After you have successfuly installed the application, run the following command to **preview**
the application
```bash
~$ npm run start
```

This will launch your default browser, run the server and host the applciation on `http://localhost:3000`

To make changes to `JavaScript` file, navigate to `/src/js/app.js`, write your code and then run
```bash
~$ npm run transpile
```