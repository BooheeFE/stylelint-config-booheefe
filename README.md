# stylelint-config-booheefe

[![npm](https://img.shields.io/npm/v/stylelint-config-booheefe.svg)](https://www.npmjs.com/package/stylelint-config-booheefe)
[![npm](https://img.shields.io/npm/dt/stylelint-config-booheefe.svg)](https://www.npmjs.com/package/stylelint-config-booheefe)
[![GitHub license](https://img.shields.io/github/license/BooheeFE/stylelint-config-booheefe.svg)](https://github.com/BooheeFE/stylelint-config-booheefe/blob/master/LICENSE)

This package provides BooheeFE's base JS .stylelintrc as an extensible shared config.

## Usage

Our default export contains all of our stylelint rules.

First, install this package
```sh
yarn add --dev stylelint-config-booheefe stylelint

or

npm install --save-dev stylelint-config-booheefe stylelint
```
Then add following contents to your .stylelintrc file
```
{
  "extends": "stylelint-config-booheefe"
}
```

## License

[**The MIT License**](LICENSE).
