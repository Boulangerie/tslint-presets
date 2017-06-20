[![Build Status](https://travis-ci.org/Boulangerie/tslint-presets.svg?branch=master)](https://travis-ci.org/Boulangerie/tslint-presets)
[![npm version](https://img.shields.io/npm/v/tslint-presets.svg)](https://www.npmjs.com/package/tslint-presets)
[![npm downloads](https://img.shields.io/npm/dm/tslint-presets.svg?style=flat-square)](http://npm-stat.com/charts.html?package=tslint-presets&from=2016-10-01)
[![dependencies](https://david-dm.org/Boulangerie/tslint-presets.svg)](https://david-dm.org/Boulangerie/tslint-presets)
[![npm devDependencies](https://img.shields.io/david/dev/Boulangerie/tslint-presets.svg)](https://david-dm.org/Boulangerie/tslint-presets)
[![npm license](https://img.shields.io/npm/l/tslint-presets.svg)](https://www.npmjs.org/package/tslint-presets)


# TSlint presets

## Usage

### Install from NPM to your Dev Dependencies

```console
npm install --save-dev tslint-presets
```

### Configure TSLint to use `tslint-presets`:

In your `tslint.json` file, extend this package, e.g:

```json
{
  "extends": [
    "tslint-presets"
  ],
  "rules": {
    "no-constant-condition": true
  }
}
```

You can also extend other tslint config packages to combine this plugin with other community custom rules.

