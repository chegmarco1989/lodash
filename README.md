# lodash v4.17.9

The [Lodash](https://lodash.com/) library exported as [Node.js](https://nodejs.org/) modules.

## Installation

Using npm:
```shell
$ npm i -g npm
$ npm i --save lodash
```

In Node.js:
```js
// Load the full build.
var _ = require('lodash');
// Load the core build.
var _ = require('lodash/core');
// Load the FP build for immutable auto-curried iteratee-first data-last methods.
var fp = require('lodash/fp');

// Load method categories.
var array = require('lodash/array');
var object = require('lodash/fp/object');

// Cherry-pick methods for smaller browserify/rollup/webpack bundles.
var at = require('lodash/at');
var curryN = require('lodash/fp/curryN');
```

See the [package source](https://github.com/lodash/lodash/tree/4.17.9-npm) for more details.

**Note:**<br>
Install [n_](https://www.npmjs.com/package/n_) for Lodash use in the Node.js < 6 REPL.

## Support

Tested in Chrome 63-64, Firefox 57-58, IE 11, Edge 14, Safari 10-11, Node.js 4-9, & PhantomJS 2.1.1.<br>
Automated [browser](https://saucelabs.com/u/lodash) & [CI](https://travis-ci.org/lodash/lodash/) test runs are available.
