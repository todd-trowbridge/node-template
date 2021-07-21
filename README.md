# node-template

1. clone the repo locally
1. cd into /node-template
1. open in vscode      ```code .```
1. initialize npm      ```npm init```
1. install express     ```npm install express```
1. install nodemon     ```npm install nodemon```
1. inside of package.json change the scripts section to:

* `"scripts": {
    "start": "node app.js",
    "dev": "nodemon app.js",
    "test": "echo \"Error: no test specified\" && exit 1"
},`

1. run the server      ```npm run dev```
