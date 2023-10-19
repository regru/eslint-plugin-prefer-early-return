Copy-paste from `eslint-plugin-shopify` from shopify team without unwanted dependencies and restrictions

## Installation

npm install @regru/eslint-plugin-prefer-early-return --save-dev

## Usage

```
{
  "plugins": [
    "@regru/prefer-early-return",
    …
  ],
  "rules": {
    "@regru/prefer-early-return/prefer-early-return": ["error", {
      "maximumStatements": 1
    }],
    …
  },
  …
}
```

## Plugin-Provided Rule

[prefer-early-return](docs/rules/prefer-early-return.md)
