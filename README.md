# eslint-plugin-plugin-path-checker

plugin for fsd

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-plugin-path-checker`:

```sh
npm install eslint-plugin-plugin-path-checker --save-dev
```

## Usage

Add `plugin-path-checker` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "plugin-path-checker"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "plugin-path-checker/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here


