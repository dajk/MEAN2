[![Build Status](https://travis-ci.org/dajk/meant-stack-todo.svg?branch=master)](https://travis-ci.org/dajk/meant-stack-todo)
[![dependencies Status](https://david-dm.org/dajk/meant-stack-todo/status.svg)](https://david-dm.org/dajk/meant-stack-todo)
[![devDependencies Status](https://david-dm.org/dajk/meant-stack-todo/dev-status.svg)](https://david-dm.org/dajk/meant-stack-todo?type=dev)

This is the full stack implementation of popular __mean__ stack technologies, the last __t__ means TypeScript.
Application is fully written with TypeScript and compiled to regular JS.

It includes:

- Reactive programming __redux-like__  structure with Angular 4 and ngrx/store
- MongoDB with MongooseJS
- Node.js and ExpressJS

### Installation Guide

```bash
  1. git clone https://github.com/dajk/meant-stack-todo.git
  2. cd meant-stack-todo
  3. yarn
```


### Dev Guide

 - for development purposes, you should have installed [MongoDB](https://docs.mongodb.com/manual/installation/?jmp=footer) on your local machine and run it
 - `npm start`
 - open [http://localhost:1337](http://localhost:1337) and 🚀🚀🚀

#### Note: After any change in development mode you have to refresh the browser.


### Production: 

As you can see in `.travis.yml`, before any deploy you should build an app typing `npm run build:prod` in terminal and run the server with simple: `node server/app.js`.
