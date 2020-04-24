# JS_UI-Library-
A simple UI-library with a few components in Javascript.

This project builds a small UI Library.

The components that are added in this library are: 
tooltips, drop-downs, tabbed content and toasts that offer little notifications on top.

To create this project a Webpack BoilerPlate was used. All files inside the boilerplate was copied to the project folder.

First thing that was done:
Open terminal/gitbash and type: npm install
then: run serve

(run serve gives us the local host)

ninja-ui folder was created in src folder.
This folder contains all JS for the UI library. We then import the files we need from this ninja-ui folder to the index.js file inside the src folder.

The library CSS and Javascript was kept inside the ninja-ui folder. Hence, CSS had to be processed thourgh Webpack using a CSS load as this is in the src folder and not the dist folder.

Setting up Webpack CSS loaders:
terminal/gitbash: npm install css-loader style-loader --save-dev

(the css-loader helps webpack to collect css from a file when it's import
the style-loader adds this css to the html page.)

In the webpack config file, after the test rule, the second rule was added.

To get deployment files in dist run in terminal: npm run build


