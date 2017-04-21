# npmdoc-reggie

#### api documentation for  reggie (v0.2.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-reggie.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-reggie) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-reggie.svg)](https://travis-ci.org/npmdoc/node-npmdoc-reggie)

#### An experimental light weight alternative to a full blown npm registry

[![NPM](https://nodei.co/npm/reggie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reggie)

- [https://npmdoc.github.io/node-npmdoc-reggie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reggie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reggie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reggie/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-reggie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-reggie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Mike Brevoort <mike@brevoort.com>",
    "name": "reggie",
    "description": "An experimental light weight alternative to a full blown npm registry",
    "version": "0.2.1",
    "bin": {
        "reggie": "./client.js",
        "reggie-server": "./server.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/mbrevoort/node-reggie.git"
    },
    "dependencies": {
        "optimist": "~0.3.4",
        "restify": "~2.5.1",
        "mkdirp": "~0.3.4",
        "request": "~2.11.1",
        "npm": "~1.1.71",
        "tar": "~0.1.17",
        "rimraf": "~2.0.2",
        "semver": "~1.0.14",
        "pkginfo": "~0.2.3",
        "read-package-json": "~0.1.5",
        "async": "~0.1.22",
        "sha": "~1.0.1",
        "cookies": "~0.3.6"
    },
    "devDependencies": {
        "mocha": "latest",
        "chai": "latest",
        "debug": "~0.7.2",
        "ini": "~1.1.0",
        "proxyquire": "~0.5.1",
        "supertest": "~0.9.0"
    },
    "optionalDependencies": {},
    "engines": {
        "node": "> 0.6"
    },
    "scripts": {
        "test": "mocha -R spec",
        "start": "node server.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
