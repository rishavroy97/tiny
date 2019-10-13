# @rishavroy97/tiny

[![GitHub issues](https://img.shields.io/github/issues/rishavroy97/tiny)](https://github.com/rishavroy97/tiny/issues)
[![npm (scoped)](https://img.shields.io/npm/v/@rishavroy97/tiny.svg)](https://www.npmjs.com/package/@rishavroy97/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@rishavroy97/tiny.svg)](https://www.npmjs.com/package/@rishavroy97/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```