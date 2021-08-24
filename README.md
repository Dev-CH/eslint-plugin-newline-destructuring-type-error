# eslint-plugin-newline-destructuring-type-error

Example project showcasing type error when using `babel-eslint` parser.

```
TypeError: Cannot read property 'type' of undefined
Occurred while linting /Users/demo/workspace/type-error/src/index.js:7
    at getPropertyString (/Users/demo/workspace/type-error/node_modules/eslint-plugin-newline-destructuring/dist/newline.js:32:14)
    at /Users/demo/workspace/type-error/node_modules/eslint-plugin-newline-destructuring/dist/newline.js:75:73
    at Array.map (<anonymous>)
    at Object.fix (/Users/demo/workspace/type-error/node_modules/eslint-plugin-newline-destructuring/dist/newline.js:75:41)
    at normalizeFixes (/Users/demo/workspace/type-error/node_modules/eslint/lib/linter/report-translator.js:193:28)
    at /Users/demo/workspace/type-error/node_modules/eslint/lib/linter/report-translator.js:364:49
    at Object.report (/Users/demo/workspace/type-error/node_modules/eslint/lib/linter/linter.js:926:41)
    at ObjectPattern (/Users/demo/workspace/type-error/node_modules/eslint-plugin-newline-destructuring/dist/newline.js:190:29)
    at /Users/demo/workspace/type-error/node_modules/eslint/lib/linter/safe-emitter.js:45:58
    at Array.forEach (<anonymous>)
```

Setup
```bash
$ git clone git@github.com:Dev-CH/eslint-plugin-newline-destructuring-type-error.git type-error
$ cd type-error
$ yarn
$ yarn lint
```
