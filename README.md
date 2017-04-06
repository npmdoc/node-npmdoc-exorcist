# api documentation for  [exorcist (v0.4.0)](https://github.com/thlorenz/exorcist)  [![npm package](https://img.shields.io/npm/v/npmdoc-exorcist.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-exorcist) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-exorcist.svg)](https://travis-ci.org/npmdoc/node-npmdoc-exorcist)
#### Externalizes the source map found inside a stream to an external `.js.map` file

[![NPM](https://nodei.co/npm/exorcist.png?downloads=true)](https://www.npmjs.com/package/exorcist)

[![apidoc](https://npmdoc.github.io/node-npmdoc-exorcist/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-exorcist_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-exorcist/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-exorcist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-exorcist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "email": "thlorenz@gmx.de",
        "url": "http://thlorenz.com"
    },
    "bin": {
        "exorcist": "./bin/exorcist.js"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/exorcist/issues"
    },
    "dependencies": {
        "minimist": "0.0.5",
        "mold-source-map": "~0.4.0",
        "nave": "~0.5.1"
    },
    "description": "Externalizes the source map found inside a stream to an external '.js.map' file",
    "devDependencies": {
        "browserify": "~10.2.0",
        "tap": "~0.4.3",
        "through2": "~0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1230ffdedd9248f42fbccf8b4a44d4cab29e3c64",
        "tarball": "https://registry.npmjs.org/exorcist/-/exorcist-0.4.0.tgz"
    },
    "engine": {
        "node": ">=0.6"
    },
    "gitHead": "2ea417707404f3b612b6ffbbbd3ba88e7393af17",
    "homepage": "https://github.com/thlorenz/exorcist",
    "keywords": [
        "source-map",
        "source",
        "map",
        "external",
        "mapfile",
        "browserify",
        "browserify-tool"
    ],
    "license": {
        "type": "MIT",
        "url": "https://github.com/thlorenz/exorcist/blob/master/LICENSE"
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "thlorenz",
            "email": "thlorenz@gmx.de"
        }
    ],
    "name": "exorcist",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/exorcist.git"
    },
    "scripts": {
        "test": "if [ -e $TRAVIS ]; then npm run test-all; else npm run test-main; fi",
        "test-0.10": " nave use 0.10 npm run test-main",
        "test-0.12": " nave use 0.12 npm run test-main",
        "test-all": "npm run test-main && npm run test-0.10 && npm run test-0.12 && npm run test-iojs",
        "test-iojs": " nave use latest npm run test-main",
        "test-main": "tap test/*.js"
    },
    "version": "0.4.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module exorcist](#apidoc.module.exorcist)



# <a name="apidoc.module.exorcist"></a>[module exorcist](#apidoc.module.exorcist)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
