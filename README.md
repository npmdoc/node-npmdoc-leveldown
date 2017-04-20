# npmdoc-leveldown

#### api documentation for  [leveldown (v1.6.0)](https://github.com/level/leveldown)  [![npm package](https://img.shields.io/npm/v/npmdoc-leveldown.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-leveldown) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-leveldown.svg)](https://travis-ci.org/npmdoc/node-npmdoc-leveldown)

#### A Node.js LevelDB binding, primary backend for LevelUP

[![NPM](https://nodei.co/npm/leveldown.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/leveldown)

- [https://npmdoc.github.io/node-npmdoc-leveldown/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-leveldown/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-leveldown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-leveldown/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-leveldown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-leveldown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "leveldown",
    "description": "A Node.js LevelDB binding, primary backend for LevelUP",
    "version": "1.6.0",
    "contributors": [
        "Rod Vagg <r@va.gg> (https://github.com/rvagg)",
        "John Chesley <john@chesl.es> (https://github.com/chesles/)",
        "Jake Verbaten <raynos2@gmail.com> (https://github.com/raynos)",
        "Dominic Tarr <dominic.tarr@gmail.com> (https://github.com/dominictarr)",
        "Max Ogden <max@maxogden.com> (https://github.com/maxogden)",
        "Lars-Magnus Skog <ralphtheninja@riseup.net> (https://github.com/ralphtheninja)",
        "David Björklund <david.bjorklund@gmail.com> (https://github.com/kesla)",
        "Julian Gruber <julian@juliangruber.com> (https://github.com/juliangruber)",
        "Paolo Fragomeni <paolo@async.ly> (https://github.com/hij1nx)",
        "Anton Whalley <anton.whalley@nearform.com> (https://github.com/No9)",
        "Matteo Collina <matteo.collina@gmail.com> (https://github.com/mcollina)",
        "Pedro Teixeira <pedro.teixeira@gmail.com> (https://github.com/pgte)",
        "James Halliday <mail@substack.net> (https://github.com/substack)",
        "Gordon Hall <gordonh@member.fsf.org> (https://github.com/bookchin)"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/level/leveldown.git"
    },
    "homepage": "https://github.com/level/leveldown",
    "keywords": [
        "leveldb",
        "level"
    ],
    "main": "leveldown.js",
    "dependencies": {
        "abstract-leveldown": "~2.6.1",
        "bindings": "~1.2.1",
        "fast-future": "~1.0.2",
        "nan": "~2.5.1",
        "prebuild-install": "^2.1.0"
    },
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
    "scripts": {
        "install": "prebuild-install || node-gyp rebuild",
        "test": "(tape test/*-test.js | faucet) && prebuild-ci",
        "rebuild": "prebuild --compile",
        "prebuild": "prebuild --all --strip --verbose"
    },
    "license": "MIT",
    "gypfile": true
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
