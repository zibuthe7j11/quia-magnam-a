# @zibuthe7j11/quia-magnam-a <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@zibuthe7j11/quia-magnam-a');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zibuthe7j11/quia-magnam-a
[npm-version-svg]: https://versionbadg.es/inspect-js/@zibuthe7j11/quia-magnam-a.svg
[deps-svg]: https://david-dm.org/inspect-js/@zibuthe7j11/quia-magnam-a.svg
[deps-url]: https://david-dm.org/inspect-js/@zibuthe7j11/quia-magnam-a
[dev-deps-svg]: https://david-dm.org/inspect-js/@zibuthe7j11/quia-magnam-a/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@zibuthe7j11/quia-magnam-a#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zibuthe7j11/quia-magnam-a.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zibuthe7j11/quia-magnam-a.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zibuthe7j11/quia-magnam-a.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zibuthe7j11/quia-magnam-a
[codecov-image]: https://codecov.io/gh/inspect-js/@zibuthe7j11/quia-magnam-a/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@zibuthe7j11/quia-magnam-a/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@zibuthe7j11/quia-magnam-a
[actions-url]: https://github.com/zibuthe7j11/quia-magnam-a/actions
