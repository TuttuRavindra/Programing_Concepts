# **AWS Full stack PROJECT**

___
## Prerequisite
1. NODE.JS
2. VS CODE
3. GIT
4. POSTMAN
5. REACT DEV TOOLS
6. REDUX DEV TOOLS

___
## VS CODE ADDONS
1. Any Bracket colorizer
2. ES7 React/Redux/GraphQL/React-native snippets
3. Any Code Formatter

___
## CDK Setup
1. Create IAM user which can interact with AWS CLI
2. npm install -g aws-cdk
3. cdk --version
4. cdk init --language typescript

___
## Backend Setup
1. Add bash terminal to the VS code.(Folder Server)
```JSON
   terminal.integrated.shell.windows": "A:\\Program FIles\\64 bit\\Git\\bin\\bash.exe"
```
2. Initialize git repo with git init.  
```BASH
   git init
```
3. Initialize node project
```NODE
   npm init
```
4. Install regular Dependencies
```NODE
   npm i express express-validator bcryptjs config gravatar jsonwebtoken mongoose request
```
5. Install Dev Dependencies
```NODE
   npm i -D nodemon concurrently
```
6. Add below script to package.json
```JSON
   "scripts": {
    "start": "node server",
    "server":"nodemon server"
  }
```
7. GIT add Commit
```GIT
   git add.
   git commit -m 'your comment'
```
8. ENV variables are inside Config file. Add your Mongo db url inside the default.json file.
   init
___
## MongoDB Setup
### ATLAS setup
1. Create Project eg: MERN.
2. Create cluster eg: MernCluster (may take some time to spin up).
3. Create user inside Database Access tab eg: MernAdmin.
4. Setup Network Access CIDR address.
5. Click on connect(inside clustertab) and copy the connection String and add to default.json.
 ```JSON
 eg: mongodb+srv://MernAdmin:<password>@merncluster.btdb6.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
 ```

 $ npm i axios react-router-dom redux react-redux redux-thunk redux-devtools-extention moment react-moment


___
## FrontEnd Setup
1. Run below command in the Client Folder
```BASH
   npm i axios react-router-dom redux react-redux redux-thunk moment react-moment node-sass@4.14.1
```
