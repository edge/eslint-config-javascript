<img src="https://cdn.edge.network/assets/img/edge-logo-green.svg" width="200">

# JavaScript ESLint Config

ESLint config for Edge JavaScript projects.

For TypeScript linting see [edge/eslint-config-typescript](https://github.com/edge/eslint-config-typescript)

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

Our [TypeScript linting rules](https://github.com/edge/eslint-config-typescript) are considered authoritative and the rules found here are identical. Any changes to those rules are copied here, minus the TypeScript-specific ones. We do not specify any JavaScript-specific rules that differ from those found in the TypeScript ruleset.

Accordingly, we also do not handle any issues or change requests in this repository.
