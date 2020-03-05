# Lonero IDE
`npm install lonero-ide`  

This is the official IDE for Lonero. In order to start, make sure you have yarn installed and NVM as well as Node version 10.  
Run the following:
```
$ nvm install 10
$ nvm use 10
$ npm install
$ yarn build
$ yarn theia start
```
In order to shut down, run: `kill $(lsof -t -i:3000)`  
The default port this uses is 3000.