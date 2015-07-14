# easy-cookie

A small library for setting/getting/removing cookies.


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
