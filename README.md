# @davidxhk/prettier-config

> My personal Prettier [shareable config](https://prettier.io/docs/en/configuration.html#sharing-configurations).

## Installation

```bash
$ npm install --save-dev @davidxhk/prettier-config
```

## Usage

**`package.json`**

```json
{
  // ...other properties
  "prettier": "@davidxhk/prettier-config"
}
```

or

**`.prettierrc.json`**

```json
"@davidxhk/prettier-config"
```

or

**`prettier.config.js`**

```js
import config from "@davidxhk/prettier-config"

export default {
  ...config,
  // ...other configs
}
```
