<img src="https://cdn.edge.network/assets/img/edge-logo-green.svg" width="200">

# JavaScript ESLint Config

ESLint config for Edge JavaScript projects.

For TypeScript config, see [edge/eslint-config-typescript](https://github.com/edge/eslint-config-typescript)

## Usage

Install to your project:

```bash
npm i --save-dev @edge/eslint-config-javascript
```

This package specifies peer dependencies, which [you may need to add manually to your project](https://nodejs.org/en/blog/npm/peer-dependencies/). To do so, run the following in shell at your npm project root:

```bash
npm i --save-dev eslint
```

Afterwards, add the following configuration to your ESLint configuration:

```json
{
  "extends": [
    "@edge/eslint-config-javascript"
  ]
}
```

Finally, configure your npm scripts, IDE, etc. as your project requires.

## Maintenance

For ease of use, this package is maintained separately from our [TypeScript linting rules](https://github.com/edge/eslint-config-typescript).

Our TS rules are considered authoritative, and these JS rules follow. Other than TypeScript-specific rules, this package's rules are identical to those.

We do not handle any issues or change requests in this repository, and any created will be closed without action. To request changes or discuss an issue, do so in the [TypeScript issues](https://github.com/edge/eslint-config-typescript/issues).

## License

Edge is the infrastructure of Web3. A peer-to-peer network and blockchain providing high performance decentralised web services, powered by the spare capacity all around us.

Copyright notice
(C) 2022 Edge Network Technologies Limited <support@edge.network><br />
All rights reserved

This product is part of Edge.
Edge is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version ("the GPL").

**If you wish to use Edge outside the scope of the GPL, please contact us at licensing@edge.network for details of alternative license arrangements.**

**This product may be distributed alongside other components available under different licenses (which may not be GPL). See those components themselves, or the documentation accompanying them, to determine what licenses are applicable.**

Edge is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

The GNU General Public License (GPL) is available at: https://www.gnu.org/licenses/gpl-3.0.en.html<br />
A copy can be found in the file GPL.md distributed with
these files.

This copyright notice MUST APPEAR in all copies of the product!
