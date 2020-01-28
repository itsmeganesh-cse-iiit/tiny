# @itsmeganeshcse/tiny

[![npm version](https://img.shields.io/npm/v/@itsmeganeshcse/tiny.svg)](https://www.npmjs.com/package/@itsmeganeshcse/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@itsmeganeshcse/tiny.svg)](https://www.npmjs.com/package/@itsmeganeshcse/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @itsmeganeshcse/tiny
```

## Usage

```js
const tiny = require("@itsmeganeshcse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

