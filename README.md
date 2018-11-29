# Toast.js

A JavaScript prototype for Toast messages, forked from: https://ireade.github.io/Toast.js.

This module's external API is very different to its original. In particular, it
exposes a commonjs module interface, rather than using a global, for easier 
integration. This may change over time, but is intended for easier use in 
ES6 projects.

Accordingly, the version has been bumped to 2.*, because the new API deserves a new
major version.

## Basic usage

Installing:

```sh
$ npm install https://github.com/turalt/toast.js
```

Use in your code:

```javascript
const Toast = require('toast.js');
...
new Toast({message: "Hello", type: 'danger'});
```