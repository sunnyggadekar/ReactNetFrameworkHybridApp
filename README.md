# React .Net Framework MVC Hybrid Application

Steps to Integrate React SPA in .Net MVC Framework.

Step 1 : Create a folder in project
         ReactNetFrameworkHybridApp/ReactNetFrameworkHybrid/ReactApp

Step 2 : CMD into the folder

Step 3 : npm init
         
Step 4 : npm install --save react react-dom

Step 5 : npm install --save-dev babel-core babel-loader webpack babel-preset-env babel-preset-react

Step 6 : add webpack.config.js in ReactApp 
          ReactNetFrameworkHybridApp/ReactNetFrameworkHybrid/ReactApp/webpack.config.js

Step 7 : npm run webpack

Step 8 : inject the build js from dist folder into the view of MVC
          ReactNetFrameworkHybridApp/ReactNetFrameworkHybrid/Views/Home/About.cshtml
