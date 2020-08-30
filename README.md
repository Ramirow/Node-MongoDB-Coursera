##  initialize a package.json file in the node-mongo folde
npm init

## Install the Node MongoDB driver and the Assert module by typing the following at the prompt
npm install mongodb@3.0.10 --save     </br>
npm install assert@1.4.1 --save 

## Accept the standard defaults suggested until you end up with a package.json file containing the following
{
  "name": "node-mongo",
  "version": "1.0.0",
  "description": "Node MongoDB Example",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index"
  },
  "author": "Jogesh Muppala",
  "license": "ISC"
}

## repair mongodb server 
mongod --repair
## run mongodb
mongod