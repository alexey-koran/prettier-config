# `@alexey-koran/prettier-config`

Prettier [sharing configuration](https://prettier.io/docs/en/configuration.html#sharing-configurations)

### Installation

```bash
pnpm i -D @alexey-koran/prettier-config
```

### Usage

prettier.config.mjs

```js
import { mjs } from '@alexey-koran/prettier-config';

/** @type {import('prettier').Config} */

export default {
  ...mjs,
};
```

### [Example](https://github.com/alexey-koran/react-template/blob/main/prettier.config.mjs)
