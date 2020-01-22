# What is this project about ? 

Yet another Todo application based on Node.js & Vue.js. This repository contains backend code written in pure node.js code using MongoDB.

## Requirements

First things first, install all the required packages using the notoriously famous command : `npm install` 
Then, be sure to edit the `config/config.js` file in order to reflect your current mongodb setup. 

You're ready to go! 

## Test

You can manually add todos using curl : 

```bash
curl -H "Content-Type: application/json" -X POST -d '{"name":"Add a star to this repo"}' http://localhost:8000/todos
```

And get all your magicals todos using another curl command :

```bash
curl  http://localhost:8000/todos
```
