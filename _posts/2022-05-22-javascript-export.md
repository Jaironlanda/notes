---
layout: post
title: "Javascript Export"
tags: javascript
---

# How to use `export` in javascript

### What is `export`
The export statement is used when creating JavaScript modules to export live bindings to functions, objects, or primitive values from the module so they can be used by other programs with the import statement. The value of an imported binding is subject to change in the module that exports it. When a module updates the value of a binding that it exports, the update will be visible in its imported value.


### Usage Basic

File `myfunc.js`

```
export default function (a, b) {
  return a + b
}
```

File `main.js`

```
import myNewFunc from './myfunc.js'
console.log(myNewFunc(1, 2));

// output: 3
```

More Info: https://developer.mozilla.org/en-US/docs/web/javascript/reference/statements/export