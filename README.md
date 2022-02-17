
# React ESLint config

[ESLint](https://eslint.org) configuration shared for [React](https://reactjs.org/) projects written in [TypeScript](https://www.typescriptlang.org/) and using [prettier](https://prettier.io/).

## Installation

First, install this module running:

```bash
npm install @custom/eslint-config-react --save-dev
```

Then, create a `.eslintrc.json` file:

```json
{
  "extends": "@custom/eslint-config-react"
}
```

## Usage

In your `package.json` file, add a script:

```json
{
  "lint": "eslint **/*.{js,jsx,ts,tsx}"
}
```
