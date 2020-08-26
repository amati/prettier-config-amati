# prettier-config-amati

personal [prettier](https://prettier.io/) setting

## Install

```shell
$ npm install --save-dev prettier-config-amati
```

## Usage

### edit `package.json`

```json
{
  // ...
  "prettier": "prettier-config-amati"
}
```

### edit `.prettierrc.json`

```json
"prettier-config-amati"
```

### edit `prettier.config.js` or `.prettierrc.js`:

```js
module.exports = {
  ...require('prettier-config-amati'),
  // optional overrides
};
```
