# ThunderNetworkRaD's Readline-Sync

[![npm](https://img.shields.io/npm/v/@thundernetworkrad/readline-sync.svg)](https://www.npmjs.com/package/readline-sync) [![GitHub issues](https://img.shields.io/github/issues/thundernetworkrad/readline-sync.svg)](https://github.com/thundernetworkrad/readline-sync/issues) [![dependencies](https://img.shields.io/badge/dependencies-No%20dependency-brightgreen.svg)](package.json) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

[Original Version](https://www.npmjs.com/package/readline-sync)

## Inputs
- Simple


### Simple
```js
var readlineSync = require('@thundernetworkrad/readline-sync');
 
var userName = readlineSync.question('Username ');
console.log('Hi ' + userName + '!');
 
var password = readlineSync.question('Password ', {
  hideEchoBack: true // The typed text on screen is hidden by `*`.
});

console.log('You logged in as ' + userName + ' with your password *********');
```

@thundernetworkrad/readline-sync