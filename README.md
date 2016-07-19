# Meganote

A simple, multi-user note-taking app that saves notes in HTML and plain text.

Based on the curriculum for [Xtern Bootcamp 2016](http://bootcamp16.getfretless.com/).

> **NOTE:** This is the front-end only. For the corresponding API, see [Meganote Server](personal github for meganote).

## Technical Overview

* [Angular J 1.x](https://angularjs.org/)
* [UI Router](https://github.com/angular-ui/ui-router)

In development:

* [ECMAScript 2015 (ES6)](http://es6-features.org/)
* [Babel](https://babeljs.io/) - convert ES6 to ES5
* [NPM](https://www.npmjs.com/) - for development dependencies
* [Bower](https://bower.io/) - for dependencies
* [Gulp](https://www.npmjs.com/package/gulp) - build system

## Getting Started

> Meganote uses NPM to manage development dependencies, so install [Node](http://nodejs.org/en/) if necessary.

To get started, clone the repository and run 'npm start'.

```
 $ git clone <this repository>
 $ cd <this project folder>
 $ npm start
```

This will install dependencies and starta a web server on port 8000

To change the URL of the API ('localhost:3030' by default), edit 'app/constants.js'.

## Deployment

To deploy Meganote, copy the contents fo the 'app' folder to your remote server.
