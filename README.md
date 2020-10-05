##### What is this?

Simple introduction of GraphQL where mutations are implemented in one of the attribute i.e. users

#### Some inital setup

1. Make directory for the application
2. Go to the location of directory
3. Then in your cmd or vscode terminal, run npm init command
4. After that there will asking some couple of questions, we don't require to answer that so keep on hitting Enter key.
5. Now, next is installing dependencies below:

#### Required NPM dependencies along with installation command

1. Intalling express, express-graphql, graphql and lodash for that enter: npm install --save express express-graphql graphql lodash

2. Install json-server,
   enter command: npm install --save json-server

3. Install axios,
   enter command: npm install --save axios

4. Install nodemon for dynamic running our server
   enter command: npm install --save nodemon

#### Note That

Make some couple of changes in your package.JSON as like the changes made in the file you see there for running our servers.
Create the json file as like there db.json for data storage.

For GraphQL operation in browser after you run server in terminal, its always better to go through the documentation and check out the process for generating data and mutating.

##### To Run Servers

It is required to run servers i.e json-server and graphql, before to see some actions so for that use command below:

1. For json-server: npm run json:server
2. For graphql: node server.js

#### THANK YOU, Keep on LEARNING!!!
