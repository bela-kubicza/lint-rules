# White Hat Gaming FE Linting Tools

## TSLint
### Install
To install this package to your local project run the following npm command

```bash
npm install tslint typescript @bela.kubicza/lint-rules --save-dev
```

### Usage
In your projects root create a file called tslint.json add the following contents to get the base tslint rules.

```json
{
  "extends": "./node_modules/@bela.kubicza/lint-rules/tslint/whg-lint-rules.json",
  "rules": {}
}
```
