# npmdoc-nlf

#### api documentation for  [nlf (v1.4.3)](https://github.com/iandotkelly/nlf)  [![npm package](https://img.shields.io/npm/v/npmdoc-nlf.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nlf) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nlf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nlf)

#### Find licenses for a node application and its node_module dependencies

[![NPM](https://nodei.co/npm/nlf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nlf)

- [https://npmdoc.github.io/node-npmdoc-nlf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nlf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nlf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nlf/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nlf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nlf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nlf",
    "title": "Node License Finder",
    "description": "Find licenses for a node application and its node_module dependencies",
    "author": "Ian Kelly <iandotkelly@gmail.com>",
    "version": "1.4.3",
    "license": "MIT",
    "bin": {
        "nlf": "./bin/nlf-cli.js"
    },
    "homepage": "https://github.com/iandotkelly/nlf",
    "repository": {
        "type": "git",
        "url": "git://github.com/iandotkelly/nlf.git"
    },
    "dependencies": {
        "archy": "1.0.0",
        "commander": "2.9.0",
        "compare-versions": "3.0.0",
        "glob-all": "3.1.0  ",
        "read-installed": "4.0.3"
    },
    "devDependencies": {
        "gulp": "^3.9.1",
        "gulp-coverage": "^0.3.36",
        "gulp-coveralls": "^0.1.3",
        "gulp-jshint": "^2.0.0",
        "gulp-mocha": "^3.0.0",
        "jshint": "^2.9.1",
        "should": "^11.2.0"
    },
    "engines": {
        "node": ">=0.10"
    },
    "keywords": [
        "license",
        "licence",
        "checker",
        "finder",
        "audit",
        "legal",
        "dependency",
        "cli"
    ],
    "scripts": {
        "test": "gulp travis"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
