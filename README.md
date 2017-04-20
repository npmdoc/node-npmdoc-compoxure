# npmdoc-compoxure

#### api documentation for  [compoxure (v2.1.18)](https://github.com/tes/compoxure)  [![npm package](https://img.shields.io/npm/v/npmdoc-compoxure.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-compoxure) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-compoxure.svg)](https://travis-ci.org/npmdoc/node-npmdoc-compoxure)

#### Composition proxy middleware for Express, allows for composition of microservices using declarations and caching.

[![NPM](https://nodei.co/npm/compoxure.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/compoxure)

- [https://npmdoc.github.io/node-npmdoc-compoxure/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-compoxure/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-compoxure/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-compoxure/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-compoxure/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-compoxure/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "compoxure",
    "version": "2.1.18",
    "description": "Composition proxy middleware for Express, allows for composition of microservices using declarations and caching.",
    "main": "index.js",
    "scripts": {
        "start": "node example/index.js",
        "lint": "jshint .",
        "coveralls": "NODE_ENV=test mocha --require blanket --reporter mocha-lcov-reporter test/unit/* test/acceptance/* | ./node_modules/coveralls/bin/coveralls.js",
        "test": "istanbul cover _mocha -- -R spec test/unit/* test/acceptance/* && istanbul check-coverage --statements 90",
        "precommit": "npm run lint; npm test"
    },
    "repository": {
        "type": "git",
        "url": "git@github.com:tes/compoxure.git"
    },
    "keywords": [
        "composition",
        "proxy"
    ],
    "author": "TES Global",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/tes/compoxure/issues"
    },
    "homepage": "https://github.com/tes/compoxure",
    "dependencies": {
        "accepts": "^1.1.0",
        "async": "^0.9.0",
        "body-parser": "^1.15.2",
        "connect-query": "^0.2.0",
        "cookie-parser": "^1.3.2",
        "html-entities": "^1.1.1",
        "htmlparser2": "^3.9.2",
        "http-status-codes": "^1.0.2",
        "lodash": "~3.6.0",
        "morgan": "^1.2.1",
        "parxer": "^2.0.3",
        "reliable-get": "^1.0.5",
        "request": "^2.39.0",
        "serve-static": "^1.8.0",
        "ware": "^1.2.0"
    },
    "devDependencies": {
        "blanket": "^1.1.6",
        "cheerio": "^0.17.0",
        "coveralls": "^2.11.1",
        "expect.js": "~0.3.1",
        "express": "^4.12.3",
        "express-device": "^0.3.11",
        "husky": "^0.11.5",
        "istanbul": "^0.3.2",
        "jshint": "^2.5.6",
        "mocha": "~1.18.2",
        "mocha-lcov-reporter": "0.0.1",
        "node-mocks-http": "^1.0.4",
        "node-uuid": "^1.4.1"
    },
    "config": {
        "blanket": {
            "pattern": "src"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
