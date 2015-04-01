# Warning

A mirror of Facebook's Warning

## Usage
```
npm install warning
```

```
// some script
var warning = require('warning');

var ShouldBeTrue = false;

warning(ShouldBeTrue, 'This thing should be true but you set to false. No soup
for you!');
//  'This thing should be true but you set to false. No soup for you!'
```

Similar to Facebook's invariant but only logs a warning if the condition is not met.
This can be used to log issues in development environments in critical
paths. Removing the logging code for production environments will keep the
same logic and follow the same code paths.
