> this package has been moved to https://github.com/zkochan/packages/tree/master/path-temp

# path-temp

> Returns a unique temp file name inside the specified folder

<!--@shields('npm', 'travis')-->
[![npm version](https://img.shields.io/npm/v/path-temp.svg)](https://www.npmjs.com/package/path-temp) [![Build Status](https://img.shields.io/travis/zkochan/path-temp/master.svg)](https://travis-ci.org/zkochan/path-temp)
<!--/@-->

Useful when there's a need to do atomic operations. The temp name contains the
process ID.

## Installation

```sh
npm i -S path-temp
```

## Usage

```js
const pathTemp = require('path-temp')

console.log(pathTemp(process.cwd()))
//> "/home/zkochan/src/path-temp/_tmp_17230_cf3396bb9fddb8ebb30807366facf123"
```

## License

[MIT](./LICENSE) © [Zoltan Kochan](https://www.kochan.io/)
