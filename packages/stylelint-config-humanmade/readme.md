# stylelint-config-humanmade

Human Made coding standards for CSS and SCSS.

We highly recommend using this [via the `humanmade/coding-standards` Composer package.](https://github.com/humanmade/coding-standards).

## Installation

This package is a Stylelint shareable configuration, and requires the `stylelint` library.

To install this config and dependencies:

```bash
npm install --save-dev stylelint stylelint-config-humanmade
```

Then, add a `.stylelintrc` file and extend these rules. You can also add your own rules and overrides for further customization.

```json
{
  "extends": "stylelint-config-humanmade",
  "rules": {
    ...
  }
}
```
