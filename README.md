# js-interop

Evaluates a given expression and returns it.

> For example, it is very useful if you want to import a library but it is not yet available server-side (SSR).

![npm](https://img.shields.io/npm/v/@honeybee-js/js-interop?style=flat-square)
![npm](https://img.shields.io/npm/dt/js-interop?style=flat-square)
![npm bundle size](https://img.shields.io/bundlephobia/min/@honeybee-js/js-interop?style=flat-square)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square)](https://standardjs.com)

## Install

```bash
npm i --save @honeybee-js/js-interop
```

```bash
yarn add @honeybee-js/js-interop
```

## Usage

```jsx
import { _interop } from 'js-interop'
```

```jsx
/* Example NextJs */
import { _interop } from 'js-interop'
import styled from 'styled-components'

export const StyledComponent = _interop(styled).div`
  background: pink;
  color: black;
  ...
`

```

## License

MIT © [Samline](https://github.com/samline)
