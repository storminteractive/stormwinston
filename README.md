## stormwinston
Preconfigured winston with syntax coloring and file logging
## Usage sample:
From command line:
```
npm i stormwinston
```
Then from the code: 
```
const l = require('stormwinston')('winston-test');

l.error("This is an error message");
l.debug("And this will be debug message");
