# SCSS-BS4-Training

Hello, Well this one is the SCSS project with the using of 7-1 structure.
Okey! then strat how to install this project in our system:

First - Pick up the clone in your exixting code editer.

Now enter the first command which is : npm install 

after that command: npm init

after that install the scss in your project command: npm install node-sass --save -dev

If you successfully install the scss in your project, then compile your code

command: npm run compile:sass



Package.json file contents:
{
  "name": "layout_basic",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "compile:sass": "node-sass scss/main.scss css/main.css -w"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "node-sass": "^4.12.0"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/gautrohit/SCSS-BS4-Training.git"
  },
  "bugs": {
    "url": "https://github.com/gautrohit/SCSS-BS4-Training/issues"
  },
  "homepage": "https://github.com/gautrohit/SCSS-BS4-Training#readme",
  "description": ""
}

index.html

<link rel="stylesheet" type="text/css" href="CSS/main.css" />

