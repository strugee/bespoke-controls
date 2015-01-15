[![Build Status](https://secure.travis-ci.org/strugee/bespoke-controls.png?branch=master)](https://travis-ci.org/strugee/bespoke-controls) [![Coverage Status](https://coveralls.io/repos/strugee/bespoke-controls/badge.png)](https://coveralls.io/r/strugee/bespoke-controls)

# bespoke-controls

Buttons for controlling slides

## Download

Download the [production version][min] or the [development version][max], or use a [package manager](#package-managers).

[min]: https://raw.github.com/strugee/bespoke-controls/master/dist/bespoke-controls.min.js
[max]: https://raw.github.com/strugee/bespoke-controls/master/dist/bespoke-controls.js

## Usage

This plugin is shipped in a [UMD format](https://github.com/umdjs/umd), meaning that it is available as a CommonJS/AMD module or browser global.

For example, when using CommonJS modules:

```js
var bespoke = require('bespoke'),
	controls = require('bespoke-controls');

bespoke.from('#presentation', [
	controls()
]);
```

When using browser globals:

```js
bespoke.from('#presentation', [
	bespoke.plugins.controls()
]);
```

## Package managers

### npm

```bash
$ npm install bespoke-controls
```

### Bower

```bash
$ bower install bespoke-controls
```

## Credits

This plugin was built with [generator-bespokeplugin](https://github.com/markdalgleish/generator-bespokeplugin).

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
