# Chat Application

A simple chat application featuring multiple chat rooms built upon socket messaging concept.
<br/>

## Deployed At:
[tejasweatherapplication.herokuapp.com](https://tejasweatherapplication.herokuapp.com/)


## Setup the Project

1. Install NodeJS in your machine

2. Install node modules

   ```
   $ cd chat-app\
   $ npm i
   ```
   
3. Project structure

    1. **Root**

       **./**

       ├── <u>`public`</u> HTML, JS, CSS files
       
       ├── <u>`src`</u> NodeJS APIs

       ├── `package.json` package manager file

       ├── `package-lock.json` package manager file

       ├── `.gitignore` list of files and folders to be ignored in git

       ├── `README.md` Instruction file
    
    2. **/public**
        
        **./**

       ├── <u>`css`</u> css files 

       ├── `img/favicon.io` chat icon

       ├── `js/chat.js` file to handle socket event
       
       ├── `chat.html` chatting page

       ├── `index.html` login page
    
    3. **/src**

       **./**
       
       ├── <u>`utils/messages`</u> file to decorate message

       ├── <u>`utils/users.js`</u> file to manipulate user's data

       ├── <u>`index.js`</u> file to initialize app
        

## Run the Project

* Go to project (chat-app) directory in terminal and run the command

   ```
   npm run start 
   ```

  // will run on localhost:3000

<hr>
