# npmdoc-how2

#### api documentation for  [how2 (v1.5.0)](https://github.com/santinic/how2)  [![npm package](https://img.shields.io/npm/v/npmdoc-how2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-how2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-how2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-how2)

#### Uses Google and Stackoverflow to find how to do things on a Unix commmand line

[![NPM](https://nodei.co/npm/how2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/how2)

- [https://npmdoc.github.io/node-npmdoc-how2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-how2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-how2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-how2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-how2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-how2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "how2",
    "author": "Claudio Santini <hireclaudio@gmail.com> (https://www.linkedin.com/in/santinic)",
    "version": "1.5.0",
    "description": "Uses Google and Stackoverflow to find how to do things on a Unix commmand line",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git@github.com:santinic/how2.git"
    },
    "keywords": [
        "how2",
        "howto",
        "man",
        "google",
        "stackoverflow",
        "stack overflow",
        "stackexchange",
        "stack exchange"
    ],
    "tags": [
        "how2",
        "howto",
        "man",
        "google",
        "stackoverflow",
        "stack overflow",
        "stackexchange",
        "stack exchange"
    ],
    "homepage": "https://github.com/santinic/how2",
    "preferGlobal": true,
    "main": "./index.js",
    "bin": {
        "how2": "./bin/how2"
    },
    "scripts": {
        "test": "mocha test",
        "start": "./bin/how2 concatenate two files"
    },
    "dependencies": {
        "blessed": "^0.1.81",
        "colors": "^1.1.2",
        "devnull": "0.0.12",
        "ent": "^2.2.0",
        "google": "^1.4.0",
        "keypress": "^0.2.1",
        "lodash": "^4.3.0",
        "marked": "0.3.5",
        "marked-terminal": "^1.6.1",
        "nconf": "^0.8.4",
        "npm-latest": "^1.0.1",
        "openurl": "^1.1.1",
        "request": "^2.69.0",
        "semver": "5.1.0",
        "simple-spinner": "0.0.5",
        "yargs": "^4.1.0"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^2.4.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
