# Corllete ES6 snippets

Javascript ES6 snippets for [Visual Studio Code][code] editor following the eslint rules of Corllete (coding standards). It's a work
in progress.

## Supported languages

* Javascript (.js)
* Javascript React (.jsx, js)

## Snippets

List of all available snippets and names (triggers) for each one of them.

### Import and export
| Name    | Content |
| ------: | ------- |
| `imp`   | Import module default `import name from 'name'` |
| `impn`  | Import named `import { name } from 'name'` |
| `impdn` | Import default and named `import name, { other } from 'name'` |
| `impg`  | Import global `import 'name'` |
| `impa`  | Import all with alias `import * as aliasName from 'name'` |
| `impal` | Import default with alias `import { name as aliasName } from 'name'` |

### Functions
| Name    | Content |
| ------: | ------- |
| `arrs`  | Simple arrow function `arg => value` |
| `arrsb` | Simple arrow function with more than one argument `(arg1, arg2) => arg1 + arg2` |
| `arrsd` | Simple arrow function with argument destruct `({ name }) => name.trim()` |
| `arr`   | Multi line arrow function with one argument and return expression only `arg => ( ret )` |
| `arrb`  | Multi line arrow function with more than one argument and return expression only `(arg1, arg2) => ( ... multi-line expr ... )` |
| `arrd`  | Multi line arrow function with argument destruct and return expression only `({ name }) => ( ... multi-line expr ... )` |
| `arro`  | Multi line arrow function with one argument and return object expression `arg => ({ key: value })` |
| `arrbo` | Multi line arrow function with more than one argument and return object `(arg1, arg2) => ({ ... multi-line object ... })` |
| `arrdo` | Multi line arrow function with argument destruct and return object expression `({ name }) => ({ ... multi-line object ... })` |
| `arrf`  | Full arrow function with body `({ name }) => { ... multi-line expression ... }` |
| `arrfd` | Full arrow function with argument destruct and body `({ name }) => { ... multi-line expression ... }` |


> Tip: To use a snippet in VSCode type the snippet name and hit Tab.

## Release Notes

### 0.0.1

Initial release of ES6 snippets

[code]: https://code.visualstudio.com