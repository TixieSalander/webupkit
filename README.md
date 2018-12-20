## VScode plugins

* https://github.com/mrmlnc/vscode-csscomb
* https://github.com/Microsoft/vscode-eslint
* https://github.com/vuejs/vetur
* https://github.com/mikestead/vscode-dotenv
* https://github.com/bmewburn/vscode-intelephense
* https://github.com/onecentlin/laravel-blade-snippets-vscode

## Sketch plugins

* https://www.sketchapp.com/extensions/plugins/svgo-compressor/

## ESLint

### no-unusued-vars with global vars

When you define a class used in another file, you need to set the /* exported variableName */ comment block to indicate that this variable is being exported and therefore should not be considered unused.

```js
/* exported MyClass */
let MyClass = (function() {
  class MyClass {
    ...
  }
  
  return MyClass
})()
```
