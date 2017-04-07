# api documentation for  [leveldown (v1.6.0)](https://github.com/level/leveldown)  [![npm package](https://img.shields.io/npm/v/npmdoc-leveldown.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-leveldown) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-leveldown.svg)](https://travis-ci.org/npmdoc/node-npmdoc-leveldown)
#### A Node.js LevelDB binding, primary backend for LevelUP

[![NPM](https://nodei.co/npm/leveldown.png?downloads=true)](https://www.npmjs.com/package/leveldown)

[![apidoc](https://npmdoc.github.io/node-npmdoc-leveldown/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-leveldown_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-leveldown/build/apidoc.html)

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
            "email": "r@va.gg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "John Chesley",
            "email": "john@chesl.es",
            "url": "https://github.com/chesles/"
        },
        {
            "name": "Jake Verbaten",
            "email": "raynos2@gmail.com",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Dominic Tarr",
            "email": "dominic.tarr@gmail.com",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Max Ogden",
            "email": "max@maxogden.com",
            "url": "https://github.com/maxogden"
        },
        {
            "name": "Lars-Magnus Skog",
            "email": "ralphtheninja@riseup.net",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "David Björklund",
            "email": "david.bjorklund@gmail.com",
            "url": "https://github.com/kesla"
        },
        {
            "name": "Julian Gruber",
            "email": "julian@juliangruber.com",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Paolo Fragomeni",
            "email": "paolo@async.ly",
            "url": "https://github.com/hij1nx"
        },
        {
            "name": "Anton Whalley",
            "email": "anton.whalley@nearform.com",
            "url": "https://github.com/No9"
        },
        {
            "name": "Matteo Collina",
            "email": "matteo.collina@gmail.com",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Pedro Teixeira",
            "email": "pedro.teixeira@gmail.com",
            "url": "https://github.com/pgte"
        },
        {
            "name": "James Halliday",
            "email": "mail@substack.net",
            "url": "https://github.com/substack"
        },
        {
            "name": "Gordon Hall",
            "email": "gordonh@member.fsf.org",
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
            "name": "rvagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "ralphtheninja",
            "email": "ralphtheninja@riseup.net"
        },
        {
            "name": "juliangruber",
            "email": "julian@juliangruber.com"
        }
    ],
    "name": "leveldown",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "1.6.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module leveldown](#apidoc.module.leveldown)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>chained_batch (db)](#apidoc.element.leveldown.chained_batch)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>destroy (location, callback)](#apidoc.element.leveldown.destroy)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>iterator (db, options)](#apidoc.element.leveldown.iterator)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>repair (location, callback)](#apidoc.element.leveldown.repair)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>super_ (location)](#apidoc.element.leveldown.super_)
1.  object <span class="apidocSignatureSpan">leveldown.</span>chained_batch.prototype
1.  object <span class="apidocSignatureSpan">leveldown.</span>iterator.prototype
1.  object <span class="apidocSignatureSpan">leveldown.</span>super_.prototype

#### [module leveldown.chained_batch](#apidoc.module.leveldown.chained_batch)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>chained_batch (db)](#apidoc.element.leveldown.chained_batch.chained_batch)
1.  [function <span class="apidocSignatureSpan">leveldown.chained_batch.</span>super_ (db)](#apidoc.element.leveldown.chained_batch.super_)

#### [module leveldown.chained_batch.prototype](#apidoc.module.leveldown.chained_batch.prototype)
1.  [function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_clear (key)](#apidoc.element.leveldown.chained_batch.prototype._clear)
1.  [function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_del (key)](#apidoc.element.leveldown.chained_batch.prototype._del)
1.  [function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_put (key, value)](#apidoc.element.leveldown.chained_batch.prototype._put)
1.  [function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_write (options, callback)](#apidoc.element.leveldown.chained_batch.prototype._write)

#### [module leveldown.iterator](#apidoc.module.leveldown.iterator)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>iterator (db, options)](#apidoc.element.leveldown.iterator.iterator)
1.  [function <span class="apidocSignatureSpan">leveldown.iterator.</span>super_ (db)](#apidoc.element.leveldown.iterator.super_)

#### [module leveldown.iterator.prototype](#apidoc.module.leveldown.iterator.prototype)
1.  [function <span class="apidocSignatureSpan">leveldown.iterator.prototype.</span>_end (callback)](#apidoc.element.leveldown.iterator.prototype._end)
1.  [function <span class="apidocSignatureSpan">leveldown.iterator.prototype.</span>_next (callback)](#apidoc.element.leveldown.iterator.prototype._next)
1.  [function <span class="apidocSignatureSpan">leveldown.iterator.prototype.</span>seek (target)](#apidoc.element.leveldown.iterator.prototype.seek)

#### [module leveldown.super_](#apidoc.module.leveldown.super_)
1.  [function <span class="apidocSignatureSpan">leveldown.</span>super_ (location)](#apidoc.element.leveldown.super_.super_)

#### [module leveldown.super_.prototype](#apidoc.module.leveldown.super_.prototype)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_chainedBatch ()](#apidoc.element.leveldown.super_.prototype._chainedBatch)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_checkKey (obj, type)](#apidoc.element.leveldown.super_.prototype._checkKey)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_isBuffer (obj)](#apidoc.element.leveldown.super_.prototype._isBuffer)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_serializeKey (key)](#apidoc.element.leveldown.super_.prototype._serializeKey)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_serializeValue (value)](#apidoc.element.leveldown.super_.prototype._serializeValue)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_setupIteratorOptions (options)](#apidoc.element.leveldown.super_.prototype._setupIteratorOptions)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>approximateSize (start, end, callback)](#apidoc.element.leveldown.super_.prototype.approximateSize)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>batch (array, options, callback)](#apidoc.element.leveldown.super_.prototype.batch)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>close (callback)](#apidoc.element.leveldown.super_.prototype.close)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>del (key, options, callback)](#apidoc.element.leveldown.super_.prototype.del)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>get (key, options, callback)](#apidoc.element.leveldown.super_.prototype.get)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>iterator (options)](#apidoc.element.leveldown.super_.prototype.iterator)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>open (options, callback)](#apidoc.element.leveldown.super_.prototype.open)
1.  [function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>put (key, value, options, callback)](#apidoc.element.leveldown.super_.prototype.put)



# <a name="apidoc.module.leveldown"></a>[module leveldown](#apidoc.module.leveldown)

#### <a name="apidoc.element.leveldown.chained_batch"></a>[function <span class="apidocSignatureSpan">leveldown.</span>chained_batch (db)](#apidoc.element.leveldown.chained_batch)
- description and source-code
```javascript
function ChainedBatch(db) {
  AbstractChainedBatch.call(this, db)
  this.binding = db.binding.batch()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.destroy"></a>[function <span class="apidocSignatureSpan">leveldown.</span>destroy (location, callback)](#apidoc.element.leveldown.destroy)
- description and source-code
```javascript
destroy = function (location, callback) {
  if (arguments.length < 2)
    throw new Error('destroy() requires 'location' and 'callback' arguments')

  if (typeof location != 'string')
    throw new Error('destroy() requires a location string argument')

  if (typeof callback != 'function')
    throw new Error('destroy() requires a callback function argument')

  binding.destroy(location, callback)
}
```
- example usage
```shell
...
  * <a href="#leveldown_approximateSize"><code><b>leveldown#approximateSize()</b></code></a>
  * <a href="#leveldown_compactRange"><code><b>leveldown#compactRange()</b></code></a>
  * <a href="#leveldown_getProperty"><code><b>leveldown#getProperty()</b></code></a>
  * <a href="#leveldown_iterator"><code><b>leveldown#iterator()</b></code></a>
  * <a href="#iterator_next"><code><b>iterator#next()</b></code></a>
  * <a href="#iterator_seek"><code><b>iterator#seek()</b></code></a>
  * <a href="#iterator_end"><code><b>iterator#end()</b></code></a>
  * <a href="#leveldown_destroy"><code><b>leveldown.destroy()</b></code></a>
  * <a href="#leveldown_repair"><code><b>leveldown.repair()</b></code></a>


--------------------------------------------------------
<a name="ctor"></a>
### leveldown(location)
<code>leveldown()</code> returns a new **LevelDOWN** instance. 'location' is a String pointing to the LevelDB location to be opened
.
...
```

#### <a name="apidoc.element.leveldown.iterator"></a>[function <span class="apidocSignatureSpan">leveldown.</span>iterator (db, options)](#apidoc.element.leveldown.iterator)
- description and source-code
```javascript
function Iterator(db, options) {
  AbstractIterator.call(this, db)

  this.binding    = db.binding.iterator(options)
  this.cache      = null
  this.finished   = false
  this.fastFuture = fastFuture()
}
```
- example usage
```shell
...
    , AbstractIterator = require('abstract-leveldown').AbstractIterator
    , fastFuture       = require('fast-future')


function Iterator (db, options) {
  AbstractIterator.call(this, db)

  this.binding    = db.binding.iterator(options)
  this.cache      = null
  this.finished   = false
  this.fastFuture = fastFuture()
}

util.inherits(Iterator, AbstractIterator)
...
```

#### <a name="apidoc.element.leveldown.repair"></a>[function <span class="apidocSignatureSpan">leveldown.</span>repair (location, callback)](#apidoc.element.leveldown.repair)
- description and source-code
```javascript
repair = function (location, callback) {
  if (arguments.length < 2)
    throw new Error('repair() requires 'location' and 'callback' arguments')

  if (typeof location != 'string')
    throw new Error('repair() requires a location string argument')

  if (typeof callback != 'function')
    throw new Error('repair() requires a callback function argument')

  binding.repair(location, callback)
}
```
- example usage
```shell
...
  * <a href="#leveldown_compactRange"><code><b>leveldown#compactRange()</b></code></a>
  * <a href="#leveldown_getProperty"><code><b>leveldown#getProperty()</b></code></a>
  * <a href="#leveldown_iterator"><code><b>leveldown#iterator()</b></code></a>
  * <a href="#iterator_next"><code><b>iterator#next()</b></code></a>
  * <a href="#iterator_seek"><code><b>iterator#seek()</b></code></a>
  * <a href="#iterator_end"><code><b>iterator#end()</b></code></a>
  * <a href="#leveldown_destroy"><code><b>leveldown.destroy()</b></code></a>
  * <a href="#leveldown_repair"><code><b>leveldown.repair()</b></code></a>


--------------------------------------------------------
<a name="ctor"></a>
### leveldown(location)
<code>leveldown()</code> returns a new **LevelDOWN** instance. 'location' is a String pointing to the LevelDB location to be opened
.
...
```

#### <a name="apidoc.element.leveldown.super_"></a>[function <span class="apidocSignatureSpan">leveldown.</span>super_ (location)](#apidoc.element.leveldown.super_)
- description and source-code
```javascript
function AbstractLevelDOWN(location) {
  if (!arguments.length || location === undefined)
    throw new Error('constructor requires at least a location argument')

  if (typeof location != 'string')
    throw new Error('constructor requires a location string argument')

  this.location = location
  this.status = 'new'
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.leveldown.chained_batch"></a>[module leveldown.chained_batch](#apidoc.module.leveldown.chained_batch)

#### <a name="apidoc.element.leveldown.chained_batch.chained_batch"></a>[function <span class="apidocSignatureSpan">leveldown.</span>chained_batch (db)](#apidoc.element.leveldown.chained_batch.chained_batch)
- description and source-code
```javascript
function ChainedBatch(db) {
  AbstractChainedBatch.call(this, db)
  this.binding = db.binding.batch()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.chained_batch.super_"></a>[function <span class="apidocSignatureSpan">leveldown.chained_batch.</span>super_ (db)](#apidoc.element.leveldown.chained_batch.super_)
- description and source-code
```javascript
function AbstractChainedBatch(db) {
  this._db         = db
  this._operations = []
  this._written    = false
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.leveldown.chained_batch.prototype"></a>[module leveldown.chained_batch.prototype](#apidoc.module.leveldown.chained_batch.prototype)

#### <a name="apidoc.element.leveldown.chained_batch.prototype._clear"></a>[function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_clear (key)](#apidoc.element.leveldown.chained_batch.prototype._clear)
- description and source-code
```javascript
_clear = function (key) {
  this.binding.clear(key)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.chained_batch.prototype._del"></a>[function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_del (key)](#apidoc.element.leveldown.chained_batch.prototype._del)
- description and source-code
```javascript
_del = function (key) {
  this.binding.del(key)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.chained_batch.prototype._put"></a>[function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_put (key, value)](#apidoc.element.leveldown.chained_batch.prototype._put)
- description and source-code
```javascript
_put = function (key, value) {
  this.binding.put(key, value)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.chained_batch.prototype._write"></a>[function <span class="apidocSignatureSpan">leveldown.chained_batch.prototype.</span>_write (options, callback)](#apidoc.element.leveldown.chained_batch.prototype._write)
- description and source-code
```javascript
_write = function (options, callback) {
  this.binding.write(options, callback)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.leveldown.iterator"></a>[module leveldown.iterator](#apidoc.module.leveldown.iterator)

#### <a name="apidoc.element.leveldown.iterator.iterator"></a>[function <span class="apidocSignatureSpan">leveldown.</span>iterator (db, options)](#apidoc.element.leveldown.iterator.iterator)
- description and source-code
```javascript
function Iterator(db, options) {
  AbstractIterator.call(this, db)

  this.binding    = db.binding.iterator(options)
  this.cache      = null
  this.finished   = false
  this.fastFuture = fastFuture()
}
```
- example usage
```shell
...
    , AbstractIterator = require('abstract-leveldown').AbstractIterator
    , fastFuture       = require('fast-future')


function Iterator (db, options) {
  AbstractIterator.call(this, db)

  this.binding    = db.binding.iterator(options)
  this.cache      = null
  this.finished   = false
  this.fastFuture = fastFuture()
}

util.inherits(Iterator, AbstractIterator)
...
```

#### <a name="apidoc.element.leveldown.iterator.super_"></a>[function <span class="apidocSignatureSpan">leveldown.iterator.</span>super_ (db)](#apidoc.element.leveldown.iterator.super_)
- description and source-code
```javascript
function AbstractIterator(db) {
  this.db = db
  this._ended = false
  this._nexting = false
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.leveldown.iterator.prototype"></a>[module leveldown.iterator.prototype](#apidoc.module.leveldown.iterator.prototype)

#### <a name="apidoc.element.leveldown.iterator.prototype._end"></a>[function <span class="apidocSignatureSpan">leveldown.iterator.prototype.</span>_end (callback)](#apidoc.element.leveldown.iterator.prototype._end)
- description and source-code
```javascript
_end = function (callback) {
  delete this.cache
  this.binding.end(callback)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.iterator.prototype._next"></a>[function <span class="apidocSignatureSpan">leveldown.iterator.prototype.</span>_next (callback)](#apidoc.element.leveldown.iterator.prototype._next)
- description and source-code
```javascript
_next = function (callback) {
  var that = this
    , key
    , value

  if (this.cache && this.cache.length) {
    key   = this.cache.pop()
    value = this.cache.pop()

    this.fastFuture(function () {
      callback(null, key, value)
    })

  } else if (this.finished) {
    this.fastFuture(function () {
      callback()
    })
  } else {
    this.binding.next(function (err, array, finished) {
      if (err) return callback(err)

      that.cache    = array
      that.finished = finished
      that._next(callback)
    })
  }

  return this
}
```
- example usage
```shell
...
    })
  } else {
    this.binding.next(function (err, array, finished) {
      if (err) return callback(err)

      that.cache    = array
      that.finished = finished
      that._next(callback)
    })
  }

  return this
}
...
```

#### <a name="apidoc.element.leveldown.iterator.prototype.seek"></a>[function <span class="apidocSignatureSpan">leveldown.iterator.prototype.</span>seek (target)](#apidoc.element.leveldown.iterator.prototype.seek)
- description and source-code
```javascript
seek = function (target) {
  if (this._ended)
    throw new Error('cannot call seek() after end()')
  if (this._nexting)
    throw new Error('cannot call seek() before next() has completed')

  if (typeof target !== 'string' && !Buffer.isBuffer(target))
    throw new Error('seek() requires a string or buffer key')
  if (target.length == 0)
    throw new Error('cannot seek() to an empty key')

  this.cache = null
  this.binding.seek(target)
  this.finished = false
}
```
- example usage
```shell
...

if (typeof target !== 'string' && !Buffer.isBuffer(target))
  throw new Error('seek() requires a string or buffer key')
if (target.length == 0)
  throw new Error('cannot seek() to an empty key')

this.cache = null
this.binding.seek(target)
this.finished = false
}

Iterator.prototype._next = function (callback) {
var that = this
  , key
  , value
...
```



# <a name="apidoc.module.leveldown.super_"></a>[module leveldown.super_](#apidoc.module.leveldown.super_)

#### <a name="apidoc.element.leveldown.super_.super_"></a>[function <span class="apidocSignatureSpan">leveldown.</span>super_ (location)](#apidoc.element.leveldown.super_.super_)
- description and source-code
```javascript
function AbstractLevelDOWN(location) {
  if (!arguments.length || location === undefined)
    throw new Error('constructor requires at least a location argument')

  if (typeof location != 'string')
    throw new Error('constructor requires a location string argument')

  this.location = location
  this.status = 'new'
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.leveldown.super_.prototype"></a>[module leveldown.super_.prototype](#apidoc.module.leveldown.super_.prototype)

#### <a name="apidoc.element.leveldown.super_.prototype._chainedBatch"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_chainedBatch ()](#apidoc.element.leveldown.super_.prototype._chainedBatch)
- description and source-code
```javascript
_chainedBatch = function () {
  return new AbstractChainedBatch(this)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.super_.prototype._checkKey"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_checkKey (obj, type)](#apidoc.element.leveldown.super_.prototype._checkKey)
- description and source-code
```javascript
_checkKey = function (obj, type) {
  if (obj === null || obj === undefined)
    return new Error(type + ' cannot be 'null' or 'undefined'')

  if (this._isBuffer(obj) && obj.length === 0)
    return new Error(type + ' cannot be an empty Buffer')
  else if (String(obj) === '')
    return new Error(type + ' cannot be an empty String')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.super_.prototype._isBuffer"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_isBuffer (obj)](#apidoc.element.leveldown.super_.prototype._isBuffer)
- description and source-code
```javascript
_isBuffer = function (obj) {
  return Buffer.isBuffer(obj)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.super_.prototype._serializeKey"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_serializeKey (key)](#apidoc.element.leveldown.super_.prototype._serializeKey)
- description and source-code
```javascript
_serializeKey = function (key) {
  return this._isBuffer(key)
    ? key
    : String(key)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.super_.prototype._serializeValue"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_serializeValue (value)](#apidoc.element.leveldown.super_.prototype._serializeValue)
- description and source-code
```javascript
_serializeValue = function (value) {
  return this._isBuffer(value) || process.browser || value == null
    ? value
    : String(value)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.super_.prototype._setupIteratorOptions"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>_setupIteratorOptions (options)](#apidoc.element.leveldown.super_.prototype._setupIteratorOptions)
- description and source-code
```javascript
_setupIteratorOptions = function (options) {
  var self = this

  options = xtend(options)

  ;[ 'start', 'end', 'gt', 'gte', 'lt', 'lte' ].forEach(function (o) {
    if (options[o] && self._isBuffer(options[o]) && options[o].length === 0)
      delete options[o]
  })

  options.reverse = !!options.reverse
  options.keys = options.keys != false
  options.values = options.values != false
  options.limit = 'limit' in options ? options.limit : -1
  options.keyAsBuffer = options.keyAsBuffer != false
  options.valueAsBuffer = options.valueAsBuffer != false

  return options
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.leveldown.super_.prototype.approximateSize"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>approximateSize (start, end, callback)](#apidoc.element.leveldown.super_.prototype.approximateSize)
- description and source-code
```javascript
approximateSize = function (start, end, callback) {
  if (   start == null
      || end == null
      || typeof start == 'function'
      || typeof end == 'function') {
    throw new Error('approximateSize() requires valid 'start', 'end' and 'callback' arguments')
  }

  if (typeof callback != 'function')
    throw new Error('approximateSize() requires a callback argument')

  start = this._serializeKey(start)
  end = this._serializeKey(end)

  if (typeof this._approximateSize == 'function')
    return this._approximateSize(start, end, callback)

  process.nextTick(function () {
    callback(null, 0)
  })
}
```
- example usage
```shell
...

LevelDOWN.prototype._batch = function (operations, options, callback) {
  return this.binding.batch(operations, options, callback)
}


LevelDOWN.prototype._approximateSize = function (start, end, callback) {
  this.binding.approximateSize(start, end, callback)
}


LevelDOWN.prototype.compactRange = function (start, end, callback) {
  this.binding.compactRange(start, end, callback)
}
...
```

#### <a name="apidoc.element.leveldown.super_.prototype.batch"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>batch (array, options, callback)](#apidoc.element.leveldown.super_.prototype.batch)
- description and source-code
```javascript
batch = function (array, options, callback) {
  if (!arguments.length)
    return this._chainedBatch()

  if (typeof options == 'function')
    callback = options

  if (typeof array == 'function')
    callback = array

  if (typeof callback != 'function')
    throw new Error('batch(array) requires a callback argument')

  if (!Array.isArray(array))
    return callback(new Error('batch(array) requires an array argument'))

  if (!options || typeof options != 'object')
    options = {}

  var i = 0
    , l = array.length
    , e
    , err

  for (; i < l; i++) {
    e = array[i]
    if (typeof e != 'object')
      continue

    if (err = this._checkKey(e.type, 'type'))
      return callback(err)

    if (err = this._checkKey(e.key, 'key'))
      return callback(err)
  }

  if (typeof this._batch == 'function')
    return this._batch(array, options, callback)

  process.nextTick(callback)
}
```
- example usage
```shell
...

LevelDOWN.prototype._chainedBatch = function () {
  return new ChainedBatch(this)
}


LevelDOWN.prototype._batch = function (operations, options, callback) {
  return this.binding.batch(operations, options, callback)
}


LevelDOWN.prototype._approximateSize = function (start, end, callback) {
  this.binding.approximateSize(start, end, callback)
}
...
```

#### <a name="apidoc.element.leveldown.super_.prototype.close"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>close (callback)](#apidoc.element.leveldown.super_.prototype.close)
- description and source-code
```javascript
close = function (callback) {
  var self      = this
    , oldStatus = this.status

  if (typeof callback != 'function')
    throw new Error('close() requires a callback argument')

  if (typeof this._close == 'function') {
    this.status = 'closing'
    this._close(function (err) {
      if (err) {
        self.status = oldStatus
        return callback(err)
      }
      self.status = 'closed'
      callback()
    })
  } else {
    this.status = 'closed'
    process.nextTick(callback)
  }
}
```
- example usage
```shell
...

LevelDOWN.prototype._open = function (options, callback) {
  this.binding.open(options, callback)
}


LevelDOWN.prototype._close = function (callback) {
  this.binding.close(callback)
}


LevelDOWN.prototype._put = function (key, value, options, callback) {
  this.binding.put(key, value, options, callback)
}
...
```

#### <a name="apidoc.element.leveldown.super_.prototype.del"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>del (key, options, callback)](#apidoc.element.leveldown.super_.prototype.del)
- description and source-code
```javascript
del = function (key, options, callback) {
  var err

  if (typeof options == 'function')
    callback = options

  if (typeof callback != 'function')
    throw new Error('del() requires a callback argument')

  if (err = this._checkKey(key, 'key'))
    return callback(err)

  key = this._serializeKey(key)

  if (typeof options != 'object')
    options = {}

  if (typeof this._del == 'function')
    return this._del(key, options, callback)

  process.nextTick(callback)
}
```
- example usage
```shell
...

LevelDOWN.prototype._get = function (key, options, callback) {
  this.binding.get(key, options, callback)
}


LevelDOWN.prototype._del = function (key, options, callback) {
  this.binding.del(key, options, callback)
}


LevelDOWN.prototype._chainedBatch = function () {
  return new ChainedBatch(this)
}
...
```

#### <a name="apidoc.element.leveldown.super_.prototype.get"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>get (key, options, callback)](#apidoc.element.leveldown.super_.prototype.get)
- description and source-code
```javascript
get = function (key, options, callback) {
  var err

  if (typeof options == 'function')
    callback = options

  if (typeof callback != 'function')
    throw new Error('get() requires a callback argument')

  if (err = this._checkKey(key, 'key'))
    return callback(err)

  key = this._serializeKey(key)

  if (typeof options != 'object')
    options = {}

  options.asBuffer = options.asBuffer != false

  if (typeof this._get == 'function')
    return this._get(key, options, callback)

  process.nextTick(function () { callback(new Error('NotFound')) })
}
```
- example usage
```shell
...

LevelDOWN.prototype._put = function (key, value, options, callback) {
  this.binding.put(key, value, options, callback)
}


LevelDOWN.prototype._get = function (key, options, callback) {
  this.binding.get(key, options, callback)
}


LevelDOWN.prototype._del = function (key, options, callback) {
  this.binding.del(key, options, callback)
}
...
```

#### <a name="apidoc.element.leveldown.super_.prototype.iterator"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>iterator (options)](#apidoc.element.leveldown.super_.prototype.iterator)
- description and source-code
```javascript
iterator = function (options) {
  if (typeof options != 'object')
    options = {}

  options = this._setupIteratorOptions(options)

  if (typeof this._iterator == 'function')
    return this._iterator(options)

  return new AbstractIterator(this)
}
```
- example usage
```shell
...
    , AbstractIterator = require('abstract-leveldown').AbstractIterator
    , fastFuture       = require('fast-future')


function Iterator (db, options) {
  AbstractIterator.call(this, db)

  this.binding    = db.binding.iterator(options)
  this.cache      = null
  this.finished   = false
  this.fastFuture = fastFuture()
}

util.inherits(Iterator, AbstractIterator)
...
```

#### <a name="apidoc.element.leveldown.super_.prototype.open"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>open (options, callback)](#apidoc.element.leveldown.super_.prototype.open)
- description and source-code
```javascript
open = function (options, callback) {
  var self      = this
    , oldStatus = this.status

  if (typeof options == 'function')
    callback = options

  if (typeof callback != 'function')
    throw new Error('open() requires a callback argument')

  if (typeof options != 'object')
    options = {}

  options.createIfMissing = options.createIfMissing != false
  options.errorIfExists = !!options.errorIfExists

  if (typeof this._open == 'function') {
    this.status = 'opening'
    this._open(options, function (err) {
      if (err) {
        self.status = oldStatus
        return callback(err)
      }
      self.status = 'open'
      callback()
    })
  } else {
    this.status = 'open'
    process.nextTick(callback)
  }
}
```
- example usage
```shell
...
  this.binding = binding(location)
}

util.inherits(LevelDOWN, AbstractLevelDOWN)


LevelDOWN.prototype._open = function (options, callback) {
  this.binding.open(options, callback)
}


LevelDOWN.prototype._close = function (callback) {
  this.binding.close(callback)
}
...
```

#### <a name="apidoc.element.leveldown.super_.prototype.put"></a>[function <span class="apidocSignatureSpan">leveldown.super_.prototype.</span>put (key, value, options, callback)](#apidoc.element.leveldown.super_.prototype.put)
- description and source-code
```javascript
put = function (key, value, options, callback) {
  var err

  if (typeof options == 'function')
    callback = options

  if (typeof callback != 'function')
    throw new Error('put() requires a callback argument')

  if (err = this._checkKey(key, 'key'))
    return callback(err)

  key = this._serializeKey(key)
  value = this._serializeValue(value)

  if (typeof options != 'object')
    options = {}

  if (typeof this._put == 'function')
    return this._put(key, value, options, callback)

  process.nextTick(callback)
}
```
- example usage
```shell
...

LevelDOWN.prototype._close = function (callback) {
  this.binding.close(callback)
}


LevelDOWN.prototype._put = function (key, value, options, callback) {
  this.binding.put(key, value, options, callback)
}


LevelDOWN.prototype._get = function (key, options, callback) {
  this.binding.get(key, options, callback)
}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
