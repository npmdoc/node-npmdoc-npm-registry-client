# npmdoc-npm-registry-client

#### basic api documentation for  [npm-registry-client (v8.2.0)](https://github.com/npm/npm-registry-client#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-registry-client.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-registry-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-registry-client.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-registry-client)

#### Client for the npm registry

[![NPM](https://nodei.co/npm/npm-registry-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-registry-client)

- [https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-registry-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me/"
    },
    "bugs": {
        "url": "https://github.com/npm/npm-registry-client/issues"
    },
    "dependencies": {
        "concat-stream": "^1.5.2",
        "graceful-fs": "^4.1.6",
        "normalize-package-data": "~1.0.1 || ^2.0.0",
        "npm-package-arg": "^3.0.0 || ^4.0.0 || ^5.0.0",
        "npmlog": "2 || ^3.1.0 || ^4.0.0",
        "once": "^1.3.3",
        "request": "^2.74.0",
        "retry": "^0.10.0",
        "semver": "2 >=2.2.1 || 3.x || 4 || 5",
        "slide": "^1.1.3"
    },
    "description": "Client for the npm registry",
    "devDependencies": {
        "negotiator": "^0.6.1",
        "nock": "^9.0.9",
        "readable-stream": "^2.1.5",
        "require-inject": "^1.4.0",
        "rimraf": "^2.5.4",
        "standard": "^9.0.0",
        "tap": "^10.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "39067d3c086db0ff8fa7cf444e9d4a785a9c07f6",
        "tarball": "https://registry.npmjs.org/npm-registry-client/-/npm-registry-client-8.2.0.tgz"
    },
    "files": [
        "lib",
        "index.js"
    ],
    "gitHead": "53c15d996ceaa39e36453c499f32adaebbba97b9",
    "homepage": "https://github.com/npm/npm-registry-client#readme",
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "iarna"
        }
    ],
    "name": "npm-registry-client",
    "optionalDependencies": {
        "npmlog": "2 || ^3.1.0 || ^4.0.0"
    },
    "repository": {
        "url": "git+https://github.com/npm/npm-registry-client.git"
    },
    "scripts": {
        "test": "standard && tap test/*.js"
    },
    "version": "8.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
