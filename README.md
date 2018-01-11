# get-chrome

> Find Google Chrome's local path based on current system.

## Introduction
This module provide simple method which returns local chrome path depending on platforms.

This codes are based on `chrome-finder` of [chrome-launcher](https://github.com/GoogleChrome/chrome-launcher) module.

## Supports
Supports 4 platforms: darwin, linux, win32, wsl

The 3 platforms(darwin, linux, win32) are detected from nodejs envrionment variable `process.platform`.

## Simple usage

```js
var getChrome = require('getChrome');
console.log(getChrome());
```

Based on anthoer platform like macOS.

```js
var getChrome = require('getChrome');
console.log(getChrome('darwin'));
```
