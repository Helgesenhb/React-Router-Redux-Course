Install npm by installing NodeJs

Initialize a new empty project
## npm init ##

Install babel compiler etc
## npm install @babel/cli @babel/core @babel/polyfill @babel/preset- env --save-dev

Create .babelrc file and add the following content
## {
##    "presets": ["@babel/preset-env"]
## }

Transpile all js-files in src-folder into the lib-folder
## babel src --out-dir lib

Create a .browserlist file 
OR
Add browserlist to package.json
##

