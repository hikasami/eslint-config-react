# ESLint Config React
This package provides the Hikasami ESLint and Prettier configuration.

## ESLint

[ESLint](https://eslint.org/) statically analyzes your code to quickly find problems. ESLint is built into most text editors and you can run ESLint as part of your continuous integration pipeline.

## Prettier

[Prettier](https://prettier.io/) is an opinionated code formatter. It removes original styling and ensures that all outputted code conforms to a consistent style.

## Installation

The Hikasami ESLint config is available as an [NPM package](https://www.npmjs.com/package/@hikasami/eslint-config-react).

```
// npm
npm install @hikasami/eslint-config-react

// bun
bun install @hikasami/eslint-config-react
```

In the root of your project create the following files:

_.eslintrc.js_

```js
module.exports = {
  extends: ['@hikasami/eslint-config-react'],
}
```

_.prettier.config.js_

```js
module.exports = require('@hikasami/eslint-config-react/prettier.config.js')
```

## License

The Hikasami Development is licensed under the [Apache License 2.0](https://github.com/hikasami/eslint-config-react/blob/master/LICENSE).
