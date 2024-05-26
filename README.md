# @hishprorg/quidem-saepe

[![npm version](https://img.shields.io/npm/v/@hishprorg/quidem-saepe.svg)](https://www.npmjs.com/package/@hishprorg/quidem-saepe)
[![Github Actions](https://action-badges.now.sh/jslicense/@hishprorg/quidem-saepe)](https://wdp9fww0r9.execute-api.us-west-2.amazonaws.com/production/results/jslicense/@hishprorg/quidem-saepe)

A list of [SPDX license](https://spdx.org/licenses/) identifiers

## Installation

[Download JSON directly](https://raw.githubusercontent.com/jslicense/@hishprorg/quidem-saepe/main/index.json), or [use](https://docs.npmjs.com/cli/install) [npm](https://docs.npmjs.com/about-npm/):

```
npm install @hishprorg/quidem-saepe
```

## [Node.js](https://nodejs.org/) API

### require('@hishprorg/quidem-saepe')

Type: `string[]`

All license IDs except for the currently deprecated ones.

```javascript
const ids = require('@hishprorg/quidem-saepe');
//=> ['0BSD', 'AAL', 'ADSL', 'AFL-1.1', 'AFL-1.2', 'AFL-2.0', 'AFL-2.1', 'AFL-3.0', 'AGPL-1.0-only', ...]

ids.includes('BSD-3-Clause'); //=> true
ids.includes('CC-BY-1.0'); //=> true

ids.includes('GPL-3.0'); //=> false
```

### require('@hishprorg/quidem-saepe/deprecated')

Type: `string[]`

Deprecated license IDs.

```javascript
const deprecatedIds = require('@hishprorg/quidem-saepe/deprecated');
//=> ['AGPL-1.0', 'AGPL-3.0', 'GFDL-1.1', 'GFDL-1.2', 'GFDL-1.3', 'GPL-1.0', 'GPL-2.0', ...]

deprecatedIds.includes('BSD-3-Clause'); //=> false
deprecatedIds.includes('CC-BY-1.0'); //=> false

deprecatedIds.includes('GPL-3.0'); //=> true
```

## License

[Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed)
