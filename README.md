[![maintenance](https://img.shields.io/badge/maintained-no-red.svg?style=flat-square)](http://unmaintained.tech)
[![npm](https://img.shields.io/npm/v/eslint-config-rebem.svg?style=flat-square)](https://www.npmjs.com/package/eslint-config-rebem)

[ESLint Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs).

```sh
npm i -D eslint-config-rebem babel-eslint eslint-plugin-babel eslint-plugin-react
```

```js
// .eslintrc
{
  "extends": [
    "rebem/configs/common",
    "rebem/configs/babel",
    "rebem/configs/react",
    "rebem/configs/test"
  ],
  "rules": {
    // custom tweaks
  }
}
```

If working with React config, install `eslint-plugin-react@4.0.0` or above.
