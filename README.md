# def-helper

> A collection of functions and methods to make it easier for you to create applications.

[![NPM](https://img.shields.io/npm/v/def-helper.svg)](https://www.npmjs.com/package/def-helper) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save def-helper
```

## Usage

```tsx
import { slugify, validateEmail, validatePhone } from 'def-helper'

const slug = slugify('Hello World')
// result will be "hello-world"

const email = validateEmail('user@mail.com')
// result will be true

const phone = validatePhone('08123456789')
// result will be true
```

## License

MIT © [defuj](https://github.com/defuj)
