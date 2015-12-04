# stylelint-config-wordpress
[![NPM version](http://img.shields.io/npm/v/stylelint-config-wordpress.svg)](https://www.npmjs.org/package/stylelint-config-wordpress) [![Travis Build Status](https://img.shields.io/travis/stylelint/stylelint-config-wordpress/master.svg?label=unix%20build)](https://travis-ci.org/stylelint/stylelint-config-wordpress) [![AppVeyor Build Status](https://img.shields.io/appveyor/ci/stylelint/stylelint-config-wordpress/master.svg?label=windows%20build)](https://ci.appveyor.com/project/stylelint/stylelint-config-wordpress)

> WordPress shareable config for stylelint.

Configuration rules to ensure your CSS is compliant with the [WordPress CSS Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/css/).

## Installation

```console
$ npm install stylelint-config-wordpress
```

## Usage

Set your stylelint config to:

```json
{
  "extends": "stylelint-config-wordpress"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to four spaces and turn off the `number-leading-zero` rule:


```json
{
  "extends": "stylelint-config-wordpress",
  "rules": {
    "indentation": [2, 4],
    "number-leading-zero": 0
  }
}
```

## [Changelog](CHANGELOG.md)

## [License](LICENSE)
