# easy-cookie

A small library for setting/getting/removing cookies.

[![Dependency Status](https://david-dm.org/zkochan/easy-cookie/status.svg?style=flat)](https://david-dm.org/zkochan/easy-cookie)
[![Build Status](https://travis-ci.org/zkochan/easy-cookie.svg?branch=master)](https://travis-ci.org/zkochan/easy-cookie)
[![npm version](https://badge.fury.io/js/easy-cookie.svg)](http://badge.fury.io/js/easy-cookie)


## Installation

```
npm install --save easy-cookie
```


## Usage

```js
var cookie = require('easy-cookie');

cookie.set('foo', 'bar');
console.log(cooke.get('foo'));

cookie.remove('foo');
console.log(cooke.get('foo'));
```


## License

MIT
