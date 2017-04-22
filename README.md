# npmdoc-wagner-core

#### api documentation for  [wagner-core (v0.2.0)](https://github.com/vkarpov15/wagner-core#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-wagner-core.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wagner-core) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wagner-core.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wagner-core)

#### Dependency injector and DI-based async framework for writing modular, durable server code.

[![NPM](https://nodei.co/npm/wagner-core.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wagner-core)

- [https://npmdoc.github.io/node-npmdoc-wagner-core/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wagner-core/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wagner-core/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wagner-core/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wagner-core/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wagner-core/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Valeri Karpov"
    },
    "bugs": {
        "url": "https://github.com/vkarpov15/wagner-core/issues"
    },
    "dependencies": {
        "get-parameter-names": "0.2.0",
        "underscore": "1.5.2"
    },
    "description": "Dependency injector and DI-based async framework for writing modular, durable server code.",
    "devDependencies": {
        "acquit": "0.0.3",
        "istanbul": "0.3.2",
        "jscs": "1.9.0",
        "mocha": "2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5405cc71e4eb49e7832aacaab632441c7fa55c30",
        "tarball": "https://registry.npmjs.org/wagner-core/-/wagner-core-0.2.0.tgz"
    },
    "gitHead": "5a131a1796bd7ee369effd8ca128073b38efb783",
    "homepage": "https://github.com/vkarpov15/wagner-core#readme",
    "jscsConfig": {
        "preset": "airbnb",
        "requireMultipleVarDecl": null,
        "disallowMultipleVarDecl": true
    },
    "license": "Apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "vkarpov15"
        }
    ],
    "name": "wagner-core",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/vkarpov15/wagner-core.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*",
        "test": "mocha ./test/*.test.js"
    },
    "version": "0.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
