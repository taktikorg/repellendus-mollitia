# @taktikorg/repellendus-mollitia <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has `Symbol.toStringTag` support. Supports spec, or shams.

## Example

```js
var hasSymbolToStringTag = require('@taktikorg/repellendus-mollitia');

hasSymbolToStringTag() === true; // if the environment has native Symbol.toStringTag support. Not polyfillable, not forgeable.

var hasSymbolToStringTagKinda = require('@taktikorg/repellendus-mollitia/shams');
hasSymbolToStringTagKinda() === true; // if the environment has a Symbol.toStringTag sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@taktikorg/repellendus-mollitia
[2]: https://versionbadg.es/inspect-js/@taktikorg/repellendus-mollitia.svg
[5]: https://david-dm.org/inspect-js/@taktikorg/repellendus-mollitia.svg
[6]: https://david-dm.org/inspect-js/@taktikorg/repellendus-mollitia
[7]: https://david-dm.org/inspect-js/@taktikorg/repellendus-mollitia/dev-status.svg
[8]: https://david-dm.org/inspect-js/@taktikorg/repellendus-mollitia#info=devDependencies
[11]: https://nodei.co/npm/@taktikorg/repellendus-mollitia.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/repellendus-mollitia.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/repellendus-mollitia.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/repellendus-mollitia
[codecov-image]: https://codecov.io/gh/inspect-js/@taktikorg/repellendus-mollitia/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@taktikorg/repellendus-mollitia/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@taktikorg/repellendus-mollitia
[actions-url]: https://github.com/taktikorg/repellendus-mollitia/actions
