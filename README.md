### 1- terminal npm init
### 2- terminal npm i @babel/cli @babel/core @babel/polyfill @babel/preset-env --save-dev
### 3- create file called .babelrc (configuration file)
### 4- .babelrc -> { "presets": ["@babel/preset-env"] }
### 5- create file called src
### 6- create js files inside of src that we want to compile
### 7- package.json scripts -> "build": "babel src -d lib"
### 8- terminal npm run build (this will search our build command inside of our node_modules, not search in global)
### 9- check lib file
