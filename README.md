# npmdoc-setimmediate

#### api documentation for  setimmediate (v1.0.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-setimmediate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-setimmediate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-setimmediate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-setimmediate)

#### A shim for the setImmediate efficient script yielding API

[![NPM](https://nodei.co/npm/setimmediate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/setimmediate)

- [https://npmdoc.github.io/node-npmdoc-setimmediate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-setimmediate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-setimmediate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-setimmediate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-setimmediate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-setimmediate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "setimmediate",
    "description": "A shim for the setImmediate efficient script yielding API",
    "version": "1.0.5",
    "author": "YuzuJS",
    "contributors": [
        "Domenic Denicola <d@domenic.me> (https://domenic.me)",
        "Donavon West <github@donavon.com> (http://donavon.com)",
        "Yaffle"
    ],
    "license": "MIT",
    "repository": "YuzuJS/setImmediate",
    "main": "setImmediate.js",
    "files": [
        "setImmediate.js"
    ],
    "scripts": {
        "lint": "jshint setImmediate.js",
        "test": "mocha test/tests.js",
        "test-browser": "opener http://localhost:9008/__zuul && zuul test/tests.js --ui mocha-bdd --local 9008",
        "test-browser-only": "opener http://localhost:9007/test/browserOnly/index.html && http-server . -p 9007"
    },
    "devDependencies": {
        "jshint": "^2.5.0",
        "mocha": "~1.18.2",
        "http-server": "~0.6.1",
        "opener": "^1.3",
        "zuul": "^1.6.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
