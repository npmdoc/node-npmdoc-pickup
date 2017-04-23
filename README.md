# npmdoc-pickup

#### api documentation for  [pickup (v5.1.1)](https://github.com/michaelnisi/pickup)  [![npm package](https://img.shields.io/npm/v/npmdoc-pickup.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pickup) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pickup.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pickup)

#### Transform RSS or Atom XML to JSON

[![NPM](https://nodei.co/npm/pickup.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pickup)

- [https://npmdoc.github.io/node-npmdoc-pickup/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pickup/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pickup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pickup/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pickup/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pickup/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pickup",
    "version": "5.1.1",
    "description": "Transform RSS or Atom XML to JSON",
    "main": "index.js",
    "directories": {
        "example": "example",
        "test": "test"
    },
    "scripts": {
        "pretest": "standard",
        "test": "tap test/*.js --cov"
    },
    "bin": {
        "pickup": "bin/cli.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/michaelnisi/pickup.git"
    },
    "keywords": [
        "rss",
        "atom",
        "xml",
        "json",
        "itunes",
        "podcast",
        "feed",
        "transform",
        "stream",
        "through",
        "streams2"
    ],
    "bugs": {
        "url": "https://github.com/michaelnisi/pickup/issues"
    },
    "homepage": "https://github.com/michaelnisi/pickup",
    "dependencies": {
        "readable-stream": "^2.1.5",
        "sax": "^1.2.1"
    },
    "devDependencies": {
        "standard": "^8.5.0",
        "tap": "^8.0.0"
    },
    "engines": {
        "node": ">=4"
    },
    "author": "Michael Nisi <michael.nisi@gmail.com> (http://troubled.pro)",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
