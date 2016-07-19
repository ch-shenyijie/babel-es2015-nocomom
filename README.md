# babel-preset-es2015-nocommom

> Babel preset for all es2015 plugins but babel-plugin-transform-es2015-modules-commonjs.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-nocommom
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-nocommom"]
}
```

### Via CLI


### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-nocommom"]
});
```
