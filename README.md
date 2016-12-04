# eslint-config-eshinse

Configuration:

* ES2017
* ESLint core rules.

Peer dependencies:

* [eslint](https://github.com/eslint/eslint)

## Install

`npm install --save-dev eslint-config-eshinse`

## Use

The order of the extensions matter; each additional configuration extends the preceding configurations.

**.eslintrc.yaml:**

```
---

extends:
  - eshinse
  - eshinse-jsdoc
  - eshinse-react
  - eshinse-react-native
```

**.eslintrc.json:**

```json
{
  "extends": [
    "eshinse",
    "eshinse-jsdoc",
    "eshinse-react",
    "eshinse-react-native"
  ]
}
```

## Licence (Apache-2.0)

See [LICENCE](LICENCE).

## Additional ESLint configs

* [eslint-config-eshinse-jsdoc](https://github.com/eshinse/eslint-config-eshinse-jsdoc)
* [eslint-config-eshinse-react](https://github.com/eshinse/eslint-config-eshinse-react)
* [eslint-config-eshinse-react-native](https://github.com/eshinse/eslint-config-eshinse-react-native)
