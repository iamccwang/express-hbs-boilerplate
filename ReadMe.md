# HTML Boilerplate 

Make a boilerplate to start a express web app project easier.

## Install Dev Tool Packages

Initialize npm and install development tools
```
npm init
```

Install expressjs
```
npm install --save express
```

Install expressjs view engine hbs
```
npm install --save hbs
```

Install nodemon
```
npm install --save-dev nodemon
```

## Create Folder Structure
```
├── ...
├── node_modules            # node app
├── public                  # public content folder
│   ├── css                 # client side css files
│   ├── img                 # client side image files
│   ├── js                  # client side js file
├── src                     # source content folder
│   ├── utils               # server side js files
│   └── app.js              # start the app
├── template                # html template
│   ├── partials            # partials' html files
│   └── views               # pages' html files
├── package.json            
├── package-lock.json
├── ReadMe.md          
├── webpack.config.js       
└── ...
```

## How to work on this boilerplate

Run dev-server to develop web app
```
npm run dev-server 
```

Run start to launch web app
```
npm run start
```