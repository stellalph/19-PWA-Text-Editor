## 19 Progressive Web Applications (PWA) : Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline.

The URL of the GitHub repository is https://github.com/stellalph/19-PWA-Text-Editor.git and the repository name is 19-PWA-Text-Editor.

This application is deployed to Heroku and the URL of the deployed application is https://mighty-waters-80466.herokuapp.com/

## Table of Contents

* [Installation](#installation)
* [Deployment](#deployment)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Installation

* This text editor require a number of methods and store data to an IndexedDB database to be builded up.

* This application will require the installation of Node.js and various npm packages.

*   Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

*  This application will use the following npm packages:-

         - npm install express (express.js)
         - npm install --save-dev webpack (Webpack)
         - npm install webpack-dev-server --save-dev (webpack-dev-server)
         - npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         - npm install babel (Babel)
         - npm install --save-dev css-loader (CSS-loader)
         - npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
         - npm npm install idb (IndexedDB)

* Nodemon is installed as development dependency meaning that if our application ever goes in production, this package will not be included. The command to install for in this case is **npm i -D nodemon**. The purpose of this package is to watch for any changes in our files and restart the server instead of us having to do that manually ourselves.


## Deployment

Deploy to Heroku 🚀
 
https://mighty-waters-80466.herokuapp.com/

## Usage







## References

## License

This project is licensed under the terms of the MIT license.