# @bobyzgirlllnpm/fugiat-amet-minus <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Returns an array of Typed Array names that are available in the current environment.

## Example

```js
var availableTypedArrays = require('@bobyzgirlllnpm/fugiat-amet-minus');
var assert = require('assert');

assert.deepStrictEqual(
	availableTypedArrays().sort(),
	[
		'Int8Array',
		'Uint8Array',
		'Uint8ClampedArray',
		'Int16Array',
		'Uint16Array',
		'Int32Array',
		'Uint32Array',
		'Float32Array',
		'Float64Array',
		'BigInt64Array',
		'BigUint64Array'
	].sort()
);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@bobyzgirlllnpm/fugiat-amet-minus
[2]: https://versionbadg.es/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus.svg
[5]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus.svg
[6]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus
[7]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus/dev-status.svg
[8]: https://david-dm.org/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus#info=devDependencies
[11]: https://nodei.co/npm/@bobyzgirlllnpm/fugiat-amet-minus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/fugiat-amet-minus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/fugiat-amet-minus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/fugiat-amet-minus
[codecov-image]: https://codecov.io/gh/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@bobyzgirlllnpm/fugiat-amet-minus
[actions-url]: https://github.com/bobyzgirlllnpm/fugiat-amet-minus/actions
