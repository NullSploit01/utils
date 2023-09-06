# @teteu/utils
[![npm (scoped)](https://img.shields.io/npm/v/@teteu/utils?label=%40teteu%2Futils&style=for-the-badge)](https://www.npmjs.com/package/@teteu/utils)

✨ Library to commonly used cross-projects utilities methods ✨

## Run
```bash
npm install @teteu/utils --save
```

## Usage
```js
const utils = require('@teteu/utils');

utils.random(10, 20); // should return a random number between 10 and 20
```

## Contribute
Feel free to contribute. Check if we have open issues or request your utility method. Your code here is very welcome 🤝🤝

## Methods Docs
### Arrays
|Method|What It Does|Parameters|Return|
|-|-|-|-|
|uniqueElements|Returns an array with unique elements| (array: any[]) | {any[]}|
|groupBy|Returns an array grouped by the given key| (array: T[], key: keyof T) | {Record<string, T[]>}|
