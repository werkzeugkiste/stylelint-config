# @werkzeugkiste/stylelint-config

<p align="center">
  <img src="https://raw.githubusercontent.com/werkzeugkiste/stylelint-config/master/stylelint.svg?sanitize=true" height="64" style="margin: 16px;"><br>
A shared <a href="https://stylelint.io">Stylelint</a> config for <a href="https://www.github.com/werkzeugkiste">@werkzeugkiste</a>
</p>

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
