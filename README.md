# boilerplate-for-dev
Boilerplate code for javascript developments. 
***********************************************************************
**************************Boilerplate Setup*********************
*********************************************************************

1.A task manager with commonly used build tasks
2.A development server which is spinned off once you start development
3.A module bundler to convert your modular source code to a browser servable version.

1.Gulp as the task manager
2.Webpack as the module bundler and as the dev server
3.Node package manager

Steps:

**** Setup a new npm project ****
 
$ mkdir boilerplate-for-dev
$ cd boilerplate-for-dev
$ npm init

**** Install gulp and its utils/tasks ****

$ npm install gulp --save-dev
$ npm install gulp-util --save-dev
$ npm install gulp-uglify --save-dev
$ npm install gulp-concat --save-dev
$ npm install gulp-sourcemaps --save-dev


******  Install webpack and webpack dev server ******

$ npm install webpack --save-dev
$ npm install webpack-dev-server --save-dev
$ npm install webpack-stream --save-dev

*** Install babel for ES2015 ******
npm install --save-dev babel-loader
npm install --save-dev babel-core
npm install --save-dev babel-preset-es2015
npm install --save-dev babel-preset-react


******* Create necessery config files ***********

touch webpack.config.js
touch Gulpfile.js

