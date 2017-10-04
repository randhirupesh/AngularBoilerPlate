# AngularJS-Boilerplate
Simple AngularJS Boilerplate to kick start your new project with build tasks

# Features
* Minimal CSS styling of the view
* Gulp watch, build and local server tasks
* Responsive navigation
* Owl slider directive
* localStorage service for set, get, remove data
* queryService $http wrapper to handle calls
* Simpler and modular folder structure
* minified CSS and JS build files
* google analytics snippet

## Pre-requisites
* Install latest version of Node.js
* Install bower 
```bash
npm install -g bower
```
## Download
```bash
bower install angularjs-boilerplate
```

or

```bash
git clone https://github.com/vidyutron/AngularBoilerPlate.git
```

## 1. Setup
```bash
npm install
```
- install all npm and bower dependencies

**Note:** If `npm install` fails during dependency installation it will be likely caused by `gulp-imagemin`. In that case remove `gulp-imagemin` dependency from `package.json`, run `npm install` again and then install `gulp-imagemin` separately with following command: `npm install gulp-imagemin --save-dev`

## 2. Watch files
```bash
npm start
```
or
```bash
gulp
```

- all SCSS/HTML will be watched for changes and injected into browser thanks to BrowserSync

## 3. Build production version
```bash
npm run build
```
or
```bash
gulp build
```
- this will process following tasks:
* clean _build folder
* compile SASS files, minify and uncss compiled css
* copy and optimize images
* minify and copy all HTML files into $templateCache
* build index.html
* minify and copy all JS files
* copy fonts
* show build folder size

## 4. Start webserver without watch task
```bash
npm run server
```
or
```bash
gulp server
```

## 5. Start webserver from build folder
```bash
npm run serverbuild
```
or
```bash
gulp server-build
```

## Contact
Copyright (C) 2017 Vishal Sridhar<br>
[www.vishalsridahr.com](http://www.vishalsridahr.com)<br>
[www.github.com/vidyutron](http://www.github.com/vidyutron)<br>
Released under MIT license

## Changelog

### 1.0.0
- initial release<br>
04.10.2017
