# remove-json-extension [![Build Status](https://secure.travis-ci.org/johnotander/remove-json-extension.png?branch=master)](https://travis-ci.org/johnotander/remove-json-extension) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

Remove the json extension from a path.

## Installation

```bash
npm install --save remove-json-extension
```

## Usage

```javascript
var removeJsonExtension = require('remove-json-extension')

removeJsonExtension('some/json/file.json')  // => 'some/json/file'
removeJsonExtension('some/json/file.JSON')  // => 'some/json/file'
removeJsonExtension('foo/bar.js')  // => 'foo/bar.js'
```

## License

MIT

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by John Otander ([@4lpine](https://twitter.com/4lpine)).

***

> This package was initially generated with [yeoman](http://yeoman.io) and the [p generator](https://github.com/johnotander/generator-p.git).
