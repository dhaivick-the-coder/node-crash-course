# Node Crash Course

- **Intro:** https://www.w3schools.com/nodejs/nodejs_intro.asp

## Node Package Manager

- package.json(dependencies)
- package-lock.json(tracks all dependencies)
- **npm scripts**: run tasks, present in package.json.
- **npm init [-y]**: generates package.json file.
- **npm i [-S] packageName**: installs package locally.
- **npm i -g packageName**: installs package globally.
- **npm i -D packageName**: installs a dev dependency.
- **npm r (or) un packageName**: uninstall a package.
- **npm up**: updates npm packages.
- **npm help commandName**: provides details regarding command, eg: npm help i.
- **node --version**
- **npm --version**
- **node (REPL)**
- **node filename.js**
- **Cmd+C (exit)**
- **npm t:** npm test
- **npm it:** npm install && npm test

## Packages:

- **Inbuilt packages:** path, fs, os, url, http, eventemitter etc.
- **Third party packages:** installed via npm.

## Including packages and files in code

- const path = require(‘path’)
- module.exports = myFile; (or) exports.myFile = () => {}
- const myFile = require(‘./myFile’)
- Note:
  - **./:** File in current directory
  - **../:** File in parent directory
  - **\_\_dirname:** gives name of directory in which file exists.
  - **\_\_filename:** gives name of file and directory in which file exists.

## Useful Links

- http://johnny-five.io
- https://stateofjs.com
- https://nodejs.org/en/download/
