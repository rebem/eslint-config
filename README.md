[![npm](https://img.shields.io/npm/v/eslint-config-yummies.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-yummies)

[ESLint Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs).

```sh
npm i -D eslint-config-yummies eslint-plugin-babel babel-eslint eslint-plugin-react
```

```js
// .eslintrc
{
  "extends": [
    "yummies/configs/common",
    "yummies/configs/babel",
    "yummies/configs/react"
  ],
  "rules": {
    // custom tweaks
  }
}
```
