# npmtest-esdoc

#### basic test coverage for  [esdoc (v0.5.2)](https://esdoc.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-esdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-esdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-esdoc.svg)](https://travis-ci.org/npmtest/node-npmtest-esdoc)

#### Good Documentation Generator For JavaScript

[![NPM](https://nodei.co/npm/esdoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/esdoc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-esdoc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-esdoc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-esdoc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-esdoc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-esdoc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-esdoc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-esdoc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-esdoc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-esdoc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-esdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-esdoc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-esdoc/build/test-report.html](https://npmtest.github.io/node-npmtest-esdoc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-esdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-esdoc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-esdoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-esdoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-esdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-esdoc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-esdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-esdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "h13i32maru"
    },
    "bin": {
        "esdoc": "out/src/ESDocCLI.js"
    },
    "bugs": {
        "url": "https://github.com/esdoc/esdoc/issues"
    },
    "dependencies": {
        "babel-generator": "6.11.4",
        "babel-traverse": "6.12.0",
        "babylon": "6.14.1",
        "cheerio": "0.22.0",
        "color-logger": "0.0.3",
        "escape-html": "1.0.3",
        "fs-extra": "1.0.0",
        "ice-cap": "0.0.4",
        "marked": "0.3.6",
        "minimist": "1.2.0",
        "taffydb": "2.7.2"
    },
    "description": "Good Documentation Generator For JavaScript",
    "devDependencies": {
        "babel-cli": "6.11.4",
        "babel-plugin-istanbul": "2.0.1",
        "babel-plugin-transform-es2015-modules-commonjs": "6.11.5",
        "babel-register": "6.11.6",
        "codecov": "1.0.1",
        "esdoc-importpath-plugin": "0.1.0",
        "eslint": "3.6.0",
        "http-server": "0.9.0",
        "mocha": "2.5.3",
        "nyc": "8.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "cbfd0b20e3d1cacc23c93c328eed987e21ba0067",
        "tarball": "https://registry.npmjs.org/esdoc/-/esdoc-0.5.2.tgz"
    },
    "engines": {
        "node": ">= 6.0.0"
    },
    "files": [
        "out/src",
        "README.md"
    ],
    "gitHead": "6681b76aa7b4676f008ead7b1f89d470e99e35c4",
    "homepage": "https://esdoc.org/",
    "keywords": [
        "jsdoc",
        "api",
        "document",
        "documentation",
        "ES6",
        "ECMAScript6",
        "ES2015",
        "ECMAScript2015",
        "ES7",
        "ECMAScript7",
        "ES2016",
        "ECMAScript2016",
        "ES8",
        "ECMAScript8",
        "ES2017",
        "ECMAScript2017",
        "proposal"
    ],
    "license": "MIT",
    "main": "out/src/ESDoc.js",
    "maintainers": [
        {
            "name": "h13i32maru"
        }
    ],
    "name": "esdoc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/esdoc/esdoc.git"
    },
    "scripts": {
        "build": "node ./script/build.js",
        "esdoc": "node ./script/esdoc.js",
        "lint": "node ./script/eslint.js",
        "site": "node ./script/site.js",
        "start": "node ./script/server.js",
        "test": "node ./script/test.js",
        "test-ci": "node ./script/test-ci.js",
        "test-prod": "node ./script/test-prod.js"
    },
    "version": "0.5.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
