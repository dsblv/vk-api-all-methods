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
	console.log('Yeah!');
```


## Related

- [vk-api-open-methods](https://github.com/dsblv/vk-api-open-methods) — List of VK API methods that don't require authentication
- [vk-api-scoped-methods](https://github.com/dsblv/vk-api-scoped-methods) — Hash of VK API methods that require correct scope and scopes they require
- [vk-api-scopes](https://github.com/dsblv/vk-api-scopes) — Hash of VK API access permission codes


## License

MIT © [Dmitriy Sobolev](http://vk.com/sobo13v)
