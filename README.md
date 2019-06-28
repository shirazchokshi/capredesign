
## Features / Use Cases
This Gulp Starter Kit provides a simple way of setting up a modern web development environment.
Here is a list of the current features:

- Copy HTML files from `src` to `dist` directory
- Compile Pug template files (`.pug`) from `src` to HTML files and put them inside `dist` directory
- Compile CSS preprocessor code (Sass/SCSS, Less, Stylus) to CSS
- Autoprefix and minify CSS and put it inside `dist` directory
- Compile ES6+ to ES5, concatenate JS files and minify code
- Compress and copy images into `dist` directory
- Copy dependencies specified in `package.json` from `src/node_modules` directory into `node_modules` folder inside `dist` directory
- Import dependencies into your application with ES6 modules
- Spin up local dev server at `http://localhost:3000` including auto-reloading

## Requirements
This should be installed on your computer in order to get up and running:

- [Node.js](https://nodejs.org/en/)
- [Gulp 4](https://gulpjs.com/)

## Dependencies
These [npm](https://www.npmjs.com/) packages are used in the Gulp Starter Kit:

- [@babel/core](https://www.npmjs.com/package/@babel/core)
- [@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env)
- [browser-sync](https://www.npmjs.com/package/browser-sync)
- [del](https://www.npmjs.com/package/del)
- [gulp](https://www.npmjs.com/package/gulp)
- [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)
- [gulp-babel](https://www.npmjs.com/package/gulp-babel)
- [gulp-concat](https://www.npmjs.com/package/gulp-concat)
- [gulp-clean-css](https://www.npmjs.com/package/gulp-clean-css)
- [gulp-plumber](https://www.npmjs.com/package/gulp-plumber)
- [gulp-sass](https://www.npmjs.com/package/gulp-sass)
- [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps)
- [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)
- [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)
- [webpack-stream](https://www.npmjs.com/package/webpack-stream)
- [gulp-pug](https://www.npmjs.com/package/gulp-pug)
- [gulp-less](https://www.npmjs.com/package/gulp-less)
- [gulp-stylus](https://www.npmjs.com/package/gulp-stylus)

For more information, take a look at the [package.json](package.json) file or visit the linked npm package sites.

## Getting Started
In order to get started, make sure you are meeting all requirements listed above.
Then, just go ahead and download the Gulp Starter Kit. For this, you can choose between the following options:

### `npm install && npm start`
And then you should be good to go :smile:


### What kinds of build scripts does the Gulp Starter Kit offer?
The Gulp Starter Kit offers two different build scripts:

1. `npm run build`: This is used to build all files and run all tasks without serving a development server and watching for changes.
2. `npm start`: This is the normal development script used to build all files and run all tasks, but also to serve a development server and watch for changes.

### What types of images are supported?
The following types of images are currently supported:

- PNG
- JPG / JPEG
- GIF
- SVG
- ICO (not compressed)

## **IMPORTANT: BEFORE YOU CODE** Push all of your code to a branch under your name

### If you do not already have a branch, go to your terminal and enter the following commands:

1. `git pull` your master branch needs to be up-to-date
2. create your branch locally using `git checkout -b [name_of_your_new_branch]`
3. push this branch to the repo:`git push origin -u [name_of_your_new_branch]`

## **IMPORTANT NOTES FOR WHEN YOU CODE:** Since we will be sending this code out for other people to read/edit, we need to follow good code etiquette.

1. Document **ALL** your code.
2. If you are creating new classes or ids, please name them appropriately. It will help immensely when we merge all our
3. Always remember: **Document**, *Document*, **_Document_**!
