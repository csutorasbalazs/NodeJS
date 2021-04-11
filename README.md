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

# add "dev":"webpack" at the end of scripts

