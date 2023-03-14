# @valtech-commerce/optimizely-config

[![npm][npm-badge]][npm-url]
[![npms.io: Score][npmsio-badge]][npmsio-url]
[![libraries.io: SourceRank][librariesio-badge]][librariesio-url]
[![Tests][tests-badge]][tests-url]
[![License: MIT][license-badge]][license-url]

> Opinionated Optimizely configurations.

## Configurations

| config                               | Description                  |
| ------------------------------------ | ---------------------------- |
| [eslint](config/eslintrc.yaml)       | Configurations for ESLint    |
| [prettier](config/prettierrc.yaml)   | Configurations for Prettier  |
| [stylelint](config/stylelintrc.yaml) | Configurations for stylelint |

## Install

```
$ npm install @valtech-commerce/optimizely-config
```

## Usage for ESLint

Add some ESLint config to your `.eslintrc.cjs`:

```js
module.exports = {
	...require("@valtech-commerce/optimizely-config/eslint"),
};
```

### Used plugin / configuration

- [@valtech-commerce/react](https://github.com/valtech-commerce/eslint-config) - Valtech_Commerce base React.js rules
- [@valtech-commerce/typescript](https://github.com/valtech-commerce/eslint-config) - Valtech_Commerce base TypeScript rules

## Usage for Prettier

Add some Prettier config to your `.prettierrc.cjs`:

```js
module.exports = {
	...require("@valtech-commerce/optimizely-config/prettier"),
};
```

## Usage for stylelint

Add some stylelint config to your `.stylelintrc.cjs`:

```js
module.exports = {
	...require("@valtech-commerce/optimizely-config/stylelint"),
};
```

### Used plugin / configuration

- [@valtech-commerce/core](https://github.com/valtech-commerce/stylelint-config) - Valtech_Commerce base rules

## Documentation

See the [Changelog](CHANGELOG.md) to see what has changed.

## Contribute

See the [Contributing Guidelines](CONTRIBUTING.md) for ways to get started.

See the [Support Guide](SUPPORT.md) for ways to get help.

See the [Security Policy](SECURITY.md) for sharing vulnerability reports.

This project has a [Code of Conduct](CODE_OF_CONDUCT.md).
By interacting with this repository, organization, or community you agree to abide by its terms.

## License

[MIT](LICENSE) © [Valtech Canada inc.](https://www.valtech.ca/)

[npm-badge]: https://img.shields.io/npm/v/@valtech-commerce/optimizely-config?style=flat-square
[npmsio-badge]: https://img.shields.io/npms-io/final-score/@valtech-commerce/optimizely-config?style=flat-square
[librariesio-badge]: https://img.shields.io/librariesio/sourcerank/npm/@valtech-commerce/optimizely-config?style=flat-square
[tests-badge]: https://img.shields.io/github/actions/workflow/status/valtech-commerce/optimizely-config/tests.yaml?style=flat-square&branch=main
[license-badge]: https://img.shields.io/badge/license-MIT-green?style=flat-square
[npm-url]: https://www.npmjs.com/package/@valtech-commerce/optimizely-config
[npmsio-url]: https://npms.io/search?q=%40valtech-commerce%2Foptimizely-config
[librariesio-url]: https://libraries.io/npm/@valtech-commerce%2Foptimizely-config
[tests-url]: https://github.com/valtech-commerce/optimizely-config/actions/workflows/tests.yaml?query=branch%3Amain
[license-url]: https://opensource.org/licenses/MIT
