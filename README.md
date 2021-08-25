# is-zone

> Return true if the given value is zone.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save is-zone
```

## Usage

```js
var isZone = require('is-zone');

isZone(0);
//=> false
isZone(null);
//=> false
isZone("2");
//=> false
isZone("zone");
//=> true
```