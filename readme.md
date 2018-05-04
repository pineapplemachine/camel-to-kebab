# camel-to-kebab

[![Build Status](https://travis-ci.org/pineapplemachine/camel-to-kebab-js.svg?branch=master)](https://travis-ci.org/pineapplemachine/camel-to-kebab-js)

This is a JavaScript library implementing one function, **camelToKebabCase**.
It accepts a _camelCase_ string as input and outputs a _kebab-case_ equivalent. It also works for _PascalCase_ inputs.

This library is very lightweight at 827 bytes minified and 431 bytes gzipped. It requires no external dependencies, and it's licensed according to the permissive
[zlib/libpng license](https://github.com/pineapplemachine/camel-to-kebab-js/blob/master/LICENSE).

## Installation

You can add **camelToKebabCase** to your JavaScript project by using a
package manager to install the `camel-to-kebab` package. For example:

``` text
npm install --save camel-to-kebab
```

## Usage

**camelToKebabCase** can be used in the browser, imported as a CommonJS
module, or imported as an ES module.

``` js
// Import camel-to-kebab as a CommonJS module
const camelToKebabCase = require("camel-to-kebab");
```

``` js
// Import camel-to-kebab as an ES module
import camelToKebabCase from "camel-to-kebab";
```

``` html
<!-- Use camel-to-kebab in the browser -->
<script src="camel-to-kebab.min.js"></script>
```

## Examples

``` js
const camelToKebabCase = require("camel-to-kebab");

// prints "hello-world"
console.log(camelToKebabCase("helloWorld"));

// prints "camel-to-kebab-case"
console.log(camelToKebabCase("camelToKebabCase"));

// prints "testing-123"
console.log(camelToKebabCase("testing123"));

// prints "inner-html"
console.log(camelToKebabCase("innerHTML"));

// prints "border-top-left-radius"
console.log(camelToKebabCase("borderTopLeftRadius"));
```
