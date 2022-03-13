# codi.pro prettier config

## Install

```
$ npx install-peerdeps --dev @codi.pro/prettier-config
```

## Usage

Reference it in `package.json` using the `prettier` property:

```js
{
  "prettier": "@codi.pro/prettier-config",
  "devDependencies" : {
    "@codi.pro/prettier-config": "^1.0.0"
  }
}
```

To extend a configuration you will need to create `.prettierrc.js` file:
```js
// .prettierrc.js
module.exports = {
    ...require('@codi.pro/prettier-config'),

    // Additional, per-project rules...
};
```
