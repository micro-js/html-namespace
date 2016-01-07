
# html-namespace

[![Build status][travis-image]][travis-url]
[![Git tag][git-image]][git-url]
[![NPM version][npm-image]][npm-url]
[![Code style][standard-image]][standard-url]

HTML element namespace URI

## Installation

    $ npm install @f/html-namespace

## Usage

```js
var htmlNs = require('@f/html-namespace')
var svgNs = require('@f/svg-namespace')

function elementType (node) {
  switch (node.namespaceURI) {
    case htmlNs:
      return 'html'
    case svgNs:
      return 'svg'
  }
}
```

## License

MIT

[travis-image]: https://img.shields.io/travis/micro-js/html-namespace.svg?style=flat-square
[travis-url]: https://travis-ci.org/micro-js/html-namespace
[git-image]: https://img.shields.io/github/tag/micro-js/html-namespace.svg
[git-url]: https://github.com/micro-js/html-namespace
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat
[standard-url]: https://github.com/feross/standard
[npm-image]: https://img.shields.io/npm/v/@f/html-namespace.svg?style=flat-square
[npm-url]: https://npmjs.org/package/@f/html-namespace
