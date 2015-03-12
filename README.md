# Performance Platform - Javascript style configs

Centralised configs for JSHint and JSCS style-checking.

JSHint is focussed around code correctness more logic-based checks.

JSCS is about code style, eg use of braces whitespace and indentation.

To install these configs as an NPM module in your own project:

```
npm install performanceplatform-js-style-configs
```

## JSHint

There are two separate JSHint config files:
- .jshintrc-node - for Node projects so the list of assumed globals doesn't include those for a browser environment eg window, document
- .jshint-browser - allows browser globals

To install JSHint globally:

```
npm install jshint -g
```

To run JSHint from the root of the host project:

```
jshint --config ./node_modules/performanceplatform-js-style-configs/.jshintrc-browser.json
```

## JSCS

Javascript code style checking.
- .jscrc

