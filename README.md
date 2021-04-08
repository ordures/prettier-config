# `@ordures/prettier-config`

> ordures project Prettier config

## Usage

**Install**:

```bash
$ yarn add -D @ordures/prettier-config
or
$ npm install @ordures/prettier-config --dev
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@ordures/prettier-config"
}
```

**Edit `.prettierrc.js`**:

```js
module.exports = {
  ...require("@ordures/prettier-config"),
  semi: false,
};
```
