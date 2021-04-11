# NodeJS

PowerShell Run As Administrator
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine
Set-ExecutionPolicy -ExecutionPolicy AllSigned -Scope LocalMachine

VS Code
node -v
npm install -g http-server
http-server

Git
git --version
git init
git status
git add README.md
git log
git commit -m "Update Readme.md"
git push

NodeJS Client side
npm init
npm install jquery
npm install --save http-server

# Configura packages.json
# add "start": "http-server" at the end of scripts
npm start
npm install webpack webpack-cli --save-dev
# Configura packages.json
# looking at package.json file, you can see that the library has been added to a new section called devDependencies. This section is only for utilities that help you work with the application and not help you develop the application. Some of the things that can end up in this section are libraries that help you run things like unit tests or other developer tools.

# add "dev": "webpack --mode development" at the end of scripts
# rename scripts to src
# rename app.js to index.js
npm run dev
# compiled files are in dist filder
# use dist/main.js in index.html

# src/index.js
# import $ from 'jquery'
npm run dev
npm start

# Adding webpack-dev-server
# need to manually recompile your code . This is not an acceptable situation and you need to fix it. You can fix this by using the Webpack webserver. This will replace the server you used before. Stop the server if it is currently
npm install webpack-dev-server –save-dev

# update start script in package.json

# webpack-dev-server –mode development --open

# Here you are directing your script to use the webpack server and adding the flag -—open. This flag will open the default browser and load the index page. The added benefit to this is when you make changes to the files, it will automatically update and refresh the page. This will give you an updated version of the page every time you make an edit.

# Babel.js
# use when you want to use the most advanced features of JavaScript and still support browsers that may not yet support these features.
npm install @babel/core babel-loader @babel/preset-env -save-dev

# Adding HTML and CSS Loaders
