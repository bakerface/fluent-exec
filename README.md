[![Build Status](https://travis-ci.org/bakerface/fluent-exec.svg?branch=master)](https://travis-ci.org/bakerface/fluent-exec) [![Coverage Status](https://coveralls.io/repos/bakerface/fluent-exec/badge.svg?branch=master)](https://coveralls.io/r/bakerface/fluent-exec)

# fluent-exec
**A fluent interface for shell execution in Node.js**

``` javascript
var exec = require('fluent-exec');

exec.command('echo your command')
  .then(function(stdout) {
    // the command was successful
  })
  .catch(function(reason) {
    // an error occurred
  });
```
