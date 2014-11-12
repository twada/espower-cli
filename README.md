espower-cli
================================

Command line tool for espower.

[![Build Status][travis-image]][travis-url]
[![NPM version][npm-image]][npm-url]
[![Dependency Status][depstat-image]][depstat-url]
[![License][license-image]][license-url]


DESCRIPTION
---------------------------------------

espower-cli provides an `espower` command which transforms source code by using [espower](http://github.com/twada/espower).

COMMAND LINE USAGE EXAMPLE
---------------------------------------

```
espower test.js > test.espowered.js 
```

```
cat test.js | espower > test.espowered.js 
```

INSTALL
---------------------------------------

### via npm

Install locally,

    $ npm install --save-dev espower-cli

and/or globally.

    $ npm install -g espower-cli


AUTHOR
---------------------------------------
* [Takuto Wada](http://github.com/twada)


LICENSE
---------------------------------------
Licensed under the [MIT](http://twada.mit-license.org/) license.


[npm-url]: https://npmjs.org/package/espower-cli
[npm-image]: https://badge.fury.io/js/espower-cli.svg

[travis-url]: http://travis-ci.org/twada/espower-cli
[travis-image]: https://secure.travis-ci.org/twada/espower-cli.svg?branch=master

[depstat-url]: https://gemnasium.com/twada/espower-cli
[depstat-image]: https://gemnasium.com/twada/espower-cli.svg

[license-url]: http://twada.mit-license.org/
[license-image]: http://img.shields.io/badge/license-MIT-brightgreen.svg
