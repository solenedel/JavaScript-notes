## Require vs import

- `require()` and `import()` are two ways of fetching modules to be used in our code.
- a **module** contains JS code and is more or less the same as a library. 
- using modules means less lines or code and more simplicity since we make use of thirs-party code that is neatly packaged into functions.


### 1) require
- in NodeJS, **require** is a built-in function that lets us use external modules that exist in separate files. 
- a require() statement basically reads a JavaScript file, executes it, and then proceeds to return the export object.

- require is 

`const express = require('express')`


### 2) import (and export)
- **import()** & **export()** statements are used to refer to an ES (.js) module. 
- Other modules with file types such as .json cannot be imported with these statements. 

`const express = import('express')`
OR
`import express from 'express'`

## Differences between require and import

One of the major differencesis that **require() can be called from anywhere** inside the program whereas import() cannot be called conditionally, it **always runs at the beginning** of the file.


### More reading 
- https://www.positioniseverything.net/javascript-import-vs.-require
