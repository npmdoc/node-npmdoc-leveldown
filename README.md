# npmdoc-leveldown

#### basic api documentation for  [leveldown (v1.6.0)](https://github.com/level/leveldown)  [![npm package](https://img.shields.io/npm/v/npmdoc-leveldown.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-leveldown) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-leveldown.svg)](https://travis-ci.org/npmdoc/node-npmdoc-leveldown)

#### A Node.js LevelDB binding, primary backend for LevelUP

[![NPM](https://nodei.co/npm/leveldown.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/leveldown)

- [https://npmdoc.github.io/node-npmdoc-leveldown/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-leveldown/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-leveldown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-leveldown/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-leveldown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-leveldown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/level/leveldown/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "John Chesley",
            "url": "https://github.com/chesles/"
        },
        {
            "name": "Jake Verbaten",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Dominic Tarr",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Max Ogden",
            "url": "https://github.com/maxogden"
        },
        {
            "name": "Lars-Magnus Skog",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "David Björklund",
            "url": "https://github.com/kesla"
        },
        {
            "name": "Julian Gruber",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Paolo Fragomeni",
            "url": "https://github.com/hij1nx"
        },
        {
            "name": "Anton Whalley",
            "url": "https://github.com/No9"
        },
        {
            "name": "Matteo Collina",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Pedro Teixeira",
            "url": "https://github.com/pgte"
        },
        {
            "name": "James Halliday",
            "url": "https://github.com/substack"
        },
        {
            "name": "Gordon Hall",
            "url": "https://github.com/bookchin"
        }
    ],
    "dependencies": {
        "abstract-leveldown": "~2.6.1",
        "bindings": "~1.2.1",
        "fast-future": "~1.0.2",
        "nan": "~2.5.1",
        "prebuild-install": "^2.1.0"
    },
    "description": "A Node.js LevelDB binding, primary backend for LevelUP",
    "devDependencies": {
        "async": "^2.0.1",
        "delayed": "~1.0.1",
        "du": "~0.1.0",
        "faucet": "0.0.1",
        "iota-array": "~1.0.0",
        "lexicographic-integer": "~1.1.0",
        "mkfiletree": "~1.0.1",
        "monotonic-timestamp": "~0.0.8",
        "node-uuid": "~1.4.3",
        "optimist": "~0.6.1",
        "prebuild": "^6.0.2",
        "prebuild-ci": "^2.0.0",
        "readfiletree": "~0.0.1",
        "rimraf": "~2.5.0",
        "slump": "~2.0.0",
        "tape": "^4.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e6ec906d2995a8bffd02499f39e95988cd2b230f",
        "tarball": "https://registry.npmjs.org/leveldown/-/leveldown-1.6.0.tgz"
    },
    "gitHead": "113e0ce2f125eb5aa6915a4dba23a18445dc89a6",
    "gypfile": true,
    "homepage": "https://github.com/level/leveldown",
    "keywords": [
        "leveldb",
        "level"
    ],
    "license": "MIT",
    "main": "leveldown.js",
    "maintainers": [
        {
            "name": "rvagg"
        },
        {
            "name": "ralphtheninja"
        },
        {
            "name": "juliangruber"
        }
    ],
    "name": "leveldown",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/level/leveldown.git"
    },
    "scripts": {
        "install": "prebuild-install || node-gyp rebuild",
        "prebuild": "prebuild --all --strip --verbose",
        "rebuild": "prebuild --compile",
        "test": "(tape test/*-test.js | faucet) && prebuild-ci"
    },
    "version": "1.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
