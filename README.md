# npmdoc-git-guppy

#### api documentation for  [git-guppy (v2.1.0)](https://github.com/therealklanni/git-guppy)  [![npm package](https://img.shields.io/npm/v/npmdoc-git-guppy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-git-guppy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-git-guppy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-git-guppy)

#### Simple git-hook integration for your gulp workflows.

[![NPM](https://nodei.co/npm/git-guppy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/git-guppy)

- [https://npmdoc.github.io/node-npmdoc-git-guppy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-git-guppy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-git-guppy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-git-guppy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-git-guppy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-git-guppy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "git-guppy",
    "description": "Simple git-hook integration for your gulp workflows.",
    "homepage": "https://github.com/therealklanni/git-guppy",
    "author": "Kevin Lanni (https://github.com/therealklanni)",
    "repository": {
        "type": "git",
        "url": "https://github.com/therealklanni/git-guppy.git"
    },
    "bugs": {
        "url": "https://github.com/therealklanni/git-guppy/issues"
    },
    "license": "MIT",
    "keywords": [
        "git",
        "git-hook",
        "git-hooks",
        "gulp",
        "gulpplugin",
        "guppy"
    ],
    "main": "index.js",
    "engines": {
        "node": ">= 4"
    },
    "scripts": {
        "test": "gulp test",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "update": "updtr"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "gulp": "^3.9.1",
        "gulp-filter": "^4.0.0",
        "gulp-istanbul": "^1.0.0",
        "gulp-jshint": "^2.0.0",
        "gulp-load-plugins": "^1.2.0",
        "gulp-mocha": "^2.0.0",
        "guppy-pre-commit": "^0.3.0",
        "jshint": "^2.9.1",
        "jshint-stylish": "^2.1.0",
        "mocha": "*",
        "proxyquire": "^1.7.4",
        "semantic-release": "^4.3.5",
        "sinon": "^1.12.1",
        "sinon-chai": "^2.6.0",
        "updtr": "^0.1.10"
    },
    "dependencies": {
        "lodash": "^4.17.4",
        "map-stream": "0.0.6",
        "shelljs": "^0.6.0",
        "strip-bom": "^2.0.0"
    },
    "directories": {
        "test": "test"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
