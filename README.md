# White Hat Gaming FE Linting Tools

## TSLint
### Install
To install this package to your local project run the following npm command

```bash
npm install tslint typescript @burrowsyr/lint-rules --save-dev
```

if you receive a 404 error when installing make sure you are logged into npm and your .npmrc file has an auth token which is valid for the burrows repo.

### Usage
In your projects root create a file called tslint.json add the following contents to get the base tslint rules.

```json
{
  "extends": "./node_modules/@burrowsyr/lint-rules/tslint/whg-lint-rules.json",
  "rules": {}
}
```

Alternate packages which can also be added are listed below
* **tslint-common** - all base rules required to conform to our coding guidelines
* **tslint-angular** - all rules requried for angular projects 
