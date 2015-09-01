# vk-api-all-methods [![Build Status](https://travis-ci.org/dsblv/vk-api-all-methods.svg?branch=master)](https://travis-ci.org/dsblv/vk-api-all-methods)

> Just a list of all VK API (v5.37) [methods](http://vk.com/dev/methods).


## Install

```
$ npm install --save vk-api-all-methods
```


## Usage

The module is basically an instance of JavaScript `Array`, so...

```js
var allMethods = require('vk-api-all-methods');
var method = 'friends.get';

if (allMethods.indexOf(method) !== -1)
	console.log('Hurray!');
```


## License

MIT © [Dmitriy Sobolev](http://vk.com/sobo13v)
