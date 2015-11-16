# truthy

[![npm][npm-image]][npm-url]
[![travis][travis-image]][travis-url]

[npm-image]: https://img.shields.io/npm/v/truthy.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/truthy
[travis-image]: https://img.shields.io/travis/bcomnes/truthy.svg?style=flat-square
[travis-url]: https://travis-ci.org/bcomnes/truthy


Determines if something should be considered a synonym for `true`.

A modularized version of the `truthy` function found in [*Functional Javascript*](http://shop.oreilly.com/product/0636920028857.do) by [Michael Fogus](http://blog.fogus.me/).

## Install

```
npm install truthy
```

## Usage

```js
var truthy = require('truthy')
truthy(false) // false
truthy(undefined) // false
truthy(0) // true
truthy('') // true
```

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## Related

- [`existy`](https://www.npmjs.com/package/existy)

## References

- [*Functional Javascript*](http://shop.oreilly.com/product/0636920028857.do) by [Michael Fogus](http://blog.fogus.me/)
- ["this is my best module"](https://twitter.com/substack/status/469024887949242368) - substack

## License

[ISC](LICENSE)
