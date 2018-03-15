# Mindzcloud

One Paragraph of project description goes here

### Prerequisites

What frameworks you need before cloning the project and how to install them

``` bash
* nodejs

# Windows, follow the below link
http://blog.teamtreehouse.com/install-node-js-npm-windows

# Linux based OS
https://nodejs.org/en/download/package-manager/

* Vue CLI

# install vue-cli using command prompt or terminal
npm install --global vue-cli

```

### Installing

A step by step series of examples that tell you have to get a development env running

``` bash

# clone the project
git clone project-git-link

# install dependencies
npm install

# naviagte to project-name folder
cd project-name

# serve with hot reload at localhost:8080
npm run dev

```

## Running the app using node server

``` bash

# build for production with minification
npm run build

# serve with hot reload at localhost:5000
node server.js

```

## Deployment on heroku server

``` bash
* First time deployment

heroku create projectname
heroku config:set NODE_ENV=production --app projectname
npm run build
heroku git:remote --app projectname

# ensure /dist/ is commented in .gitignore file before deploying using git

git add .
git commit -a -m "message"
git push heroku master

* Posting updates

git add -A
git commit -m "message"
git push -f heroku

```

## Built With

* [Vuejs] - open-source progressive JavaScript framework for building user interfaces.
* [Nodejs] - open-source, cross-platform JavaScript run-time environment for executing JavaScript code server-side.

## Version

2.0

## Authors

* **Swayam Chuoksey**
* **Sneha Shah**
* **Ankit Guddewala**

## License

This project is licensed under the Mindzcloud License
