# commitlint-config-gain

shareable config for commitlint

[![license](https://img.shields.io/github/license/GainCompliance/commitlint-config-gain.svg)](LICENSE)
[![npm](https://img.shields.io/npm/v/commitlint-config-gain.svg)](https://www.npmjs.com/package/commitlint-config-gain)

[![Build Status](https://img.shields.io/travis/com/GainCompliance/commitlint-config-gain/master.svg?style=flat)](https://travis-ci.com/GainCompliance/commitlint-config-gain)

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

This config extends [commitlint-config-travi](https://github.com/travi/commitlint-config-travi)

## Usage

### Installation

```sh
$ npm install commitlint-config-gain -D
```

### Define the config for your project

```sh
$ echo "module.exports = {extends: ['gain']};" > .commitlintrc.js
```

### Define the npm script for [husky](https://github.com/typicode/husky)

```json
{
  "scripts": {
    "commitmsg": "commitlint -e"
  }
}
```

[dependabot-link]: https://dependabot.com/

[dependabot-badge]: https://badgen.net/dependabot/GainCompliance/commitlint-config-gain/?icon=dependabot
