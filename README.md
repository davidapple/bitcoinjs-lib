# BitcoinJS For Browsers (bitcoinjs-lib-for-browsers)
[![Build Status](https://travis-ci.org/bitcoinjs/bitcoinjs-lib.png?branch=master)](https://travis-ci.org/bitcoinjs/bitcoinjs-lib)
[![NPM](https://img.shields.io/npm/v/bitcoinjs-lib.svg)](https://www.npmjs.org/package/bitcoinjs-lib)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

A javascript Bitcoin library for node.js and *ACTUALLY FOR BROWSERS*.

Released under the terms of the [MIT LICENSE](LICENSE).

## Installation For Browsers

```bash
bower install bitcoinjs-lib-for-browsers#4.0.2 --save
```

## Usage

```html
<script src="bower_components/bitcoinjs-lib-for-browsers/dist/bitcoinjs-lib-4.0.2.min.js"></script>
```

## Should I use this in production?
The *master* branch represents stable version 4.0.2.

## Can I trust this code?
The [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) developers are very responsible and very security conscious. They recommend every bitcoinjs user audit and verify any underlying code for its validity and suitability. Their motto is:

> Don't trust. Verify.

Their insistence on user verification has caused them not to include a compiled and minified distrubution of their js library for the browser.

As noble as this is; it is massively inconvenient for developers wishing to use [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) quickly in the browser, without having to install a long list of dependancies and learn the intricacies of [Browserify](https://github.com/substack/node-browserify).

I believe that if you understand the risks of using a pre-compiled version of [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib), there is no reason why this shouldn't be made freely available. [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) should not be restricted to developers running node servers and elitist developers that are able to compile it.

## For More Information
For more information and examples, please visit [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib)

## LICENSE [MIT](LICENSE)
