# node-template

clone the repo locally\
\
cd into /node-template\
\
open in vscode      ```code .```\
\
initialize npm      ```npm init```\
\
install express     ```npm install express```\
\
install nodemon     ```npm install nodemon```\
\
inside of package.json change the scripts section to:

`"scripts": {
    "start": "node app.js",
    "dev": "nodemon app.js",
    "test": "echo \"Error: no test specified\" && exit 1"
},`

run the server      ```npm run dev```
