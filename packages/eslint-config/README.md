# Pinetwork-js ESLint config

> ESLint config for Pinetwork-js projects

This repository contains the ESLint configuration used by the packages of Pinetwork-js.

## Installation

You need to install [ESLint](https://eslint.org) with `@pinetwork-js/eslint-config` and others peer dependencies:

```sh
npm i eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-plugin-import eslint-plugin-sonarjs eslint-plugin-unicorn @pinetwork-js/eslint-config -D
# or with Yarn :
yarn add eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-plugin-import eslint-plugin-sonarjs eslint-plugin-unicorn @pinetwork-js/eslint-config -D
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `@pinetwork-js/prettier-config` and others peer dependencies globally.

## Usage

`@pinetwork-js` must be extended when creating packages for Pinetwork-js.

JSON format:

```js
{
	"root": true,
	"extends": ["@pinetwork-js"]
	// ...
}
```

YAML format:

```yaml
root: true
extends: ['@pinetwork-js']
# ...
```
