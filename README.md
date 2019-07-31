# @werkzeugkiste/stylelint-config [alpha]

A shared [Stylelint](https://stylelint.io) config for [@werkzeugkiste](https://www.github.com/werkzeugkiste).

## Installation

Get started by running this command in the root of your project:

```sh
yarn add --dev @werkzeugkiste/stylelint-config
```

```sh
npm install --save-dev @werkzeugkiste/stylelint-config
```

Afterwards install all `peerDependencies` into your project:

```sh
npx install-peerdeps --dev @werkzeugkiste/stylelint-config
```

Then add an `.stylelint.json` file to the root of your project before running the eslint command, with the following content

```json
{
  "extends": ["@werkzeugkiste/stylelint-config"]
}
```

For more information see: https://stylelint.io/user-guide/configuration#extends
