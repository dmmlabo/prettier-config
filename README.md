# @dmmlabo/prettier-config

## Usage

**Install**
```
npm i @dmmlabo/prettier-config -D

yarn add @dmmlabo/prettier-config -D
```

**Edit** `package.json`:

```
{
  // ...
  "prettier": "@dmmlabo/prettier-config"
}
```

**Edit (if you need overwrite rules)** : `.prettierrc.js`
```js
const config = require("@dmmlabo/prettier-config");

module.exports = {
  ...config,
  semi: false
};
```

Like the example below:
[Prettier - Configuration File](https://prettier.io/docs/en/configuration.html)
