### `Steps for opening a nodeJS Project from scratch`

1 Install Node Js and along with install NPM
2 After installation open the project in the IDE and in the terminal write a command called npm install
3 Npm install would create a folder called node modules where all the nodes mentioned in the pakage.json would be installed.
4 If you face an error called  'error:03000086:digital envelope routines::initialization error'
Add the following script in pakage.json file: 
"scripts": {
    "start": "set SET NODE_OPTIONS=--openssl-legacy-provider && react-scripts start",
    "build": "set SET NODE_OPTIONS=--openssl-legacy-provider && react-scripts build"
}
5 If everything works fine run npm start in the terminal and then the server should start and you should be redirected to browser. 
6 If you want to build the project for production then just type npm build. 
